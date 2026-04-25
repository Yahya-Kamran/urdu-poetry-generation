# 📜 Urdu Poetry Generation (RNN/LSTM)

[![Framework](https://img.shields.io/badge/Framework-PyTorch-red.svg)](#)
[![Model](https://img.shields.io/badge/Model-RNN_%7C_LSTM-orange.svg)](#)

> Sequence-based text generation designed to mimic the rhythmic and linguistic patterns of classical Urdu poetry.

## 📖 Overview
Generating poetry is a delicate test of a language model's ability to capture syntax, rhythm, and semantic beauty. This NLP project focuses on training Recurrent Neural Networks (and LSTMs) on a rich corpus of classical Urdu literature to generate original, stylistically coherent poetry.

## ✨ Key Features
- **Style Mimicry**: Trained specifically on the nuances of Urdu linguistics, capturing meter and rhyme.
- **Temperature Control**: Implemented adjustable softmax temperature to control the randomness and creativity of the output sequence.
- **Custom Tokenization**: Specialized text preprocessing to handle Urdu characters, spaces, and punctuation correctly.
- **Sequential Learning**: Demonstrates the power of hidden states in preserving contextual memory over long sequences.

## 📁 Repository Structure
```text
.
├── urdu_poetry_generation.ipynb   # Complete pipeline: preprocessing, training, and generation
├── requirements.txt               # Python dependencies
└── README.md                      # Project documentation
```

## 🚀 Setup & Usage
1. Clone the repository.
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook to explore the generation logic and tweak the `temperature` parameter for different poetic styles:
   ```bash
   jupyter notebook urdu_poetry_generation.ipynb
   ```
