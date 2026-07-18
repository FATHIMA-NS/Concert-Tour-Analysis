# 📊 Concert Tour Revenue Analysis

This is a project where I took a messy list of concert tour data and cleaned it up so I could actually learn something from it.

## 📋 About This Project
I found a "dirty" dataset on Kaggle and wanted to practice my data cleaning skills. My goal was to make the data readable and find out which tours made the most money.

- **Tools used:** Google Sheets
- **Dataset:** [Kaggle Link](https://www.kaggle.com/datasets/amruthayenikonda/dirty-dataset-to-practice-data-cleaning)

## 🛠️ How I Cleaned the Data
The data had a lot of "junk" in it that made it hard to work with. Here is what I did:

1. **Removed Noise:** I used "Find and Replace" to get rid of citation markers (like `[b]` or `[2]`) in the "Peak," "All Time Peak," and "Actual Gross" columns.
2. **Fixed Formatting:** I changed the "Actual Gross" column to a number format so I could calculate totals and averages.
3. **Handled Missing Data:** I noticed empty cells in the "Peak" and "All Time Peak" columns, so I labeled them as "NA" to keep the dataset consistent.
4. **Checked for Mistakes:** I found two tours listed as "Rank 7" and double-checked them to make sure it wasn't a mistake. It turned out to be a tie, not a duplicate!
5. **Sorted the Data:** I sorted the entire dataset by "Actual Gross" from **Z to A (Descending)** so the highest-earning tours appeared at the top.

## 📈 What I Found
After cleaning and sorting the data, I found two clear answers:
- **The Top Tour:** "The Eras Tour" was the clear winner, with a gross of $780,000,000.
- **The Average:** On average, the tours in this list made $287,950,903.25.

## 💡 What I Learned
- I learned that it's important to **investigate** before fixing—like checking the "Rank 7" tie instead of just deleting it.
- I learned how to handle missing values ("NA") so that the data stays organized.
- I got much more comfortable removing specific noise like citation markers to make data usable.
- I realized that "cleaning" is actually 80% of the work in data analysis!
---

*This project is licensed under the MIT License.*
