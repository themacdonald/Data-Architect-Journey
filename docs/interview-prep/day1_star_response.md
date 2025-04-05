# ⭐ STAR Interview Response – Day 1

**Prompt:**  
Describe the role of a Data Architect and how it differs from a Data Engineer and Analyst. Include real-world examples.

---

**S (Situation):**  
At [Company X], I worked on a data team with both analysts and engineers, supporting marketing and finance departments with reports and insights.

**T (Task):**  
We often struggled with inconsistent data quality, unclear ownership, and pipelines breaking whenever upstream schemas changed. Leadership asked us to improve trust in our data systems.

**A (Action):**  
While analysts continued building dashboards, and engineers handled pipeline fixes, I proposed a **data architecture approach**:
- Documented a conceptual data model across departments
- Introduced a centralized data lake on AWS S3 with a curated zone
- Implemented dbt to enforce data transformations
- Worked with governance leads to apply access controls

**R (Result):**  
This architectural redesign:
- Reduced pipeline failures by 60%
- Improved cross-departmental data discoverability
- Enabled analysts to build reports faster with higher confidence

---

**Closing Comparison:**  
Unlike Analysts who generate insights, and Engineers who build pipelines, **Data Architects define the structure, flow, quality, and governance of the entire system**, ensuring it scales, adapts, and serves diverse consumers.
