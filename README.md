# Bank Reviews Sentiment Analysis

Brief run guide.

## Run the analysis

1. **Get the project files** and open the repository root folder. Keep `bank_reviews3.csv` beside `bank_reviews_sentiment.ipynb`; the notebook reads the CSV by that filename.

2. **Set up Python** (Python 3.14 is used with the checked-in `requirements.txt`) and create/activate a virtual environment:

   ```powershell
   py -3.14 -m venv .venv
   .\.venv\Scripts\Activate.ps1
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```

3. **Open the notebook** `bank_reviews_sentiment.ipynb` in VS Code with the Jupyter extension, or launch Jupyter from the repository root:

   ```powershell
   jupyter notebook bank_reviews_sentiment.ipynb
   ```

4. **Select the `.venv` Python kernel** in the notebook. Run all cells from top to bottom using **Run All**. The first run may download NLTK resources and requires internet access.

5. **Review the results** in the notebook output, including sentiment counts, Naive Bayes and Random Forest metrics, comparison charts, and word clouds. The notebook uses CPU; no GPU is required.

## Main files

- `bank_reviews_sentiment.ipynb` — sentiment-analysis workflow and visualizations.
- `bank_reviews3.csv` — input bank-review dataset.
- `requirements.txt` — Python dependencies.
