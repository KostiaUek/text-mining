python -m venv .venv
source .venv/Scripts/activate

pip install -r requirements.txt

python
> import nltk
> nltk.download("stopwords")
> nltk.download("punkt_tab")