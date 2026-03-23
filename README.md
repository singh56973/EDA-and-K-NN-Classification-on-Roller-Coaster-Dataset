## 🎢 Roller Coaster — EDA & KNN Classification

### 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** and applies a **K-Nearest Neighbors (KNN)** classification model on a roller coaster dataset (`coaster_db.csv`) containing 1,087 records and 30 features such as speed, height, inversions, type, manufacturer, location, and opening date.

---

### 🔧 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (KNeighborsClassifier)

---

### 📂 Steps Covered

**1. Data Understanding**
- Inspected shape, data types, and summary statistics using `.shape`, `.dtypes`, `.describe()`

**2. Data Preparation**
- Converted date columns to `datetime` format
- Renamed columns for clarity
- Checked for null values and duplicate rows
- Feature engineering (speed in mph, height in ft, clean inversion count)

**3. Exploratory Data Analysis**
- Distribution plots of speed, height, and inversions
- Count plots by coaster type (Wood vs Steel)
- Trend analysis — number of coasters introduced per year
- Correlation heatmap of numerical features
- Pairplots to visualize relationships between key variables

**4. KNN Classification**
- Defined target variable (e.g., coaster type) and selected relevant features
- Split data into training and test sets
- Trained a KNN classifier and evaluated accuracy
- Plotted **Error Rate vs. K Value** (k = 1 to 20) to identify the optimal K

---

### 📈 Key Insights
- Most roller coasters in the dataset were introduced between the 1980s and 2010s
- Steel coasters tend to be faster and taller than wooden ones
- The optimal K value was identified through error rate analysis
