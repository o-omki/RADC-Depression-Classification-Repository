# Reproducibility Notes

## Environment
The notebooks were developed in a Google Colab-style environment and include Colab mount paths in some cells.

## Main Python packages
The notebooks install the following core packages:
- torch
- torchvision
- transformers
- datasets
- scikit-learn
- accelerate
- sentence-transformers
- evaluate

## Data layout
The notebooks expect a local project layout with dataset files and outputs rooted under a project directory. For local reproduction, replace any hardcoded `/content/drive/...` paths with paths valid on your machine.
