# 🌍 Kiva Poverty Mapping Challenge

This project is part of Kaggle's **Data Science for Good** initiative, where the goal is to support **Kiva.org**, a nonprofit microlending platform, by estimating the poverty levels of loan recipients around the world. By combining Kiva’s internal data with external datasets, I aim to uncover regional insights that help guide better lending strategies and deepen Kiva’s social impact.

---

## 📌 Problem Statement

Kiva wants to better understand the **welfare levels of borrowers** in the regions it serves. The objective is to **pair Kiva's loan data with external sources** to estimate poverty at a granular geographic level.

Strong solutions will:
- Map loan and borrower features to regional poverty indicators
- Accurately geocode borrower locations (even when vaguely described)
- Disaggregate poverty data by **gender**, **loan sector**, or **borrowing behavior**
- Provide insights into how Kiva’s lending decisions relate to local economic conditions

---

## 📁 Dataset

Kiva provides a rich dataset covering:
- Loan details (amount, use case, sector, terms)
- Borrower demographics (gender, group size)
- Location info (village, country, etc.)
- Field partner metadata

> ⚠️ **Note**: Due to GitHub’s file size limits, the full dataset is **not included** in this repository.  
> You must download it directly from [Kaggle’s challenge page](https://www.kaggle.com/competitions/data-science-for-good-kiva-crowdfunding).

To download via CLI:
```bash
kaggle competitions download -c data-science-for-good-kiva-crowdfunding
