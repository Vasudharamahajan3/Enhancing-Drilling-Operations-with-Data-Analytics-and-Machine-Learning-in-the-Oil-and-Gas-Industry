# Drilling Data Analytics – Internship Projects
This repository showcases the projects I worked on during my internship at **Helmerich & Payne**.  
The focus was on **data-driven drilling optimization**, clustering-based criticality detection, and robust logging utilities.

---

## 📊 Slide Criticality & Setpoint Analytics
**Tools:** Python, Pandas, scikit-learn, Seaborn, Matplotlib, Docker  
**Problem:** Manual detection of drilling slide/rotate intervals and monitoring of setpoints was slow and error-prone.  

**Approach:**  
- Performed **Exploratory Data Analysis (EDA)** on drilling logs from 200+ wells.  
- Applied clustering algorithms (**KMeans, GMM, BIRCH, Spectral**) to identify slide/rotate intervals.  
- Benchmarked clustering with **Silhouette Score** and **Davies–Bouldin Index** → Spectral clustering gave **15% better performance**.  
- Built visualizations (histograms, violin plots) of setpoint distributions (RPM, WOB, flow rate) across multiple operators and basins.  

**Outcome:**  
- Reduced manual review workload by **40%**.  
- Improved anomaly detection accuracy by **25%**.  
- Delivered reusable notebooks and dashboards for ongoing well monitoring.  

---

## ⚙️ Robust Logging System
**Tools:** Python, Docker, REST APIs, Logging Frameworks  
**Problem:** Logging pipelines often failed during container shutdowns or network issues, leading to data loss.  

**Approach:**  
- Developed a **Dockerized logging system** with persistent volumes.  
- Added **signal handling** to ensure logs are retained even when containers stop unexpectedly.  
- Implemented modular APIs for consistent log retrieval and storage.  

**Outcome:**  
- Achieved **100% log retention**, even under container/network failures.  
- Provided a reusable template for fault-tolerant data logging in drilling workflows.  

---

## 📄 Publication
- **Ambisync: An Internet of Things Approach to Room Energy Automation and Optimization**  
  Published in IEEE Conference Proceedings, 2025. [Read here](https://lnkd.in/gGwSM_nZ)  

---

## 📌 How to Run
1. Clone this repo:  
   ```bash
   git clone https://github.com/your-username/drilling-data-analytics.git
   cd drilling-data-analytics
