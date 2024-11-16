# Tweet classification. 
 
 A dataset of tweets and labels was loaded and preprocessed in order to fine tune a Huggingface model (tiny-BERT). The resulting model was saved to an AWS S3 instance and made available to a Streamlit app which could then be used for classification of new unseen tweets. This method follows that given in the 2025 Deploy ML Model in Production with FastAPI and Docker course by Laxmi Kant.
