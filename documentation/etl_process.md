# ETL Process

Power Query was used as the ETL layer for data preparation.

---

# Data Cleaning

The following actions were performed:

- removal of duplicated fields
- validation of null values
- correction of data types
- standardization of column names

---

# KPI Governance

Precalculated metrics such as:

- CTR
- CPC
- CPA
- ROAS

were removed to avoid inconsistencies and recalculated using DAX measures.

---

# Standardization

Column names were standardized from English to Spanish to improve usability and business readability.

Examples:

- impressions → Impresiones
- clicks → Clics
- conversions → Conversiones
- spend → Inversion
- revenue → Ingresos

---

# Data Modeling Preparation

The ETL process also prepared the dataset for Star Schema implementation.
