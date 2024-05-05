# Running Gemma-2B-Instruct with Transformers on Google Colab

This repository contains a Google Colab notebook that demonstrates the use of the transformers library by Hugging Face for casual language modeling. The code primarily focuses on interacting with pre-trained language models available through Hugging Face's model hub.

The notebook begins with installing the transformers package, which provides state-of-the-art machine learning models, primarily focused on Natural Language Processing (NLP). The script uses torch for tensor computations and GPU operations, AutoTokenizer and AutoModelForCausalLM from transformers for tokenization and language modeling, respectively.

## Parameters
- **MAX_TOKENS**: maximum number of tokens;
- **TEMPERATURE**: temperature.

A chat array is initialized to simulate a conversation. The tokenizer formats the chat and encodes it into a tensor. The model then generates a response based on this input, which is decoded and printed as plain text.

Feel free to clone this repository to run the notebook in your own Google Colab environment and modify the code as needed for your own experiments!
