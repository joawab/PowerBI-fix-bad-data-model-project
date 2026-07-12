# 📊 PowerBI Fix Bad Data Model

Fixing a poorly structured Power BI data model: cleaning dimensions, building proper fact tables, connecting relationships, adding a date dimension, measures, and RLS.

**Data source:** [DataWithBaraa Power BI Course Materials](https://academy.datawithbaraa.com/l/digital_download/955781/power-bi-course-materials)

**Inspired by:** [this video](https://www.youtube.com/watch?v=0A2k62YEbfI) - built independently.

---

## 🧱 Project Goal

Original datasource contains 23 unstructured and messy data tables. 

The goal of the project is to create a galaxy schema with correct dimensions and fact tables.

The chosen methodology is to follow medallion architecture.

### Bronze Layer

Staging query with raw data import.

### Silver Layer

Data exploration, validating and cleaning of each table.


### Gold Layer

Building dimension tables and multiple fact tables into a galaxy schema. Creating and validating relationships.

---

## 🎯 Goals

*What "fixed" looks like for this model.

- [x] Standardized naming conventions
- [ ] Clean galaxy schema (facts + dimensions)
- [ ] Correct relationships
- [ ] Date dimension in place
- [ ] Core measures defined
- [ ] Row-level security applied

---

## 🔀 Workflow

Work is tracked via GitHub Issues. Each issue gets its own branch and PR.

**Branch naming:** `type/issue-number-short-name`
Examples: `feature/7-standardize-dimensions`

**Types used:** `feature`, `fix`, `chore`

**Merge strategy:** Squash merge into `main`. PR description includes `Closes #N`.

---

## 📈 Progress

See [Issues](../../issues) for the full task breakdown, from initial exploration through final validation.

| Stage | Status |
|---|---|
| Explore & standardize dimensions | ✅  |
| Build fact tables | 🟡 |
| Date dimension | 🔲 |
| Connect model | 🔲 |
| Measures | 🔲 |
| RLS | 🔲 |
| Validation | 🔲 |

---

## 🛠️ Tools

- Power BI Desktop


---

## 📝 Notes

