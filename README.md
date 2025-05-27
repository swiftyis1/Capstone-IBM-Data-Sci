SpaceX Falcon 9 Landing Prediction

This project was developed as part of the IBM Data Science Professional Certificate Capstone. It focuses on predicting the successful landing of Falcon 9 first-stage boosters using historical SpaceX data. Accurate landing predictions can help SpaceX optimize launch planning and cost efficiency.

Problem Statement

SpaceX's ability to reuse Falcon 9 rocket boosters depends on successful landings. This project aims to build machine learning models that can predict the likelihood of a successful first-stage landing based on launch data, payload mass, orbit type, and other variables.

Project Workflow

This project follows the complete data science lifecycle:

1. **Data Collection**
   - SpaceX API and Wikipedia web scraping using BeautifulSoup.

2. **Data Wrangling**
   - Data cleaning, merging, and transformation.

3. **Exploratory Data Analysis (EDA)**
   - Pattern detection and summary statistics with visualizations.

4. **Geospatial Analysis**
   - Launch site mapping using Folium.

5. **SQL Queries**
   - Using SQLite to extract structured insights.

6. **Machine Learning Modeling**
   - Logistic Regression, Decision Tree, SVM, and Random Forest classifiers.

7. **Interactive Dashboard**
   - Built with Plotly Dash for launch visualization and prediction exploration.

---

Project Structure

Capstone-IBM-Data-Sci/
data/ # Cleaned/processed datasets
jupyter-labs-spacex-data-collection-api.ipynb
jupyter-labs-webscraping.ipynb
labs-jupyter-spacex-data-wrangling.ipynb
edadataviz.ipynb
jupyter-labs-eda-sql.ipynb
lab-jupyter-launch-site-location.ipynb
SpaceX_Machine_Learning_Prediction_Part_5.ipynb
spacex-dash-app.py # Dashboard code
README.md


---

Tools & Technologies Used

- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, Dash, BeautifulSoup, Folium
- **Other Tools:** SQLite, REST APIs, Jupyter Notebooks

---

Machine Learning Models

Models trained and evaluated:

- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest

Dashboard Features

The interactive dashboard allows users to:
- View launch outcomes by site
- Adjust payload mass range
- Explore launch success by orbit and booster version
- View trends with pie charts and scatter plots
- For example the result if you select all sites is included in the repository as success_rate_per_launchsite.
  
To run locally:
```bash
python spacex-dash-app.py

Key Insights
GTO launches have lower success rates than LEO.

Success rates are higher at certain launch sites.

Payload mass influences landing success probability.

Certain booster versions are more reliable than others.

How to Run This Project
Clone the repository:
git clone https://github.com/swiftyis1/Capstone-IBM-Data-Sci.git
cd Capstone-IBM-Data-Sci
Install the required packages:
pip install -r requirements.txt
Launch the dashboard:
python spacex-dash-app.py

Author
David Swift
IBM Data Science Professional Certificate Graduate
GitHub: @swiftyis1
Email: davidswift0920@gmail.com

License
This project is open source and available under the MIT License.

