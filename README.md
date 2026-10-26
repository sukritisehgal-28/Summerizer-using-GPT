# Abstractive Summarizer

Turns a long passage into a one-sentence summary written in new words, rather than copying sentences out of the text. I built this during my machine learning internship at **DRDO**.

## How it works
- Uses Google's **PEGASUS** model (`google/pegasus-xsum`) through Hugging Face Transformers.
- Tokenizes the input text, generates the summary with the model, and decodes it back to text.
- The notebook runs it on a research-paper abstract about large language models.

## Run it
Open `Summarizer_using_GPT_models.ipynb` in Google Colab. The first cells install `torch`, `transformers` and `sentencepiece`. To summarize your own text, swap it into the `text` cell.

**Stack:** Python · PyTorch · Hugging Face Transformers · SentencePiece

---
More of my work: [sukritisehgal.me](https://sukritisehgal.me)
