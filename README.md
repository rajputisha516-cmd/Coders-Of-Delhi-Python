# Coders of Delhi – Social Network Analysis (Python)

This project is a small-scale social network analysis system built using **pure Python** and **JSON data**.  
The goal of this project is to understand, clean, and analyze social data similar to real-world platforms like Facebook or LinkedIn.

Although the dataset is small, the project focuses on **clear logic, problem-solving, and clean data handling**.

---

## 📂 Project Structure

Coders-of-Delhi/
│
├── data1.json
├── data2.json
├── cleaned_data2.json
│
├── stage1.ipynb
├── stage2.ipynb
├── stage3.ipynb
├── stage4.ipynb

---

## 🧩 Tasks Completed

### 🔹 Stage 1: Data Understanding & Reporting
- Explored the JSON data structure
- Analyzed users, friends, and pages
- Created a simple report that can be easily understood by a manager or non-technical stakeholder

---

### 🔹 Stage 2: Data Cleaning & Structuring
- Removed users with missing or empty names
- Removed duplicate users
- Removed duplicate pages
- Cleaned duplicate friend IDs from friend lists
- Generated a cleaned JSON file for further analysis

---

### 🔹 Stage 3: People You May Know
- Implemented a **friend recommendation system**
- Suggested users based on **mutual friends**
- Ranked recommendations using mutual friend count
- Handled edge cases such as missing users

---

### 🔹 Stage 4: Pages You Might Like
- Suggested pages based on:
  - Pages liked by friends
  - Pages liked by friends-of-friends
- Avoided suggesting pages already liked by the user
- Ensured only valid and meaningful recommendations

---

## 🛠️ Technologies Used

- Python
- JSON
- Jupyter Notebook

(No external libraries were used)

---

## 🎯 Key Learnings

- Working with nested JSON data
- Writing clean and reusable Python functions
- Data cleaning and validation
- Implementing recommendation logic
- Thinking from a real-world system design perspective

---

## 🚀 Future Improvements

- Use larger datasets
- Add popularity-based page recommendations
- Convert logic into OOP-based design
- Add unit tests

---

## 👩‍💻 Author

**Isha Rajput**  
Aspiring Data Scientist | Python Developer
