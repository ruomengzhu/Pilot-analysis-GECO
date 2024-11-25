# Pilot-analysis-GECO

semantic_associations.ipynb: A Jupyter notebook for training a traditional Word2Vec model and analyzing semantic associations.
gpt2_finetuning.ipynb: A Jupyter notebook for fine-tuning a GPT-2 model.

EnglishMaterial.xlsx: An Excel file containing text data used to train the Word2Vec model.


Word2Vec Model Training
- Corpus Preparation: The model was trained on the English text material from the GECO corpus.
- Training: A traditional Word2Vec model was trained using Gensim, capturing semantic relationships between words in the GECO data.
- Semantic Analysis: The model computed word similarities using cosine similarity.

GPT-2 Model Fine-Tuning
- Loading Pre-trained GPT-2: A pre-trained GPT-2 model from the HuggingFace Transformers library was used as the base.
- Fine-Tuning: The GPT-2 model was fine-tuned on the same English text material from the GECO corpus to adapt it to the specific language patterns in the dataset.
