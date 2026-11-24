# Hi there, I'm Sneha K 👋
### 🚀 Data Engineer & Data Analyst
**Building Scalable Data Pipelines & Actionable Business Analytics**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sneha%20Kumaravel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sneha-kumaravel)
[![GitHub](https://img.shields.io/badge/GitHub-Sneha--9361-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sneha-9361)
[![Email](https://img.shields.io/badge/Email-snehakumaravel6%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:snehakumaravel6@gmail.com)

---

### 👩‍💻 About Me

- 🏢 **8 months of industry experience** at **Teleperformance** (Sep 2025 – May 2026)
- 🔧 Building end-to-end **ETL/ELT data pipelines** using Azure Databricks, Azure Data Factory, PySpark, and Delta Lake
- 🏗️ Designing **Medallion Architecture (Bronze ➔ Silver ➔ Gold)** workflows with Unity Catalog governance and data quality validation
- 📊 Creating interactive **Power BI dashboards** and writing clean SQL & Python for data analysis and problem-solving
- 🎓 **B.E. in Electronics & Communication Engineering** | Sona College of Technology (Anna University) — CGPA: 8.08
- 📍 Tamil Nadu, India

---

### 🛠️ Tech Stack & Tooling

**Cloud, Data Engineering & Storage**  
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Databricks](https://img.shields.io/badge/Azure_Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![ADLS Gen2](https://img.shields.io/badge/ADLS_Gen2-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=flat-square&logo=apachespark&logoColor=white)
![Unity Catalog](https://img.shields.io/badge/Unity_Catalog-FF3621?style=flat-square&logo=databricks&logoColor=white)

**Languages & Databases**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-FF6F00?style=flat-square&logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC292B?style=flat-square&logo=mysql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL_8.0-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Analytics, BI & Version Control**  
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### 🚀 Featured Projects

#### ⚡ End-to-End Databricks Medallion Lakehouse Pipeline
> Batch data pipeline built on Azure Databricks with Unity Catalog, processing ~7,000+ daily customer interaction records.

- **Bronze Layer:** Raw batch ingestion into Unity Catalog with operational audit metadata (`_source_file`, `_ingestion_timestamp`, `call_date`).
- **Silver Layer:** Incremental watermark ingestion, schema validation, quarantine routing for invalid records (`call_id IS NULL`, `call_duration <= 0`), and idempotent Delta `MERGE INTO` deduplication.
- **Storage-Level Integrity:** Enforced native Delta Lake `CHECK` constraints (`valid_call_id` and `positive_duration`) to block non-compliant writes.
- **NLP Enrichment:** Rule-based transcript tokenization and sentiment scoring using native PySpark array functions.
- **Gold Layer:** Business aggregation rollups, daily KPI tracking, topic frequency analysis, and supervisor escalation alerts.
- **Optimization & Automation:** Scheduled `OPTIMIZE` and `Z-ORDER` clustering, `VACUUM` log retention, Databricks Workflows orchestration, and GitHub Actions CI checks.

📁 **Repository:** [databricks-lakehouse-pipeline](https://github.com/Sneha-9361/databricks-lakehouse-pipeline)

---

#### 📊 Customer Support Performance Analysis & Practice Repositories

- **Customer Support Performance Dashboard (Power BI):** Interactive one-page dashboard built with Power Query and DAX across 500 customer support records to analyze SLA metrics, resolution times, and agent performance ([contact-center-sla-analytics](https://github.com/Sneha-9361/contact-center-sla-analytics)).
- **LeetCode Top SQL 50 (MySQL 8.0):** Structured solutions covering joins, window functions, CTEs, subqueries, and aggregations ([leetcode-sql-50](https://github.com/Sneha-9361/leetcode-sql-50)).
- **Python & DSA Practice:** Core Python problem-solving, dictionary frequency patterns, and array algorithms ([python_interview_practice](https://github.com/Sneha-9361/python_interview_practice)).

---

### 📜 Certifications

- 🎓 **Databricks Fundamentals** — Databricks (2026)
- 🤖 **AI Fundamentals** — Google (2026)
- ☁️ **Genesys Cloud Professional Certificate** — Genesys (2025)
- 💡 **SQL Problem Solving** — HackerRank (2024)
- 🐍 **Basics of Python** — Infosys Springboard (2024)
