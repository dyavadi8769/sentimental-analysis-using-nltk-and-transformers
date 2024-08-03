# sentimental-analysis-using-nltk-and-transformers

You can download the data from here: https://drive.google.com/drive/folders/1sTCtiBLOdRqT5VPCrakVgFBtpJgcodFi?usp=sharing


## Steps Involved in the Sentiment Analysis Project

1. **Importing Libraries:** Imported necessary libraries like pandas, numpy, matplotlib.pyplot, seaborn, and nltk.
2. **Loading Data:** Loaded the dataset using pandas and displayed the first few rows, filtering to 500 rows.
3. **Exploratory Data Analysis (EDA):** Plotted the distribution of review scores using a bar chart and displayed an example text.
4. **Text Tokenization:** Tokenized the example text into sentences and words using NLTK.
5. **Part-of-Speech Tagging and Named Entity Recognition:** Tagged parts of speech and performed named entity recognition on the tokenized words.
6. **Downloading NLTK Resources:** Downloaded NLTK resources like 'averaged_perceptron_tagger', 'maxent_ne_chunker', 'words', and 'vader_lexicon'.
7. **Sentiment Analysis with VADER:** Used SentimentIntensityAnalyzer from NLTK to analyze example texts and the entire dataset, storing results in a dictionary and DataFrame.
8. **Visualization of Sentiment Scores:** Visualized sentiment scores (compound, positive, neutral, negative) against review scores using bar charts.
9. **Using Hugging Face Transformers for Sentiment Analysis:** Loaded the roberta-base model from transformers and calculated sentiment scores, storing results in a dictionary and DataFrame.
10. **Comparison of VADER and RoBERTa:** Compared VADER and RoBERTa sentiment scores using pair plots and queried the dataset for specific sentiment examples.
11. **Using Hugging Face Pipeline for Sentiment Analysis:** Used the Hugging Face sentiment analysis pipeline for quick sentiment analysis on sample texts.


## Commands to Setup Project on Local Machine

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dyavadi8769/sentimental-analysis-using-nltk-and-transformers.git
   cd sentimental-analysis-using-nltk-and-transformers

2.  **Create a virtual environment and activate it:**
    ```bash
    conda create -p env python==3.11.7 -y
    conda activate env/ 

3.  **Install the Required Dependecies:**
    ```bash
    pip install -r requirements.txt



yes!! Now you can start predicting 🙂

# Author:

```bash
Author: Sai Kiran Reddy Dyavadi
Role  : Data Scientist
Email : dyavadi324@gmail.com
```


