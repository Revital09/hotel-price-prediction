# 🏨 Hotel Price Prediction Project

This project analyzes and compares hotel pricing data from Booking.com and Expedia.  
It includes exploratory data analysis (EDA), data merging, and predictive modeling using machine learning techniques.

---

## 📁 Folder Structure

Data/ 
    ├── BookExp_S4.ipynb # Main notebook for analysis and modeling
    ├── booking_data.csv # Raw data from Booking.com 
    ├── expedia_data.csv # Raw data from Expedia 
    ├── merged_data.csv # Combined dataset used for modeling 
    ├── Booking/ # Folder with Booking.com-specific files 
    └── Expedia/ # Folder with Expedia-specific files


---

## 📊 Techniques Used

- 📦 **Data Preprocessing**  
  Cleaning, merging, and aligning data from multiple sources (Booking & Expedia)

- 📈 **Exploratory Data Analysis**  
  Distributions, comparisons, trends, and visualizations using `matplotlib` and `seaborn`

- 🧠 **Machine Learning Models**  
  - `DecisionTreeRegressor`
  - `MLPRegressor`  
  Trained to predict `price_for_day` using features like:
  - Hotel star rating  
  - Review score  
  - Number of reviews  
  - Distance from center  
  - Proximity to holidays (e.g. July 4th)

---

## 🎯 Project Objectives

- 🔍 Compare hotel price behavior across platforms  
- 📅 Understand influence of dates & holidays on pricing  
- 🤖 Build and evaluate predictive models

---

## 📌 Notes

- All code is written in Python and runs in Jupyter Notebook
- Data files are stored locally inside the `Data/` folder
- The project is exploratory and educational

---

> 👩‍💻 Developed by Revital Yusupov | 2024
