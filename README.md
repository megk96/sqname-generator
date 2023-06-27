# sqname-generator
Sentence Tranformers - a state-of-the-art NLP model for detecting semantic similarity is fine-tuned using a custom dataset of financial reports. 

# Recipebook-Approved SQName Generator
The following expedition explores [Sentence Transformers](https://huggingface.co/sentence-transformers) to suggest a **Recipebook-Approved SQName** which contains the _us-gaap_ namespace for a given Name to prevent redundant generation of derived SQNames from custom tickers. This is an effort towards improving comparability in financial reports. Sentence Transformers are state-of-the-art models for semantic textual similarity. It is meant to be representative of a high-dimensional embedding model that can effectively capture semantic similarity between Names and existing SQNames. 

## Finetuning a Sentence Transformer
The Hugging Face Sentence Transformer is leveraged with a powerful yet lightweight pre-trained model, and then fine-tuned with the dataset provided to serve this specific use-case. 
