# Genshin Impact Character Voice Model (ASR)
Model aiming to identify and differentiate Genshin Impact character voices, and be able to predict which Genshin character has the most similar voice to that in an uploaded file.

Key files:
- `playground_model.ipynb`: Model notebook to play around with and upload voice files to match with Genshin characters.
- `preprocessing.ipynb`
- `processing+nn.ipynb`: Feature extraction with Deep Neural Networks with Wav2Vec2
- `processing_lr.ipynb`: Feature extraction with Logistic Regression with Wav2Vec2
- `processing_mfcc.ipynb`: Feature extraction with DNN with MFCC's 
- `processing_custom.ipynb`: Feature extraction with DNN with Pitch and Formants

# Relevant Links
* Link to Dataset: [Hugging Face](https://huggingface.co/datasets/simon3000/genshin-voice)
* Link to Processed Training Data with Wav2Vec2: [X.csv](https://drive.google.com/file/d/1aMqL2mr9FmrDFtpVe6CoIwlpG33ZJ-XN/view?usp=sharing)
* Link to Character Voice Folders: [Characters.zip](https://drive.google.com/file/d/1q3AdK38yMUIf4CRcbGazdCUVDl8n2RNB/view)

If you want to rerun this project, I would highly recommend for you to create a characters folder with all of the voice lines from their respective characters from the preprocessing notebook. I would also recommend to check out the project in the following order: preprocessing --> processing_lr --> processing+nn --> processing_mfcc --> processing_custom --> playground_model. 
