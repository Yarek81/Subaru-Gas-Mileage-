# 🚗 Subaru Gas Mileage

## 📊 Project Overview

This project analyzes **gas mileage and fuel spending** data collected from a **Subaru vehicle over one year** to test the manufacturer’s claim of 31 miles per gallon (mpg).
The analysis demonstrates that the vehicle’s actual mpg performance is **higher than the claimed value**, supported by exploratory visualizations.

## 🧠 Motivation

Fuel efficiency claims can significantly influence consumer decisions. By tracking real-world data and visualizing it effectively, this project aims to:

* Verify the accuracy of manufacturer mpg claims
* Explore how fuel spending changes by season and gas station
* Showcase the power of **data visualization** in personal analytics

## 🧰 Tools & Libraries

This project was developed using:

* **Python** - for data analysis
* **Pandas** — for data manipulation
* **NumPy** — for numerical computations
* **SciPy** - for scientific and technical computing
* **Matplotlib / Seaborn / Plotly** — for supporting plots 
* **Jupyter Notebook** — for code execution and presentation

## 📂 Dataset

The dataset was **personally collected** and includes:

| Column Name                    | Description                     |
| ------------------------------ | ------------------------------- |
| `date`                         | Date of fuel purchase           |
| `amount_dollars_per_full_tank` | Total cost per fill-up          |
| `price_per_gallon`             | Gas price per gallon            |
| `gas_station`                  | Name of the gas station         |
| `miles_driven_per_tank`        | Miles driven since last fill-up |
| `season`                       | Indicates warm or cold month    |

## 📈 Visualizations

Visualizations include:

* **Stacked Bar Charts** showing spending by gas station and month
* **Distribution Plots** comparing fuel spending between warm and cold months
* **Interactive Charts** enabling dynamic exploration of gas prices and mileage trends

## ⚙️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/project-subaru-gas-and-mileage-altair-version.git
   cd project-subaru-gas-and-mileage-altair-version
   ```
2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Launch the notebook or view the HTML output:

   ```bash
   jupyter notebook project-subaru-gas-and-mileage-altair-version.ipynb
   ```

   or open the HTML file directly in your browser.

## 🧩 Results

* The analysis **rejected** the manufacturer’s claim of 31 mpg — the real-world data showed **higher mpg**.
* Seasonal variations and gas station differences were also visualized, showing clear trends in spending and efficiency.

## 🏁 Future Improvements

* Integrate regression analysis to model factors affecting mpg.
* Extend data collection across multiple vehicles or driving conditions.
* Build a dashboard using **Streamlit** or **Plotly Dash** for interactive exploration.

## 👤 Author

**Iaroslav (Yarek) Grushetskyi**
Master’s candidate in Data Science, University of Colorado Boulder
Passionate about combining data analytics with real-world decision-making.
