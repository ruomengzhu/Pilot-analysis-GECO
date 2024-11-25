# Pilot-analysis-GECO-ENG

Pilot analysis_GECO_Eng (W2V-semantics).ipynb: A Jupyter notebook for training a traditional Word2Vec model and analyzing semantic associations.

Pilot analysis_GECO_Eng (GPT2).ipynb: A Jupyter notebook for fine-tuning a GPT-2 model.

EnglishMaterial.xlsx: An Excel file containing text data used to train the Word2Vec model and to fine-tune the gpt2 model.


Word2Vec Model Training
- Corpus Preparation: The model was trained on the English text material from the GECO corpus (English).
- Training: A traditional Word2Vec model was trained using Gensim, capturing semantic relationships between words in the GECO data.
- Semantic Analysis: The model computed word similarities using cosine similarity and can generate outcome file containing all the semantic similarity scores for word pairs derived from the Word2Vec model.

GPT-2 Model Fine-Tuning
- Loading Pre-trained GPT-2: A pre-trained GPT-2 model (pre-trained distilgpt2 model) from the HuggingFace Transformers library was used as the base.
- Fine-Tuning: The GPT-2 model was fine-tuned on the same English text material from the GECO corpus to adapt it to the specific language patterns in the dataset.
