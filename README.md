### PART A: DATASET PREPARATION AND TEXT PREPROCESSING

In this part, the IMDb movie review dataset is loaded and explored to understand the sample reviews and their sentiment labels. The number of samples and the distribution of positive and negative reviews are examined. The dataset is divided into training and testing sets. A pretrained BERT tokenizer is loaded to convert text into tokens and numerical IDs. Padding and truncation are applied to maintain a fixed input length. Finally, the tokenized data is converted into the required format and prepared for batch-wise processing.

### PART B: FINE-TUNING BERT FOR TEXT CLASSIFICATION

In this part, a pretrained BERT model is loaded for sentiment classification. The model is configured with two classes: positive and negative. The tokenized training and testing datasets are prepared, and training parameters such as learning rate, batch size, and number of epochs are defined. The BERT model is fine-tuned using the training dataset and evaluated using the testing dataset. Performance is measured using accuracy, precision, recall, and F1-score. New text inputs are given to the model to predict sentiment labels. Finally, the trained model and tokenizer are saved for future use.

### PART C: IMPLEMENTING A SEQUENCE-TO-SEQUENCE APPLICATION USING TRANSFORMERS

In this part, a pretrained sequence-to-sequence Transformer model called T5-small is loaded along with its tokenizer. Sample text inputs are prepared for text generation tasks such as summarization. The input text is preprocessed according to the model requirements. The model generates output text using parameters such as maximum output length and beam search. Different input texts and generation settings are tested to observe changes in the generated results. The input and generated output are displayed and saved for further analysis.

### PART D: MODEL TESTING AND OUTPUT ANALYSIS

In this part, the fine-tuned BERT model is tested using positive and negative movie reviews. The predicted sentiment labels are recorded and analyzed using accuracy, precision, recall, and F1-score. The T5 model is also tested with different input texts and generation settings. The generated outputs are compared based on relevance, readability, and coherence. Possible errors and limitations of both models are identified. Finally, the applications of BERT-based text classification and sequence-to-sequence text generation are compared, and the overall observations are summarized.

# 24ADI006_RAMYAR_24BAD096_EX_09
