# anime-feature-engineering-pandas


# 🎬 Anime Feature Engineering using Pandas

## 📌 Overview
This project focuses on transforming raw and unstructured anime dataset into meaningful numerical features using Python and Pandas.

The dataset contains messy text fields such as:
- "Title" → includes episode count + airing dates
- "Total Time" → embedded within text

---

## ⚙️ Problem Statement
Raw data is not directly usable for analysis or machine learning.

Example:
Fullmetal Alchemist: BrotherhoodTV (64 eps) Apr 2009 - Jul 2010

Goal:
- Extract structured features from unstructured text
- Convert them into numerical values

---

## 🔧 Feature Engineering Tasks

### 1. Episode Extraction
- Extracted episode count from text
- Converted string → integer

### 2. Time Extraction
- Extracted date range (start → end)

### 3. Duration Calculation
- Converted date range into total months

---

## 📊 Key Results

| Insight | Result |
|--------|--------|
| ⭐ Highest Rated Anime | Fullmetal Alchemist: Brotherhood |
| 📺 Most Episodes | Gintama (201 episodes) |
| ⏳ Longest Running | Ginga Eiyuu Densetsu (111 months) |

---

## 🛠️ Tech Stack
- Python
- Pandas
- Datetime
- dateutil

---

