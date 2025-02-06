# 📊 Rule-Based Sentiment Analysis in Python  

## 📝 Overview  
This project implements a simple **rule-based sentiment analysis** algorithm using **Python**. It processes Amazon.com reviews for cell phones and accessories, analyzing sentiments based on predefined rules.  

## 🏆 Features  
- Loads and preprocesses JSON review data  
- Removes punctuation and stop words  
- Performs thematic analysis to identify key phrases  
- Implements a **rule-based sentiment analysis** method  
- Saves the analyzed results to a text file  

## 📂 Project Structure  
📦 Sentiment-Analysis  
┣ 📜 Code.ipynb # Jupyter Notebook with implementation  
┣ 📜 reviews.json # JSON file containing Amazon reviews  
┣ 📜 stopwords.txt # List of stop words for preprocessing  
┣ 📜 results.txt # Final sentiment analysis results  
┣ 📜 README.md # Project documentation  


## 🛠 Implementation Steps  

### 1️⃣ Data Loading & Preprocessing  
- Read and parse the JSON file.  
- Filter the dataset to retain essential columns.  
- Remove punctuation and stop words.  

### 2️⃣ Thematic Analysis  
- Identify frequently used positive and negative words.  
- Use cumulative frequency distribution (CDF) for analysis.  

### 3️⃣ Sentiment Analysis  
- Apply a **rule-based approach** to classify reviews.  
- Assign weights to positive and negative words.  
- Compute cumulative sentiment scores and classify reviews as **positive, negative, or neutral**.  

### 4️⃣ Storage  
- Save the final sentiment-labeled reviews to a text file.  

## 🚀 How to Run the Project  
### Steps to Execute  

1. **Extract the Reviews Zip File:**  
   - Unzip the file and ensure **Cell_Phones_and_Accessories_5** is extracted.  

2. **Organize the Files:**  
   - Place **Cell_Phones_and_Accessories_5** in the same folder as **Code.ipynb**.  
   - Ensure **stopword.txt** is also in the same folder.  

3. **Run the Jupyter Notebook:**  
   - Open **Code.ipynb** in Jupyter Notebook.  
   - Execute all cells to perform sentiment analysis.  

## 📌 Example Output
Review: "This phone is amazing! The battery lasts long."  
Sentiment: Positive  

Review: "Terrible product. Stopped working in a week."  
Sentiment: Negative  
