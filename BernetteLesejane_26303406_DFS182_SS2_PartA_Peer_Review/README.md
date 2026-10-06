# Bank Reviews Sentiment Analysis - Peer Review Package

## Included files
- `bank_reviews_sentiment.ipynb` - analysis notebook (preprocessing, TF-IDF, Naive Bayes and Random Forest models, evaluation and visualizations).
- `bank_reviews3.csv` - dataset used by the notebook.
- `requirements.txt` - Python packages needed to run the analysis.
- `Peer_Reviewer_Guide.docx` - step-by-step setup and review instructions.

## Quick start (Windows)
1. Extract the ZIP and open PowerShell in the extracted folder.
2. Create a virtual environment: `py -m venv .venv`
3. Activate it: `.\.venv\Scripts\Activate.ps1`
4. Install dependencies: `python -m pip install -r requirements.txt`
5. Open the notebook in VS Code, select the `.venv` kernel, and run all cells. Or use `python -m jupyter notebook bank_reviews_sentiment.ipynb`.
6. Internet access is needed on the first run so NLTK can download stopwords and WordNet.

Keep the CSV beside the notebook. No GPU is needed.
