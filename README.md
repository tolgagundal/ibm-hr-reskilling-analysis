# IBM HR Analytics: Predicting Training ROI & Reskilling Success

## Business Question
Which employees are most likely to benefit from reskilling programs? 
Can we predict who will successfully transition to new roles based on their 
training engagement and performance history?

## Why This Matters
Today, companies invest $5K–$15K per employee in reskilling. Most fail to track 
if training actually predicts career growth. This analysis identifies the 
characteristics of successful reskilling candidates.

## Dataset
[IBM HR Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- 1,470 employees
- 35 features: salary, department, training hours, promotion history, tenure, attrition
- Time period: Cross-sectional snapshot

## SQL Tasks (What I built)
1. Segment employees by training hours + promotion frequency
2. Calculate promotion rate by training investment quartile
3. Identify departments with highest reskilling ROI (training → promotion)

## Python Analysis (What I calculate)
1. Correlation: training hours vs. promotion probability
2. Cohort analysis: employees with 20+ training hours vs. <5 training hours
3. Prediction model: logistic regression to flag high-potential reskilling candidates

## Key Metrics
- Promotion rate by training investment
- Average time-to-promotion after training
- Success rate (stayed + promoted vs. left)

## Dashboard Idea (Tableau)
- Top 10% vs. Bottom 10% comparison: training investment vs. outcomes
- Department reskilling ROI heatmap
- Prediction model confidence scores

## Timeline
- SQL queries: Days 1-2
- Python analysis: Days 3-4
- Visualizations: Day 5
- Write-up & GitHub polish: Day 6
