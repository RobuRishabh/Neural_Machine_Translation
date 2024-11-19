
# Neural Machine Translation (NMT) Project

This project implements a Neural Machine Translation system using modern deep learning techniques. The goal is to translate text from a source language to a target language using sequence-to-sequence models.

## Features
- Encoder-Decoder architecture with attention mechanisms.
- Support for custom datasets.
- Tokenization and preprocessing pipeline.
- Training, validation, and evaluation scripts.
- BLEU score evaluation for translation quality.

## Table of Contents
1. [Installation](#installation)
2. [Dataset](#dataset)
3. [Model Details](#model-details)
4. [Results](#results)
5. [Acknowledgements](#acknowledgements)
6. [License](#license)
 

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/RobuRishabh/Neural_Machine_Translation.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
- **Source Language:** English (en)
- **Target Language:** French (fr)
- Datasets should be placed in the `data/` directory.
- Supported formats: `txt` or `csv` with each line containing a source-target sentence pair.

## Model Details
- **Architecture:** Encoder-Decoder with Luong Attention.
- **Framework:** PyTorch.
- **Optimizer:** Adam with learning rate scheduling.
- **Loss Function:** Cross-entropy loss with label smoothing.

## Results
- Achieved a BLEU score of **0.097** on the validation set.
- Sample translations:
  - Source: "Hello, how are you?"
  - Target: "Bonjour, comment ça va?"
  - Predicted: "Bonjour, comment allez-vous?"

## Acknowledgements
- The architecture is inspired by [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215).
- Attention mechanism based on [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
