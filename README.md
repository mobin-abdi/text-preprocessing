# **Text Preprocessing Pipeline for Children's Books Descriptions**

This repository contains a simple Python script demonstrating essential text preprocessing steps using the Pandas library. It's a personal learning project aimed at understanding and applying fundamental Natural Language Processing (NLP) data cleaning techniques.

## 📚 Project Goal

The primary goal of this project is to take raw book descriptions and clean them for further analysis or model training. This involves:
- Standardizing text to lowercase.
- Removing non-standard characters and excess whitespace.
- Removing punctuation.

## 📈 Data Source

The script utilizes a small dataset of children's book descriptions from the file `Course Materials/Data/childrens_books.csv`. This dataset is used for demonstration purposes.

## 🛠️ Technologies Used

- **Python:** The programming language.
- **Pandas:** For data manipulation and analysis.

## 🚀 Getting Started

### Installation

1.  Clone the repository:
```bash
git clone https://github.com/mobin-abdi/text-preprocessing.git
cd text-preprocissing
```

2. Ensure you have Python and Pandas installed. If not, you can install Pandas using pip:
```bash
pip install pandas
```
or:
```bash
pip install -r requirements.txt
```

## Running the Script
1. Make sure the childrens_books.csv file is located at Course Materials/Data/childrens_books.csv relative to the script.
2. run jupyter-notebook in terminal

## ✨ Demonstration
1. Load Data: Reads the CSV file into a Pandas DataFrame.
2. Lowercase Conversion: Converts all text in the ‘Description’ column to lowercase.
3. Whitespace Normalization: Replaces non-breaking spaces (\xa0) with regular spaces.
4. Punctuation Removal: Removes all characters that are not alphanumeric or whitespace.

## 💡 Learning Journey
**This project is part of my ongoing learning in NLP. While the preprocessing steps here are fundamental, they are crucial for building robust NLP pipelines. Future steps might involve:**
- More advanced text cleaning (e.g., handling emojis, URLs).
- Stop word removal.
- Stemming or Lemmatization.
- Tokenization.

*This script serves as a basic building block, and I’m excited to expand upon these techniques!*
