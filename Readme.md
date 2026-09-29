# Implementation of Grover's Search Algorithm using Qiskit

## About the Project

This project focuses on implementing **Grover's Search Algorithm using Qiskit** and exploring its application in **cloud resource allocation and optimization**.

In traditional computing, searching an unsorted list requires checking elements one by one, which takes **O(N)** time. Grover's Search Algorithm uses quantum concepts such as **superposition and amplitude amplification** to achieve a theoretical quadratic speedup, requiring approximately **O(√N)** operations.

The project demonstrates how quantum computing can be used to search through possible solutions and explore more efficient approaches to cloud resource management.

## Problem Statement

As the number of users, tasks, and available resources increases, traditional cloud resource allocation can become slow and inefficient.

Some of the main challenges are:

* Increased computation time for large search spaces
* Inefficient resource allocation
* Increased task execution time
* Lower utilization of cloud resources
* Difficulty in handling complex resource allocation problems

This project explores Grover's Search Algorithm as a quantum-based approach for searching possible resource allocation solutions.

## Objectives

* Implement Grover's Search Algorithm using Qiskit.
* Optimize cloud resource allocation.
* Reduce execution time in cloud task scheduling.
* Improve cloud resource utilization.
* Generate and execute quantum circuits.
* Analyze the obtained results.
* Compare quantum-based searching with classical methods.
* Explore the use of quantum computing in cloud resource management.

## How the Algorithm Works

The project follows these basic steps:

```text
User / Optimization Input
          ↓
Define the Problem
          ↓
Generate Search Space
          ↓
Encode the Problem into Qubits
          ↓
Create Quantum Oracle
          ↓
Apply Diffusion Operator
          ↓
Run Quantum Circuit
          ↓
Measure Qubits
          ↓
Analyze the Results
```

The **oracle** marks the required solution, while the **diffusion operator** increases the probability of obtaining the target state.

## Technologies Used

* **Python 3.11+**
* **Qiskit**
* **Jupyter Notebook**
* **FastAPI**
* **React.js**
* **PostgreSQL**
* **SQLite** for development
* **IBM Quantum Cloud**
* **Visual Studio Code**

The initial Stage-I implementation specifically identifies **Qiskit and Jupyter Notebook** as the technologies used.

## Proposed System

The proposed system combines a web application with a quantum optimization module.

```text
User
  ↓
React.js Frontend
  ↓
FastAPI Backend
  ↓
Qiskit Quantum Module
  ↓
Qiskit Simulator / IBM Quantum Cloud
  ↓
Optimization Results
```

PostgreSQL is planned for storing execution history and generated reports.

## Key Features

* Grover's Search Algorithm implementation
* Quantum circuit generation
* Quantum simulation using Qiskit
* Cloud resource allocation optimization
* Optimization result analysis
* Performance analysis
* Execution history and report storage
* Future support for IBM Quantum Cloud

## Functional Requirements

The system is designed to:

* Accept optimization problem inputs.
* Generate quantum circuits using Grover's Algorithm.
* Execute quantum simulations.
* Display optimization results.
* Provide performance analysis.
* Store execution history.
* Generate reports.

## Expected Outcome

The project aims to demonstrate the use of Grover's Search Algorithm for efficient searching and explore how quantum computing can be applied to cloud resource optimization.

It also provides a foundation for developing future **quantum-enabled cloud management systems**.

## Future Scope

Future development may include:

* Running circuits on real quantum hardware
* IBM Quantum integration
* Larger optimization problems
* Advanced cloud scheduling
* Real-time resource allocation
* Performance benchmarking
* Scalable cloud deployment
* Integration with other quantum optimization algorithms

## SDG

**SDG 9 – Industry, Innovation and Infrastructure**

The project is aligned with SDG 9 through its focus on quantum computing, innovation, and improved computational infrastructure.

## Team Members

| Name                   | Roll Number |
| ---------------------- | ----------- |
| **B. Jashwanth**       | 23AG1A0572  |
| **D. Vishnu Vardhan**  | 23AG1A0585  |
| **Shaik Tawfiq Abbas** | 23AG1A05B6  |

**Project Guide:** Mr. V. Chandra Sekhar Reddy, Associate Professor

**Batch:** 11
**Class:** IV B.Tech CSE – B
**Academic Year:** 2026–27

## Project Status

**Major Project Stage – I**

Currently, the project is in the **research, design, and implementation phase**, with the focus on implementing Grover's Search Algorithm using Qiskit and developing the proposed quantum-based cloud optimization platform.
