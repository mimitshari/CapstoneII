# 🧬 AINovelChemStruc 🧬 
AI Novel Chemical Structure

This project focuses on leveraging artificial intelligence and deep generative models, such as RNNs and Transformers, to focus in the field of drug discovery. By synthesizing novel chemical structures and assessing their properties through SMILES string representations, this project aims to advance the capabilities in pharmaceutical development. This repository contains the code and datasets

## Usage
This project includes four main scripts for generating novel chemical structures using different combinations of models and datasets. Below are the steps to run each script:

### 1. Transformer with ChEMBL Dataset
Run the Transformer model trained on the ChEMBL dataset 

### 2. Transformer with DrugBank Dataset
Run the Transformer model trained on the DrugBank dataset:

### 3. RNN with Ligand ChEMBL Dataset
Run the RNN model trained on the Ligand ChEMBL dataset:

### 4. RNN with DrugBank Dataset
Run the RNN model trained on the DrugBank dataset:

## Output and Evaluation
Each script in this project not only generates SMILES strings but also evaluates them to ensure the chemical structures are viable for drug discovery. The evaluation is based on several important criteria:

- **Toxicity Metrics**: The chemical structures are assessed for potential toxicity, which is crucial for determining their safety as pharmaceutical agents.
- **ADME Profiling**: The Absorption, Distribution, Metabolism, and Excretion (ADME) properties of the compounds are analyzed. This profiling helps in understanding how the compounds behave in a biological system, which is essential for drug development.

### Example of Evaluation Output
After generating the SMILES strings, each script will output a summary of the evaluation results. Here is what you might expect:

```json
{
  "SMILES": "CCOc1ccc2nc(S(N)(=O)=O)sc2c1",
  "Toxicity": "Low",
  "ADME": {
    "Absorption": "High",
    "Distribution": "Moderate",
    "Metabolism": "Stable",
    "Excretion": "Normal"
  }
}

