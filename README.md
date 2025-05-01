# Affordability of Living in Florida by County

This interactive map helps users explore the affordability of Florida counties based on household income and cost of living data.

---

## 📌 Project Overview

Choosing a place to live can feel overwhelming. This project simplifies that decision by providing a visual tool that compares household income to the cost of living in each Florida county. Users can quickly see where they can afford to live, based on income and household size.

*You can click the image here to get a 45-second summary on YouTube*

[![Watch the video](https://img.youtube.com/vi/IKXP2eBfmPk/0.jpg)](https://youtu.be/IKXP2eBfmPk)

---

## Installation

To run this project, you will need Python and the following libraries:

- Python
	- pandas
	- geopandas
	- folium
	- numpy
	- openpyxl
- Jupyter Notebook

Place the data folder at the project root. The notebook expects data/florida_counties.geojson and data/fbc_data_2024.xlsx.

---

## 🚀 Or try it in Binder

Likewise, click the badge here to launch an interactive version in your browser:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/markizevbigie/county-livability-project/main?urlpath=%2Fdoc%2Ftree%2Fmap_project.ipynb)

---

## 📁 How to Use

1. Launch the notebook via Binder or clone the repo locally.
2. Open the Jupyter Notebook.
3. Adjust the income and household size inputs to view affordability.
4. View color-coded county maps and output summaries.

---

## 💡 Key Features

- 📊 Visualize affordability across Florida's counties.
- 👨‍👩‍👧 Household-size specific cost of living comparisons.
- 💵 Adjusts for income levels from $0 to $200,000.
- 🧮 Includes affordability ratios and surplus/deficit values.

---

## 📈 Sample Output

![Example Output](images/example_output.JPG)

---

## 🔍 Data Sources

- [United States Census Bureau](https://data.census.gov/all?q=cost%20of%20living%20florida)
- [The Economic Policy Institute’s Family Budget Calculator](https://www.epi.org/resources/budget/budget-map/)

---

## 🧠 What I Learned

- How to clean and merge multiple datasets.
- Building geographic visualizations using GeoPandas.
- Turning abstract questions into data-driven tools.

---

## 🗣️ Future Work

- Expand beyond Florida to other U.S. states.
- Include public transportation and quality-of-life factors.
- Deploy a web version (e.g., Streamlit or Dash).

---

## 👋 About Me

Hi, I’m Mark! I enjoy simplifying complex decisions using data. If you're interested in this work or want to collaborate, feel free to connect.

---

## 📬 Contact

- LinkedIn: www.linkedin.com/in/mark-izevbigie
- Email: markizevbigie@gmail.com
