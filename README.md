# Funnel Drop Analysis — E-Commerce Conversion Study

## Project Overview
This project analyzes how users move through an e-commerce sales funnel — from visiting the homepage to completing a purchase. The goal is to identify where users drop off, why conversions decline, and what improvements can increase revenue.

In online shopping, not every visitor becomes a customer. Some users leave after browsing products, while others abandon their cart before checkout. By studying these behavior patterns, this project identifies weak points in the funnel and provides data-driven recommendations to improve conversions and user experience.

---

## Objective
The objective of this project is to understand how users move through the e-commerce funnel and identify stages where users lose interest.

The analysis focuses on:

- Identifying the weakest funnel stage where the most users drop off
- Comparing conversion performance across devices and traffic sources
- Providing practical recommendations to improve conversion rates

The goal is to convert raw behavioral data into clear insights that support product and marketing decisions.

---

## Tools Used
- Python (Pandas, NumPy)
- Data Visualization (Matplotlib, Seaborn)
- Jupyter Notebook
- Funnel Analysis
- Conversion Rate Analysis

---

## Key Funnel Steps

Home Page → Product Page → Cart → Checkout → Order Confirmation

Each step represents progress in the purchase journey. The analysis tracks how many users move to the next stage and where the biggest drop-offs occur.

---

## Main Metrics Used

**To Next Step Conversion %**  
Shows the percentage of users moving from one funnel stage to the next.

**Overall Conversion %**  
Measures the percentage of total visitors who complete a purchase.

**Bounce Rate**  
Percentage of users leaving the website after viewing only one page.

**Average Session Time**  
Measures how long users stay on the website.

**Cart Abandonment Rate**  
Shows how many users add items to the cart but do not complete checkout.

---

## Key Insights

- The largest drop-off occurs between the Product Page and Cart, with nearly 60% of users leaving at this stage.
- Desktop and tablet users convert better than mobile users, suggesting possible mobile UX issues.
- Google and Email traffic sources generate slightly higher conversions.
- Users who complete purchases spend 3.4× more time on the website compared to non-buyers.
- Cart abandonment is evenly distributed across devices and referral sources.

---

## Business Impact

Improving the Product → Cart stage by just 10% could significantly increase conversions and revenue.

Example scenario:

- 100,000 monthly visitors
- 2.5% conversion rate
- Average Order Value = $75

A small improvement could generate approximately $18K–$20K additional monthly revenue.

---

## Real-World Applications

This analysis can help teams with:

- Marketing Optimization
- UX Improvements
- Product Strategy
- Conversion Optimization

---

## Future Improvements

Possible next steps include:

- Adding real revenue and transaction data
- Performing customer segmentation analysis
- Applying predictive models to detect drop-off risk
- Building an interactive dashboard (Power BI or Tableau)

---

## What I Learned

- How to analyze user journeys using funnel analysis
- How to identify conversion bottlenecks
- How to communicate insights in business-friendly language
- How small improvements in conversion rate can create large revenue impact

---

## Project Summary

This project demonstrates how data analysis can identify weak points in an e-commerce conversion funnel. By analyzing user behavior across funnel stages, the study highlights key opportunities to improve user experience, increase conversions, and support data-driven product decisions.

---

## How to Run the Project

```bash
git clone https://github.com/yogeshdhote18/funnel-drop-analysis.git
cd funnel-drop-analysis

pip install pandas numpy matplotlib seaborn jupyter

jupyter notebook "funnel-drop.ipynb"
