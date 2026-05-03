# 🎬 Movie Recommendation and Review System (C + GTK)

## 📌 Overview
This project is a **Movie Recommendation and Review System** built using the **C programming language** with a **GTK-based graphical user interface (GUI)**.

It allows users to:
- Filter and search movies based on preferences  
- View recommended movies  
- Submit reviews  
- View reviews for specific movies  

The system reads movie data from a CSV file and dynamically updates results based on user input.

---

## 🚀 Features

### 🔍 Movie Recommendation
- Filter movies based on:
  - Genre  
  - Language  
  - Decade  
  - Minimum rating  
- Displays matching movies in the format:

```
Movie Name (Year) [Rating]
```

- If no matches are found:
  - Shows **Top 5 highest-rated movies**

---

### 📝 Review System
- Users can submit reviews in the format:

```
Movie Name, Review
```

- Reviews are stored in a file (`Reviews.csv`)
- Displays confirmation:
  - "Review submitted successfully"
  - "Please enter the review in the given format."

---

### 📖 Review Display
- Enter a movie name to view all its reviews  
- If no reviews exist:

```
(No reviews found)
```

---
