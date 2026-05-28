# A/B Testing Analytics Dashboard & Statistical Engine

An interactive full-stack analytics dashboard for analyzing A/B test experiments using live statistical significance calculations, conversion tracking, and real-time visualization.

---

## Live Demo

### Deployed Application

https://ab-dashboard-coral.vercel.app/

### GitHub Repository

https://github.com/bnyashwanth/ab_dashboard

---

## Dashboard Preview

### Full Dashboard Overview

<p align="center">
  <img src="images/dashboard-overview.png" width="100%" alt="Dashboard Overview"/>
</p>

---

### Conversion Analytics Chart

<p align="center">
  <img src="images/conversion-chart.png" width="100%" alt="Conversion Analytics"/>
</p>

---

### Experiment Results Panel

<p align="center">
  <img src="images/experiment-results.png" width="100%" alt="Experiment Results"/>
</p>

---

### Real-Time Metrics Cards

<p align="center">
  <img src="images/metrics-cards.png" width="100%" alt="Metrics Cards"/>
</p>

---

### Sidebar & Navigation UI

<p align="center">
  <img src="images/sidebar-navigation.png" width="100%" alt="Sidebar Navigation"/>
</p>

---

## Features

* Real-Time Data Ingestion using Pandas
* Live Statistical Significance Calculation
* Dynamic Polling Engine
* Interactive Chart.js Visualizations
* Bootstrap 5 Responsive UI
* Flask REST API Backend
* A/B Experiment Comparison Engine
* Conversion Tracking Dashboard

---

## Technologies Used

### Backend

* Python 3
* Flask
* Pandas
* Statsmodels

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap 5
* Chart.js

---

## Project Structure

```text id="t6g4xo"
ab_dashboard/
│
├── app.py
├── ab_data.csv
├── requirements.txt
├── vercel.json
├── README.md
│
├── images/
│   ├── dashboard-overview.png
│   ├── conversion-chart.png
│   ├── experiment-results.png
│   ├── metrics-cards.png
│   └── sidebar-navigation.png
│
└── templates/
    └── index.html
```

---

## Installation

### Clone Repository

```bash id="mg0vri"
git clone https://github.com/bnyashwanth/ab_dashboard
```

### Move into Project Folder

```bash id="gl7p4q"
cd ab_dashboard
```

### Install Dependencies

```bash id="e3k8lu"
pip install -r requirements.txt
```

### Run Application

```bash id="r5n2yw"
python app.py
```

### Open Browser

```text id="x0v7ns"
http://127.0.0.1:5000/
```

---

## Statistical Analysis

The dashboard uses Z-Test statistical calculations to determine whether Version B significantly outperforms Version A.

### Conversion Formula

```text id="z2d6fb"
Conversion Rate = (Conversions / Visitors) × 100
```

### Statistical Engine

* P-value calculation
* Confidence level analysis
* Live experiment comparison
* Conversion performance tracking

---

## Dataset Insights

| Variant   | Visitors | Conversions | Conversion Rate |
| --------- | -------- | ----------- | --------------- |
| Version A | 147,724  | 17,896      | 12.11%          |
| Version B | 147,766  | 17,684      | 11.97%          |

The statistical confidence level indicates that Version A performs better than Version B based on the analyzed dataset.

---

## Future Improvements

* MongoDB Atlas Integration
* User Authentication
* Experiment History Tracking
* Sample Size Calculator
* Advanced Reporting System
* Exportable Analytics Reports

---

## Author

**B N YASHWANTH**
ID: 1DS24RI010

### GitHub

https://github.com/bnyashwanth

### LinkedIn

https://linkedin.com/in/bnyashwanth
