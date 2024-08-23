# Hash Table Collision Analysis

## Overview
This project implements a hash table using **MurmurHash** and **DJB2** hashing algorithms, focusing on collision resolution via chaining. The primary goal is to analyze and compare the efficiency and collision rates of these hash functions across various seeds.

## Features
- **MurmurHash**: A high-performance, non-cryptographic hash function.
- **DJB2**: A simple, widely-used hash function.
- **Collision Handling**: Implements chaining for effective collision resolution.
- **Seed Variability**: Evaluates hash function performance with different random seeds.

## Coding Environment

### Miniconda
This project was managed using **Miniconda**, a minimal installer for Conda, providing a customizable Python environment. Miniconda enables efficient management of packages and environments, ensuring a streamlined workflow.

### Jupyter Notebook with Python 3 (IPython Kernel)
The project was developed and tested in **Jupyter Notebook**, using the **Python 3 (IPython kernel)**. This interactive environment allows for modular coding, real-time execution, and debugging, making it ideal for iterative development.

### Python Version
The code was executed using **Python 3**, managed through Conda. The specific version of Python can be verified within the notebook environment.

## Libraries Used
- **mmh3**: A Python wrapper for MurmurHash, installed via Conda or pip.
- **random**: A standard Python library for generating random numbers, used for randomizing seeds and testing collision rates.

## Setup

1. **Create a New Conda Environment:**
   ```bash
   conda create -n hash_env 
    ```
2. **Activate the Environment:**
    ```bash
    conda activate hash_env
    ```
3. **Install Jupyter Notebook:**
    ```bash
    conda install jupyter
    ```
4. **Install Required Libraries:**
    ```bash
    pip install mmh3
    ```

## Running the Code
1. **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
2. Open the relevant notebook file and execute the cells to run the code. This setup provides real-time output visualization and debugging within the notebook environment.    

