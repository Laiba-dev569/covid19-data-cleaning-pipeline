# COVID-19 End-to-End Data Cleaning Pipeline 🦠🧹

An automated data preprocessing and cleaning pipeline built using Python and Pandas to transform unstructured, messy global COVID-19 records into clean, analysis-ready datasets.

## 🚀 Key Project Highlights
* **Data Auditing:** Inspected shapes, data types, and structural null gaps using Pandas profiling tools and Seaborn.
* **Granular Extraction:** Separated localized country records by filtering out macro-regional summary totals (like 'Europe', 'Asia', 'All') and cruise ship entries.
* **Null Imputation Strategy:** Handled missing tracking attributes reliably without biasing numerical means, implementing explicit Pandas nullable integer formatting (`Int64`).
* **Text Normalization:** Standardized mixed-cased typographic naming entries through clean structural strings optimization patterns (`.str.strip()`, `.str.title()`).

## 🛠️ Built With
* **Python 3.x**
* **Pandas:** Advanced indexing (`.loc`/`.iloc`), string methods, and type-casting.
