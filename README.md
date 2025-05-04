# 🚀 SpaceX Launch Success Prediction

## 🧠 IBM Data Science Capstone Project

This project is part of the final capstone for the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science). The goal is to predict whether the first stage of the SpaceX Falcon 9 rocket will successfully land, a key factor in making spaceflight more cost-efficient and sustainable.

---

## 📊 Project Summary

SpaceX is revolutionizing space technology with reusable rockets. This project uses real launch data from SpaceX to analyze patterns and build machine learning models that can predict whether a Falcon 9 first-stage landing will succeed.

---

## 🔍 Problem Statement

Can we predict the success of a SpaceX Falcon 9 first-stage landing based on features such as:

* Launch site
* Payload mass
* Orbit type
* Booster version

A successful prediction model can help SpaceX improve mission planning and reduce costs.

---

## 🔧 Tools & Technologies

* Python
* Jupyter Notebooks
* Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn (SVM, Decision Tree, Logistic Regression, KNN)
* SQL (SQLite with Python)
* Plotly Dash
* Folium
* Web Scraping (BeautifulSoup, Requests)
* SpaceX API

---

## 📁 Project Structure

```
📂 SpaceX-Launch-Success-Prediction/
│
├── 1. data-collection-api.ipynb           # Data extraction from SpaceX API
├── 2. webscraping.ipynb                   # Web scraping Wikipedia for extra launch data
├── 3. Data wrangling_jupyterlite.ipynb    # Merging and cleaning data
├── 4. eda-sql-edx_sqllite.ipynb           # SQL analysis
├── 5. eda data visualisation.ipynb        # EDA using Python plots
├── 6. launch_site_location.ipynb          # Folium map of launch sites
├── 7. spacex_dash_app.py                  # Interactive Plotly Dash dashboard
├── 8. SpaceX_Machine Learning Prediction.ipynb  # ML modeling and evaluation
└── README.md
```

---

## 📈 Results

* **Best Model**: Prediction with \~85% accuracy
* **Key Insights**:

  * Payload mass and launch site significantly impact landing success
  * Certain orbits and booster versions correlate with better outcomes
* **Visualizations**: Included in the notebook and via Plotly Dash spacex_dash_app.py

---

## 📌 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/mgib954/SpaceX-Launch-Success-Prediction.git
   cd SpaceX-Launch-Success-Prediction
   ```

2. Install requirements:

   ```bash
   pip install -r requirements.txt
   ```

3. Run notebooks in order or launch the Dash app:

   ```bash
   python spacex_dash_app.py
   ```

---

## 📍 Key Visualizations

* EDA plots: Payload vs. success, site-based success rates
* Folium map: Global launch site locations with outcomes
* Dashboard: Interactive success filters
* Confusion matrix and accuracy comparisons

---

## ✅ Conclusion

The project shows that it's feasible to predict Falcon 9 landing success with relatively high accuracy using historical data. With more real-time data (like weather), even better models can be built.

---

## 🔗 Resources

* [SpaceX API](https://github.com/r-spacex/SpaceX-API)
* [Wikipedia SpaceX Launch List](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)

---

## 👤 Author

**Mohammad Golam Ishaque**
IBM Data Science Professional Certificate – Capstone Project
GitHub: [mgib954](https://github.com/mgib954)

