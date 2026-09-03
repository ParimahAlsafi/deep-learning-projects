# Machine Translation with Transformers

A Transformer-based English-to-Persian neural machine translation project using pretrained multilingual BERT (mBERT) embeddings and a custom encoder–decoder architecture.

## Key Features

- English–Persian translation using the ParsiNLU dataset
- Custom Transformer encoder–decoder
- Pretrained mBERT token embeddings
- Positional embeddings and multi-head attention
- Padding and causal attention masks
- Masked label-smoothed loss
- Transformer learning-rate warmup
- Beam-search decoding
- Evaluation with BLEU, ROUGE, and BERTScore

## Model Configuration

- Model dimension: 300
- Encoder layers: 2
- Decoder layers: 2
- Attention heads: 6
- Feed-forward dimension: 1024
- Dropout: 0.2

## Technologies

- Python
- TensorFlow / Keras
- Hugging Face Transformers
- Hugging Face Datasets
- multilingual BERT
- ParsBERT
- SacreBLEU
