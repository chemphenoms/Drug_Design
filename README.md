# Drug Design with Deep Reinforcement Learning

This repository contains a Google Collab Notebook (`Drug_design_with_reinforcementlearning.ipynb`) that introduces the application of Deep Reinforcement Learning (DRL) in the de novo design of new drug molecules.

## Author
Ravi Thej Pilla

## Last Modified
30th May 2024

## Overview
This notebook explores how DRL can be leveraged to synthesize novel molecular structures. It provides insights into the reward-based performance of the DRL agent and showcases the corresponding chemical structures generated during the training process.

## Key Features
* **Deep Reinforcement Learning**: Implementation of DRL for molecular design.
* **Molecular Generation**: Focus on generating new drug-like molecules from scratch.
* **SMILES Representation**: Utilizes SMILES (Simplified Molecular Input Line Entry System) strings to encode and represent molecular structures.
* **Performance Evaluation**: Provides methods to evaluate the DRL model's effectiveness in de novo molecular design tasks based on reward performance and generated chemical structures.

## Getting Started

### Prerequisites
To run this notebook, you will need a Python environment with Jupyter and relevant cheminformatics and machine learning libraries (e.g., RDKit, TensorFlow/PyTorch, OpenAI Gym if a custom environment is used). Specific dependencies will be listed within the notebook cells.

### Installation
1.  Clone this repository:
    ```bash
    git clone https://github.com/yourusername/drug-design-drl.git
    cd drug-design-drl
    ```
2.  Install the required Python packages (it is recommended to use a virtual environment):
    ```bash
    pip install -r requirements.txt
    ```
    (Note: A `requirements.txt` file is not explicitly provided in the fetched content, but it's a standard practice for Jupyter notebooks. You might need to create one based on the imports in the notebook. Or you can use Google Collab.)

### Usage
1.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2.  Open the `Drug_design_with_reinforcementlearning.ipynb` file.
3.  Execute the cells sequentially to understand the concepts and run the DRL model for molecular generation.

## Conclusion
The notebook's output provides critical insights into both the reward-based performance of the agent and the corresponding chemical structures it generates, facilitating a comprehensive evaluation of the DRL model's effectiveness in de novo molecular design tasks.
