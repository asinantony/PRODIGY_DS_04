# Twitter Sentiment Analysis using Python

## Project Overview
This project performs sentiment analysis on Twitter data to identify whether tweets are **Positive, Negative, or Neutral**.  
The analysis is performed using **Natural Language Processing (NLP)** techniques with the TextBlob library.

The project also visualizes sentiment trends using **data visualization libraries** such as Matplotlib and Seaborn.

---

## Dataset
The dataset used in this project is **twitter_training.csv** which contains tweets related to different topics.

### Dataset Columns
| Column | Description |
|------|-------------|
| ID | Unique identifier |
| Topic | Topic or category of the tweet |
| Sentiment | Original sentiment label |
| Tweet | Actual tweet text |

Total Records: **74,682 tweets**

---

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- TextBlob
- Jupyter Notebook

---

## Project Workflow

### 1 Data Loading
The dataset is loaded using **Pandas** and basic exploration is performed.

```python
df = pd.read_csv('twitter_training.csv', names=['ID', 'Topic', 'Sentiment', 'Tweet'], header=None)
