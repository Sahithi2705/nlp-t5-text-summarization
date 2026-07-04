# nlp-t5-text-summarization
T5 (Text-to-Text Transfer Transformer) is a Transformer-based language model that converts every NLP task into a text generation problem. It generates concise and meaningful summaries while preserving the key information from the original text.
# NLP Text Summarization using T5

## Overview

T5 (Text-to-Text Transfer Transformer) is a powerful Transformer-based language model developed by Google that treats every Natural Language Processing (NLP) task as a text-to-text problem. Unlike traditional extractive summarization, which selects important sentences from the original text, T5 performs abstractive summarization by generating new sentences that preserve the original meaning while producing concise and fluent summaries.

## Objective

To implement abstractive text summarization using the pre-trained T5 model from Hugging Face Transformers and generate concise summaries from long text documents.

## Tools and Libraries

* Python
* Hugging Face Transformers
* PyTorch
* SentencePiece
* Google Colab

## Dataset

A sample paragraph related to Natural Language Processing is used to demonstrate text summarization. Users can also provide their own paragraphs to generate summaries.

## Implementation Steps

1. Install and import the required libraries.
2. Load the pre-trained T5 model and tokenizer.
3. Provide a text paragraph for summarization.
4. Preprocess the input by adding the **"summarize:"** prefix.
5. Generate the summary using beam search.
6. Decode and display the generated summary.
7. Compare the original text length with the summarized output.
8. Accept user input for custom text summarization.

## Model Information

* **Model:** T5-Small
* **Architecture:** Transformer (Encoder–Decoder)
* **Task:** Abstractive Text Summarization

## Sample Output

### Original Text

```text
Natural Language Processing is a branch of Artificial Intelligence that enables computers to understand, interpret, and generate human language. NLP is widely used in applications such as chatbots, machine translation, sentiment analysis, text summarization, question answering, and speech recognition.
```

### Generated Summary

```text
Natural Language Processing enables computers to understand human language and is widely used in applications such as chatbots, machine translation, and sentiment analysis.
```

### Summary Statistics

```text
Original Words : 42
Summary Words  : 19
```

## Applications

* Document Summarization
* News Article Summarization
* Research Paper Summarization
* Legal Document Analysis
* Medical Report Summarization
* Content Recommendation
* AI Writing Assistants

## Advantages

* Generates fluent and human-like summaries.
* Preserves the meaning of the original text.
* Supports abstractive summarization instead of simply extracting sentences.
* Uses transfer learning with a pre-trained Transformer model.
* Easily adaptable to various text summarization tasks.

## Conclusion

The T5 model was successfully implemented for abstractive text summarization using the Hugging Face Transformers library. The project demonstrated how Transformer-based encoder-decoder architectures generate concise, context-aware summaries while preserving the key information from the original text, making T5 an effective solution for modern NLP summarization tasks.
