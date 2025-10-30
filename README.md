# ⚛️ Bernstein-Vazirani Algorithm

A Python implementation of the **Bernstein-Vazirani (BV) algorithm** using **Qiskit**.

---

## 🧐 What is the Bernstein-Vazirani Algorithm?

The Bernstein-Vazirani algorithm is a famous quantum algorithm that demonstrates the potential speedup of quantum computers over classical computers for certain tasks.

It solves a specific oracle problem: **Given an unknown function $f(x) = s \cdot x \pmod{2}$, where $s$ is a secret $n$-bit string, find $s$ in a single query.**

* **Classical Requirement:** A classical computer would need to query the function $f(x)$ up to $n$ times (where $n$ is the number of bits in $s$) in the worst case to determine the secret string $s$.
* **Quantum Speedup:** The Bernstein-Vazirani algorithm uses **quantum parallelism** and the **Hadamard gate** to determine the secret string $s$ with only **one query** to the quantum oracle.

---

## 💻 Prerequisites

To run this code and experiment with the Bernstein-Vazirani algorithm, you will need the following installed:

### 1. Anaconda Environment

It is highly recommended to use an **Anaconda** or **Miniconda** distribution to manage your Python environment and packages.

* **Download:** Get Anaconda from [Anaconda's Official Website](https://www.anaconda.com/download).
* **Jupyter Notebook:** Ensure your Anaconda installation includes **Jupyter Notebook** (or JupyterLab), as the code is typically presented and run within a notebook environment.

### 2. Qiskit

**Qiskit** is the open-source quantum computing software development kit (SDK) used to write and execute quantum circuits.

You can install Qiskit into your environment using **`pip`**:

```bash
pip install qiskit
