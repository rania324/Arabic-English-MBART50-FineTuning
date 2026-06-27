# Arabic-English-MBART50-FineTuning
Fine-tuning MBART-50 for Arabic-to-English Neural Machine Translation using the UN Parallel Corpus with Hugging Face Transformers.
# Arabic-to-English Neural Machine Translation using MBART-50

## Overview

This project implements an Arabic-to-English Neural Machine Translation (NMT) system using the MBART-50 multilingual transformer model. The model is fine-tuned on the United Nations (UN) Parallel Corpus using the Hugging Face Transformers library.

## Features

* Fine-Tuning MBART-50
* Arabic-to-English Translation
* Data Preprocessing
* Hugging Face Trainer API
* BLEU Score Evaluation
* PyTorch-based Training

## Dataset

* United Nations (UN) Parallel Corpus
* Source Language: Arabic
* Target Language: English

## Model

* Model: facebook/mbart-large-50
* Tokenizer: MBart50TokenizerFast
* Framework: Hugging Face Transformers

## Technologies

* Python
* PyTorch
* Hugging Face Transformers
* Datasets
* Evaluate
* SacreBLEU
* Pandas

## Training

The model is fine-tuned using the Hugging Face Trainer API with:

* Learning Rate: 3e-5
* Batch Size: 2
* Epochs: 3
* Mixed Precision (FP16)

## Evaluation

The translation quality is evaluated using the BLEU score.

## Installation

```bash
pip install -r requirements.txt
```

## Run

1. Load the UN Parallel Corpus.
2. Preprocess the Arabic-English sentence pairs.
3. Fine-tune MBART-50.
4. Evaluate the model using BLEU.
5. Save the fine-tuned model.

## Future Improvements

* Hyperparameter optimization
* Beam Search decoding
* Larger training datasets
* Additional evaluation metrics such as COMET and chrF
