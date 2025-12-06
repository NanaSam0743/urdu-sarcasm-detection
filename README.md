Urdu Sarcasm Detection Project
Quick Results
Baseline Model: 79.51% accuracy

Our Best Model: 82.74% accuracy

Improvement: +3.23% better than baseline

How to Use
1. Install
bash
pip install torch transformers pandas numpy
2. Run the Notebook
Open urdu_sarcasm_detection.ipynb in Google Colab or Jupyter

3. Quick Test
python
from src.models import predict_sarcasm

text = "واہ کیا بات ہے"  # Urdu text
result = predict_sarcasm(text)  # Returns: "Sarcastic" or "Not Sarcastic"
What's Inside
urdu_sarcasm_detection.ipynb - Complete training notebook

data/ - Urdu dataset (19,955 tweets)

src/ - Model code

paper/ - Research paper

What We Did Better
Used XLM-R instead of mBERT

Added character CNN for Urdu script

Used Conformer blocks with Rotary Position Embeddings

Got 82.74% accuracy vs baseline 79.51%

Authors
Saqib Hussain (FAST-NUCES)

Harris Imran (FAST-NUCES)

Dr. Qurat ul Ain (Supervisor)

📜 License
MIT License - Free to use
