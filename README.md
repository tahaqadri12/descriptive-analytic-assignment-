### Simplified README – Swiggy Restaurant Analytics Project

### 1\. Project Overview

This project analyzes Swiggy restaurant data from 9 Indian cities. It studies restaurant prices, ratings, popular food types, and delivery times.

It also uses predictive analytics to estimate delivery risks and identify cities with growth opportunities.

### 2\. Objectives

* Find which cities have the most restaurants.

* Compare restaurant prices.

* Analyze customer ratings.

* Identify popular cuisines.

* Compare delivery times across cities.

* Study the relationship between price, rating, and delivery time.

* Predict delivery risks and potential high-rated restaurants.

### 3\. Dataset

* Total restaurants: 8,680

* Cities: 9

* Total fields: 10

* Missing values: None

The dataset includes restaurant name, area, city, price for two people, average rating, total ratings, food type, address, and delivery time.

Cities include Bangalore, Hyderabad, Mumbai, Pune, Kolkata, Delhi, Chennai, Ahmedabad, and Surat.

### 4\. Tools Used

* Python: Main programming language

* Pandas: Data analysis

* Scikit-learn: Predictive models

* Matplotlib: Charts and graphs

* ReportLab: PDF report creation

### 5\. Key Findings

| Analysis              | Result                          |
| --------------------- | ------------------------------- |
| Most restaurants      | Kolkata – 1,346                 |
| Average price for two | ₹348.44                         |
| Average rating        | 3.66/5                          |
| Most popular cuisine  | Chinese                         |
| Average delivery time | 53.97 minutes                   |
| Fastest delivery      | Ahmedabad – 44.71 minutes       |
| Slowest delivery      | Kolkata – 67.81 minutes         |
| Most crowded area     | Rohini, Delhi – 257 restaurants |

### Price Analysis

The average price for two people is ₹348.44. Most restaurants belong to the mid-price category of ₹250–₹499.

Mumbai is the most expensive city, while Surat is the most affordable.

### Rating Analysis

The average restaurant rating is 3.66 out of 5. Chennai has the highest average rating, while Delhi has the lowest.

Some restaurants have the same 2.9 rating and exactly 80 reviews, which may indicate default ratings rather than genuine customer feedback.

### Cuisine Analysis

Chinese is the most commonly listed cuisine, followed by North Indian and Indian food.

### Delivery Analysis

Ahmedabad has the fastest average delivery time, while Kolkata has the slowest.

### Price and Rating Relationship

Higher prices do not necessarily mean better ratings or faster delivery.

### 6\. Business Insights

* Swiggy can add more restaurants in cities such as Surat and Delhi.

* Kolkata needs improvements in delivery services.

* Premium restaurants may need more promotional support.

* Chennai and Bangalore can be studied to improve service quality.

* Restaurant recommendations should consider quality, not just price.

* Unusual rating patterns should be checked.

### 7\. Predictive Analytics

The project uses machine learning to:

* Delivery Prediction: Identify restaurants whose delivery may be slower than their city's average.

* Rating Prediction: Identify restaurants likely to receive ratings of 4.5 or above.

* City Growth: Identify cities with opportunities for expansion.

* Price Analysis: Study how much price affects restaurant ratings.

The models reported 58.4% accuracy for delivery-risk prediction and 71.7% recall for high-rating prediction.

### 8\. Project Folder Structure

```text
Swiggy-Analytics/
│
├── README.md
├── dataset/
│   └── swiggy_restaurant_listings.csv
├── python/
│   ├── analysis.py
│   ├── predictive.py
│   └── make_charts.py
├── report/
│   └── report.pdf
└── charts/
    └── graphs.png
```

### 9\. Data Disclaimer

The dataset represents restaurant listings collected at one point in time. It does not show live Swiggy data or changes over time.

### 10\. Conclusion

This project uses descriptive and predictive analytics to understand restaurant prices, ratings, popular cuisines, and delivery performance. It also helps identify possible improvements in delivery services and opportunities for business growth.

Important: These findings are taken from your uploaded README. The simplified version explains them in easier language but does not independently verify the dataset or model results.
