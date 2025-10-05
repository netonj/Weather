# Seattle and Vancouver Weather Comparison

> This project compares average rainfall between Seattle, WA and Vancouver, BC to support institutional distinction for NCAA recruiting.

---

## Project Overview

This project cleaned and combined two separate data sets containting average precipitation for Seattle and Vancouver. After joining the two datasets, comparison by data visualization showed that Vancouver sees more average precipitation, but to a rather insignificant amount. 

- **Objective:** The goal of this project is to produce data about Seattle and Vancouver's rainfall to better communicate the differences to NCAA recruits choosing between Seattle and BC institutions.
- **Domain:** Weather
- **Key Techniques:** Statistical comparison and time-series.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** All data were found on the NOAA website: https://www.noaa.gov/
- **Description:** The raw data for Seattle had 10 data columns with 1658 entries of object or float variables. The raw data for Vancouver had 6 data columns with 1824 entries of object or float variables. The clean data set has 4 columns with 3652 entries of dateime, object, and float variables. 
- **License:** NA

---

## Analysis

The Jupyter notebook entitled Weather_Data is the sole notebook used to perform this analysis. Rather simple in form, it can be run in order to reproduce the results.

---

## Results

The study finds that Vancouver sees more average rainfall than Seattle, but to a rather insignificant amount. Annually, rainfall trends in Seattle and Vancouver follow a relatively similar distribution. Vancouver sees higher rainfall than Seattle in each of the 12 months.

---

## Authors

- Jack Neton - [@netonj](https://github.com/netonj)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- NOAA, pandas,numpy, matplotlib, seaborn
- DATA 5100 at Seattle University taught by Brian Fischer.
