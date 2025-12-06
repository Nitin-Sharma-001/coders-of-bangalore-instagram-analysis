# Coders of Bangalore – Instagram Data Analysis

This project is a fun and practical data analysis challenge inspired by a fictional scenario where Sam Altman gives you 24 hours to analyze raw Instagram data of Bangalore-based coders and creators.
The dataset was messy, unstructured text collected manually — and the goal was to clean it, parse it, structure it, and answer a set of analytical questions.

---

### 🚀 Project Objectives

* Parse raw Instagram profile text and answer:

1. Who has the maximum posts?

2. Who has the maximum followers?

3. Who follows the most people?

4. How many unique categories (types of pages) are present?

---

### 🧹 Data Cleaning & Parsing

* The raw file contained:

- Mixed text

- Posts, followers, and following with “K” and “M” formats

- Bios

- Category labels

- Missing fields for some users

* Using Python, each profile chunk was:

- Split

- Cleaned

- Converted into integers/floats

- Normalized (“K” → ×1,000 and “M” → ×1,000,000)

- Structured into a dictionary

- Stored into a final JSON file

---

### Example Output:

<img width="1391" height="201" alt="image" src="https://github.com/user-attachments/assets/778dd09d-1332-4887-9dec-46845452814b" />


---

### 🛠 Technologies Used

* Python

* Jupyter Notebook

* String processing & parsing

* JSON handling

* Set operations

* File I/O

---

### 🎉 Conclusion

* This project demonstrates end-to-end data handling:

- Raw data → Clean data → Insights

- Real-world parsing challenges

- Analytical reasoning
