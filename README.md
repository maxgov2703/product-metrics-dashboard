# Product Metrics Dashboard

This project demonstrates how product analytics metrics are calculated and visualized using Python.  
The goal is to simulate a typical workflow of a product analyst: collecting user activity data, computing key product metrics, and presenting them in a dashboard-style visualization.

---

## Dataset

A synthetic dataset of user activity was generated to simulate product usage.

The dataset contains the following columns:

- event_date — date of user activity
- user_id — unique user identifier

Each row represents a user event (a visit or interaction with the product).

---

## Product Metrics

The following key product metrics were calculated:

### DAU — Daily Active Users
Number of unique users active on a given day.

### WAU — Weekly Active Users
Number of unique users active within a week.

### MAU — Monthly Active Users
Number of unique users active within a month.

### Stickiness
Measures how frequently users return to the product.

Formula:

DAU / MAU

Higher values indicate stronger user engagement.

### Retention
Shows the percentage of users who return to the product after their first visit.

Retention is calculated based on the number of days since the first user activity.

---

## Visualizations

Several visualizations were created to explore product engagement.

### DAU Trend
Shows daily user activity over time.

### WAU Trend
Displays weekly active users.

### MAU Trend
Displays monthly active users.

### Retention Curve
Illustrates how user retention decreases over time.

### Product Metrics Dashboard
A combined dashboard-style visualization containing the main product metrics.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Insights

- DAU, WAU, and MAU provide different perspectives on product engagement.
- Stickiness (DAU/MAU) indicates how frequently users interact with the product.
- Retention curves help identify user drop-off patterns after the first visit.
- Visual dashboards help product teams quickly monitor key performance metrics.

---

## Purpose of the Project

This project demonstrates core skills required for product analytics:

- working with user activity logs
- calculating product metrics
- building analytical visualizations
- presenting metrics in a dashboard format
