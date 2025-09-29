# SDG_clinical_ner

[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange.svg)](https://jupyter.org/)

## Overview

This repository contains the code and experiments accompanying the paper:

> **LLM-Based Framework for Synthetic Data Generation in Portuguese Clinical NER**
> Luís Henriques, Nuno Guimarães, Alípio Jorge, 2025
> [Link to paper / preprint / DOI if available]

The primary analysis and results are implemented in Jupyter Notebooks. This repo allows you to reproduce key experiments, explore the methods, and adapt the workflows for your own research.

## Repository Structure

```
├── notebooks/        # Jupyter Notebook with code to generate synthetic records
├── requirements.txt  # Python dependencies
└── README.md
```

## Getting Started

### Prerequisites

* Python 3.8+
* [Jupyter Notebook](https://jupyter.org/) or JupyterLab

### Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/LIAAD/SDG_clinical_ner
cd your-repo-name
pip install -r requirements.txt
```

### Running the Notebooks

Launch Jupyter and open the main notebook:

```bash
jupyter notebook
```

Then navigate to `notebooks/` and run the cells sequentially.


## Citing

If you use this code in your research, please cite the paper:

```
@InProceedings{10.1007/978-3-032-05176-9_26,
author="Henriques, Lu{\'i}s and Guimar{\~a}es, Nuno and Jorge, Al{\'i}pio",
editor="Valente de Oliveira, Jos{\'e} and Leite, Jo{\~a}o and Rodrigues, Jo{\~a}o and Dias, Jo{\~a}o and Cardoso, Pedro",
title="LLM--Based Framework for Synthetic Data Generation in Portuguese Clinical NER",
booktitle="Progress in Artificial Intelligence",
year="2026",
publisher="Springer Nature Switzerland",
address="Cham",
pages="335--347",
isbn="978-3-032-05176-9"
}
```

## Future Work

* Check for depreciated code
* Convert notebooks into standalone Python scripts

