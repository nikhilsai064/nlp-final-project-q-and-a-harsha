<h2> Multilingual Question Answering </h2>

The goal of this project is to train a model to perform question answering over Languages Hindi and Tamil.
This project was inspired from the Kaggle competition "chaii - Hindi and Tamil Question Answering" by Google Research India,
with the aim of improving the performance of NLU models in low resource Indian languages.

<h4> Model</h4>

For this project, we chose to use the XLM-RoBERTa-large model, which was finetuned on Squad v2. We used the HuggingFace implementation of this model.

<h4> Datasets </h4>

We used two datasets for this project:
- Chaii-1 question answering dataset, which contains Hindi and Tamil Q&A pairs
