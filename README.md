# Fine-Tuning-Language-Models
Fine-Tuning Language Models for Enhanced E-Commerce Product Summarization

**Overview**

This project involves the development, fine-tuning, and evaluation of three prominent models—BART, T5, and Llama—specifically designed for generating text summaries. The primary objective is to thoroughly compare these models by assessing their capabilities and performance metrics in the context of summarizing Amazon product reviews.

**Objective**

The main goal of this study is to compare the BART, T5, and Llama models to determine which one is most effective at summarizing long Amazon product reviews into concise summaries. This helps in identifying the model that produces the clearest and most useful summaries without losing critical information.

**Dataset**

The dataset used in this project was sourced from Kaggle, containing ratings and reviews of over 1,000 Amazon products. It provides a rich source of textual data for summarization tasks.
* Source: [Amazon Sales Dataset](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)

**Models**
* BART: Known for its proficiency in generating coherent summaries and maintaining grammatical structure.
* T5: Notable for its balance between conciseness and informativeness, producing clear and relevant summaries.
* Llama: While competent, it lags slightly in coherence and detail retention, particularly because it wasn't fine-tuned for this task.

**Methodology**

The methodology involves using the Hugging Face Transformers library for model implementation and fine-tuning. Each model was fine-tuned on the same dataset to ensure a fair comparison. The models were evaluated using ROUGE scores and histograms of text lengths before and after summarization.

**Installation**

To use this project, clone the repository and install the necessary dependencies.

**Usage**

This project can be replicated by running the given code. Keep in mind you need to generate your own Hugging Face Access Tokens and add them in the provided space.

To replicate our models, you can directly access the fine-tuned models from Hugging Face:
* [T5Model_for_Ecommerce](https://huggingface.co/Rajpatel013/BARTModel_for_Ecommerce)
* [BARTModel_for_Ecommerce](https://huggingface.co/Rajpatel013/T5Model_for_Ecommerce)
