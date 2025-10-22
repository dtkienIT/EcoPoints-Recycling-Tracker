# 🌱 EcoPoints Recycling Tracker

### A Console-Based Java OOP Project

For this project, I am a developer to help launch a new **EcoPoints Recycling Program**.

Our city wants to motivate households to recycle more by giving them eco points every time they recycle items such as plastic, paper, glass, or metal. These points will later be redeemable for rewards.  

As the first version of this system, my goal is to build a **simple, console-based Java app** that tracks each household's recycling activities and calculates the eco points they earn — helping the community see how much they’ve contributed to a cleaner, greener neighborhood.

---

## 🧩 Project Objectives
- Apply **Object-Oriented Programming (OOP)** concepts such as encapsulation and class design.
- Use **collections (ArrayList, HashMap)** to store and manage data.
- Implement **File I/O** for data persistence.
- Practice **error handling** and input validation.

---

## 🏗️ Project Structure

### Classes
#### `Household`
Represents a household participating in the recycling program.
- `id`: unique ID of the household  
- `name`: household name  
- `address`: address of the household  
- `joinDate`: date the household joined the program  
- `totalPoints`: accumulated eco points  

#### `RecyclingEvent`
Represents a single recycling activity.
- `materialType`: material recycled (plastic, glass, metal, paper)  
- `weightKg`: weight of the material in kilograms  
- `date`: date of recycling  
- `ecoPoints`: points earned for this event  

#### `EcoPointsRecyclingTracker` (Main Class)
Handles user interactions and overall program logic:
- Register new households  
- Log recycling events  
- Display summaries and reports  
- Save and load data from files  

---

## 🗂️ Collections Used
- **HashMap\<Integer, Household\>** — stores all households mapped to their unique ID  
- **ArrayList\<RecyclingEvent\>** — stores all recycling events for each household  

---

## ⚙️ Key Features

### 🏠 Register Households
- Create and register new household profiles with unique IDs.  
- Record the date of joining using the **Java Date & Time API**.  

### 🔄 Log Recycling Events
- Input material type, weight (kg), and date.  
- Automatically calculate eco points (10 points per kg).  
- Update the household’s total points balance.  

### 💾 Store Data
- Save household profiles and recycling logs to files using **Java File I/O**.  
- Data persists even after closing the program.  

### 📊 Display Records
- Show all registered households  
- Display all recycling events for a given household  
- Calculate total recycled weight and total eco points per household  

### 🏆 Generate Reports
- Find the household with the **highest total eco points**  
- Show the **total community recycling weight**  

### ⚠️ Error Handling
- Handle invalid inputs (e.g., negative weights)  
- Manage duplicate household IDs  
- Catch file read/write exceptions  

---


## 🧠 Concepts Applied
- Encapsulation  
- Classes & Objects  
- Java Collections Framework  
- File I/O  
- Exception Handling  
- Date & Time API  

---

## ▶️ How to Run

This project runs in the same way as my previous Java project.  
👉 Please refer to the **“How to Run”** section in my earlier repository for detailed setup and execution steps:  

🔗 [https://github.com/dtkienIT/java-oop-basics](https://github.com/dtkienIT/java-oop-basics.git)

Once you’ve reviewed that, you can run this project’s `EcoPointsRecyclingTracker.java` file in the same manner.

---

## 🧑‍💻 Author
**Kien Do**  
Java Developer — passionate about building sustainable software solutions 🌍

---
