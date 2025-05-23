# 📊 Incident Pattern Analyzer – Industrial Safety Risk Insights

**Author**: Billy Pierre  
**Tools**: Python, Pandas, Matplotlib, Seaborn, Scikit-learn, WordCloud  
**Platform**: Google Colab

---

## 📌 Objective

Analyze over 400 industrial accident records to identify patterns in severity, risk types, sectors, and timing — and build a predictive model for high-severity incidents.

---

## 🗃️ Dataset

- **Source**: [Kaggle – IHMStefanini Industrial Safety Dataset](https://www.kaggle.com/datasets/ihmstefanini/industrial-safety-and-health-analytics-database)
- **Records**: 400+
- **Fields**: Date, Sector, Gender, Role, Severity, Critical Risk, Description

---

## 🔍 Key Findings

- Most accidents were low severity (Level I), but many had high potential (Levels IV–VI)
- Pressed, Manual Tools, and Chemical Substances were top risks
- Mining and Metals were the most incident-prone sectors
- Peak accidents occurred in early months (Feb–June)
- Third-party and male workers had higher incident rates

---

## 🔮 Predictive Modeling

A Random Forest classifier predicted high-potential severity incidents using:
- Accident Level
- Industry Sector
- Gender

Model outputs include a confusion matrix and feature importance chart.

---

## 📄 Report

- 📥 [Download Full Report (.docx)](Incident_Pattern_Analysis_Report_Final.docx)
- 📥 [requirements.txt](requirements.txt)

---

## 🖼️ Visual Highlights

This project includes the following key visuals:
- Top Critical Risks (with/without Other/Unknown)
- Heatmap: Severity by Industry
- Monthly Trends Line Chart
- Word Cloud of Incident Descriptions
- Confusion Matrix & Feature Importance Chart

---

## 🔧 Installation

```bash
pip install -r requirements.txt
```

---

## 📝 Future Improvements

- Expand text mining on incident descriptions
- Deploy as real-time safety dashboard
- Use model insights to build alert systems

---

## 📬 Contact

For feedback or collaboration, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/pierrebilly).
