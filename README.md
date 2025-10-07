# Quynhs Sentiment Dashboard
Amazon Fine Food Reviews Sentiment Dashboard

# 🍽 Amazon Fine Food Reviews Sentiment Dashboard

## Project Overview
This project analyzes **Amazon Fine Food Reviews** to uncover insights about customer sentiment using **text analytics and data visualization** in Power BI.

It focuses on understanding how customers feel about products and which items receive the most positive feedback.

---

## Objectives
- Analyze customer sentiment (Positive / Negative / Neutral)
- Identify top-performing products by sentiment score
- Visualize review trends over time
- Extract and showcase real customer feedback examples
- Present findings in an interactive Power BI dashboard

---

## 🗂 Dataset Information
- **Source:** [Kaggle – Amazon Fine Food Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews)
- **Size:** ~500,000 reviews
- **Key columns used:**
  - `ProductId`
  - `UserId`
  - `Summary`
  - `Text`
  - `Score` (1–5 stars)
  - `Time` (Unix timestamp)
  - `Positive/Negative/Neutral` (derived sentiment labels)

---

## Process Summary
1. **Data Preprocessing (Python)**
   - Clean text (remove stopwords, punctuation)
   - Perform sentiment analysis using `TextBlob` or `VADER`
   - Export cleaned data to CSV for visualization

2. **Visualization (Power BI)**
   - Load dataset and build sentiment visuals:
     - Overall sentiment distribution
     - Trend of sentiment over time
     - Top 10 positive products
     - Word cloud of key terms
     - Sample real reviews

3. **Design**
   - Theme color: soft pastel (pink & yellow)
   - Layout: left for summary KPIs, middle for charts, right for text insights

---

## 📊 Dashboard Highlights
- ** Trend Over Time:** Sentiment score progression yearly  
- ** Top 10 Products:** Ranked by positive sentiment share  
- ** Word Cloud:** Frequent keywords in positive reviews  
- ** Feedback Samples:** Real customer quotes representing sentiment spectrum  
- ** Goal Tracker:** Approaching 80% satisfaction milestone  

---

## Tools Used
| Tool | Purpose |
|------|----------|
| Python | Sentiment analysis, preprocessing |
| Pandas | Data manipulation |
| Power BI | Dashboard visualization |
| TextBlob / VADER | Sentiment scoring |
| Matplotlib | Optional chart testing |

---

## 👩‍💻 Author
**Phạm Diễm Quỳnh**  
📧 *diemquynhnet65@gmail.com*  
💡 *Sentiment Analysis | Power BI | Data Visualization*  
🗓 2025

---

## 📎 Preview
🔗 Power BI Dashboard: *https://app.powerbi.com/links/uaOcFFzAbV?ctid=b1a9fdc0-1d56-4c3d-a481-809fff8a26db&pbi_source=linkShare*
📁 Dữ liệu đã qua xử lý: 
🐍 Source code (Python): *https://colab.research.google.com/drive/1dFzLdC8nZOnyIpNfaNoahgUU9STa9BT0?usp=sharing*

