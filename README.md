# Automated-Disease-Entity-Recognition-System-Using-BERT

Developed an automated Named Entity Recognition (NER) system using BERT (Bidirectional Encoder Representations from Transformers) to identify and extract disease names from medical research articles, significantly reducing manual effort in the publication process.
• Preprocessed and labeled biomedical text data from the NCBI Disease Corpus, implementing a custom token-level labeling strategy to handle multiple diseases per article without a fixed disease list, effectively managing complex biomedical terminology.
• Fine-tuned the BERT model by adding a custom dense layer with softmax activation for token classification, achieving over 99% accuracy on the validation set, demonstrating the model's effectiveness in accurately identifying disease entities in unstructured text.
