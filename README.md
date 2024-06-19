# Anomaly Detection in Telecommunications Networks

This repository contains code to preprocess data, classify anomalies, and visualize the results for detecting anomalies in telecommunications networks. The project aims to improve network reliability and performance by identifying and addressing issues promptly.

## Authors

- **Oussama Guemmar**
- **Hatim Haffou**

Supervised by **Mr. Said Kasli** at **Orange Morocco**.

## Principle

The principle of this work is to detect anomalies and degradations in telecommunication networks using a combination of data preprocessing, statistical analysis, and visualization techniques. The approach involves the following steps:

1. **Data Preprocessing**:
   - **Data Cleaning**: Remove or correct any erroneous, missing, or inconsistent data entries.
   - **Normalization**: Scale the data to ensure that different metrics are on a comparable scale.
   - **Transformation**: Convert the raw data into a suitable format for analysis, such as aggregating data by time intervals or computing rolling averages.

2. **Statistical Analysis**:
   - **Rolling Averages**: Apply rolling averages to smooth the data and identify underlying trends and patterns.
   - **Standard Deviation Calculation**: Compute standard deviations to understand the variability in the data.
   - **Anomaly Detection**: Use statistical techniques such as z-scores, thresholding, and clustering to detect points or periods that deviate significantly from the norm.

3. **Anomaly Classification**:
   - **Categorization**: Classify anomalies based on their characteristics (e.g., sudden increase or decrease in traffic).
   - **Impact Analysis**: Assess the impact of anomalies on network performance and identify potential causes.

4. **Visualization**:
   - **Plotting**: Create visualizations such as line plots, scatter plots, and heatmaps to visualize the data and anomalies.
   - **Interactive Dashboards**: Develop interactive dashboards to explore the data and monitor network performance in real-time.

The ultimate goal is to improve network reliability and performance by promptly identifying and addressing issues.

## Requirements

Install the required packages using the following command:
```bash
pip install -r requirements.txt
```

## Instructions

1. Ensure you have the required dataframes from the specific database with the necessary columns.
2. Run each cell in the Jupyter Notebook ([`ADTS_telecom.ipynb`](ADTS_telecom.ipynb)) sequentially to preprocess data, classify anomalies, and visualize the results.
3. Company-specific data has been hidden for confidentiality.

### Files in this Repository

- [`ADTS_telecom.ipynb`](ADTS_telecom.ipynb): Jupyter Notebook containing the code and explanations.
- [`requirements.txt`](requirements.txt): List of required packages and their versions.

### Example Usage

To run the notebook, open [`ADTS_telecom.ipynb`](ADTS_telecom.ipynb) in Jupyter Notebook or JupyterLab and follow the instructions provided in the notebook cells.
