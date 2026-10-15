# Hi there, I'm Sneha K 👋
### 🚀 Data Engineer & Data Analyst
**Transforming Raw Data into Scalable, High-Impact Analytical Systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sneha%20Kumaravel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sneha-kumaravel)
[![GitHub](https://img.shields.io/badge/GitHub-Sneha--9361-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sneha-9361)
[![Email](https://img.shields.io/badge/Email-snehakumaravel6%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:snehakumaravel6@gmail.com)

---

### 👩‍💻 About Me

* 🏢 **Data Engineer** at **Teleperformance** (Sep 2025 – Present)
* 🔧 Building scalable, resilient **ETL/ELT data pipelines** using Azure Databricks, PySpark, and Delta Lake
* 🏗️ Implementing **Medallion Architecture (Bronze ➔ Silver ➔ Gold)** on Delta Lake
* 🛡️ Ensuring **99.9% data reliability** with schema contracts, automated quarantine routing, and engine-level constraints
* 🎓 **B.E. in Electronics & Communication** | Sona College of Technology (CGPA: 8.08)
* 📍 Tamil Nadu, India

---

### 🛠️ Tech Stack & Tooling

**Cloud Platforms & Big Data**  
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Databricks](https://img.shields.io/badge/Azure_Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=flat-square&logo=apachespark&logoColor=white)

**Languages & Database Engines**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-FF6F00?style=flat-square&logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Analytics & Visualization**  
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**DevOps, Testing & Orchestration**  
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![PyTest](https://img.shields.io/badge/PyTest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Flake8](https://img.shields.io/badge/Flake8-4682B4?style=flat-square&logo=python&logoColor=white)

---

### 🚀 Featured Engineering Project

#### ⚡ End-to-End Databricks Medallion Lakehouse Pipeline
> Enterprise-grade, production-ready batch data pipeline built on Azure Databricks with Unity Catalog, processing ~7,000+ daily interaction records.

* **Bronze Layer:** Raw batch ingestion into Unity Catalog with operational audit metadata (`_source_file`, `_ingestion_timestamp`, `call_date`).
* **Silver Layer:** Incremental watermark ingestion, schema validation, quarantine routing for corrupt records (`call_id IS NULL`, `call_duration <= 0`), and idempotent Delta `MERGE INTO` deduplication.
* **Storage-Level Integrity:** Enforced native Delta Lake `CHECK` constraints (`valid_call_id` and `positive_duration`) physically preventing non-compliant writes at the storage engine level.
* **NLP Enrichment:** Rule-based transcript tokenization and array sentiment scoring using native PySpark array operations.
* **Gold Layer:** Business aggregation rollups, daily KPI tracking, topic frequency analysis, and high-risk supervisor escalation alerts.
* **DevOps & Maintenance:** Scheduled `OPTIMIZE` and `Z-ORDER` clustering, `VACUUM` log retention, multi-task Databricks Workflows DAG orchestration, and automated CI test runs via GitHub Actions.

📁 **Repository:** [databricks-lakehouse-pipeline](https://github.com/Sneha-9361/databricks-lakehouse-pipeline)

---

### 📜 Professional Certifications

* 🎓 **Databricks Fundamentals** — Databricks (2026)
* 🤖 **AI Fundamentals** — Google (2026)
* 💡 **SQL Problem Solving** — HackerRank (2024)
* 🐍 **Basics of Python** — Infosys Springboard (2024)
* ☁️ **Genesys Cloud Professional Certificate** — Genesys (2025)
