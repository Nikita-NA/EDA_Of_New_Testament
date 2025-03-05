# Exploratory Data Analysis of New Testament Audio & Text

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA) on New Testament audio and text**. It involves web scraping to extract text from an online Bible source, organizing and analyzing corresponding audio files, and preparing the dataset for further speech and text-based AI applications. The goal is to gain insights into the structure of biblical text and its corresponding audio, which can be useful for **text-to-speech (TTS) or speech-to-text (STT) models**.

**Notably, this analysis has been conducted in our own mother tongue, making it a significant contribution to regional language processing and AI advancements.**

## 📂 Dataset Information

- **Text Data**: Scraped from `https://live.bible.is/`, containing 260 chapters of the New Testament.
- **Audio Data**: Pre-downloaded files corresponding to the extracted text.
- **Preprocessing**: Extracted text is stored in `bible_text_all_books.txt`, and audio files are organized into a structured format using Pandas.

## 🛠️ Installation & Setup

To run this project, follow these steps:

1. **Clone the repository**
   ```sh
   git clone https://github.com/Nikita-NA/EDA_Of_New_Testament.git
   cd EDA_Of_New_Testament
   ```
2. **Install dependencies**
   ```sh
   Since all installations are handled within the Colab notebook, no separate requirements.txt file is needed.
   ```
3. **Run the Jupyter Notebook or Google Colab**
   - Open `EDA_New_testament_audio_text.ipynb` in Google Colab or Jupyter Notebook.

## 🔍 Exploratory Data Analysis

### What is EDA?

Exploratory Data Analysis (EDA) is a fundamental step in data science that involves analyzing datasets to summarize their key characteristics. It helps in understanding data patterns, identifying anomalies, and preparing the dataset for further processing or modeling. This project applies EDA techniques to examine the structure, content, and insights from the New Testament text and its corresponding audio recordings.

### What has been done in this project?

The following EDA techniques were applied to the dataset:

#### **Text Analysis**

- **Web Scraping**: Extracted text from the New Testament using web scraping techniques.
- **Data Cleaning & Preprocessing**:
  - Removed unnecessary characters, punctuation, and whitespace.
  - Tokenization and normalization for better analysis.
- **Statistical & Frequency Analysis**:
  - Computed word count per chapter.
  - Analyzed the distribution of words across different books.
  - Identified unique and most frequently occurring words.
- **NLP Techniques**:
  - Generated word clouds for visual representation of word frequency.
  - Applied TF-IDF to understand term importance.
- **Visualization**:
  - Used bar charts, histograms, and word clouds to represent textual trends and distributions.

#### **Audio Analysis**

- **Metadata Extraction**:
  - Processed audio files and extracted key metadata (e.g., duration, frequency information).
  - Mapped each audio file to its corresponding textual content.
- **Duration & Speech Rate Analysis**:
  - Compared the length of audio recordings with the corresponding text length.
  - Examined the speed of spoken verses to detect variations across different books.
- **Potential Future Applications**:
  - Analyzing speech-to-text and text-to-speech alignment.
  - Identifying patterns in spoken language versus written scripture.
  - Investigating phonetic and linguistic variations in spoken Biblical text.

### Importance of This Analysis

- **Textual Insights**: Helps in understanding the structure and word distribution of biblical text.
- **Speech Processing Applications**: Can be leveraged for text-to-speech (TTS) and speech-to-text (STT) model development.
- **Linguistic Research**: Provides a structured dataset for studying phonetics, semantics, and spoken-word patterns.
- **AI & Machine Learning**: Serves as a foundation for training models on religious text processing and speech analysis.

## 📊 Results & Findings

- Successfully extracted and structured the New Testament text and audio files.
- Conducted in-depth text and audio analysis, uncovering frequency distributions and patterns.
- Created visual representations to enhance understanding of textual and audio characteristics.
- **This EDA has been conducted in our own mother tongue, making it a significant effort in regional language NLP and speech processing.**
- Organized dataset for further analysis in speech or text-based AI applications.

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

