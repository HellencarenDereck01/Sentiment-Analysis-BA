 

---

# **Sentiment Analysis of British Airways Reviews**  

## **Overview**  
This project performs **sentiment analysis** on customer reviews of **British Airways**, leveraging **web scraping techniques** to extract data from **Skytrax**. The goal is to analyze passenger feedback, identify trends in customer satisfaction, and uncover areas for improvement.  

## **Key Features**  
- **Web Scraping**: Extracts real-world customer reviews from **Skytrax**.  
- **Data Cleaning & Preprocessing**: Removes noise, tokenizes text, and prepares data for analysis.  
- **Sentiment Analysis**: Uses **Natural Language Processing (NLP)** to classify reviews as **positive, negative, or neutral**.  
- **Data Visualization**: Generates **charts and word clouds** to present sentiment distribution and key insights.  

---

## **How It Works**  

### **1. Web Scraping**  
- Uses **BeautifulSoup** to extract customer reviews, ratings, and review dates from **Skytrax**.  
- Stores the extracted data in a structured format for further processing.  

### **2. Sentiment Analysis**  
- Preprocesses text by **removing stopwords, tokenizing, and stemming**.  
- Utilizes **NLP techniques** to determine sentiment polarity (positive, negative, or neutral).  
- Computes **sentiment distribution statistics** for insight generation.  

### **3. Data Visualization**  
- Uses **Matplotlib and Seaborn** to create:  
  - Sentiment distribution charts.  
  - Trend analysis graphs over time.  
  - Word clouds highlighting frequently used words in reviews.  

---

## **Installation & Setup**  

### **Prerequisites**  
Ensure the following are installed:  
- **Python (>=3.x)**  
- **Jupyter Notebook**  
- **Required Python libraries**:  
  ```bash
  pip install beautifulsoup4 pandas nltk matplotlib seaborn wordcloud
  ```  



---

## **Repository Structure**  
```
/Sentiment Analysis BA  
│-- BRITISH AIRWAYS 2.ipynb   # Jupyter Notebook with sentiment analysis  
│-- README.md                 # Project documentation  
```  

---


---

## **Acknowledgments**  
- **Skytrax** for providing customer review data.  
- Open-source libraries like **BeautifulSoup, NLTK, and Matplotlib** for data processing and visualization.  

