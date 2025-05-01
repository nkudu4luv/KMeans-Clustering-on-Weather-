# K-Means-Python-Application

# K-Means Clustering on Weather Data
This project performs K-Means clustering on NOAA weather data using temperature, wind speed, and precipitation to group similar weather patterns. The output includes a visual representation of the clusters and their centroids.

📌 Features
Data preprocessing and cleaning

Standardization of features

K-Means clustering (3 clusters)

Clustered data export to CSV

Scatter plot with labeled clusters and centroids

🧪 Sample Output

Clusters represent dry, moderate, and wet weather conditions.

🛠️ Requirements
Make sure you have the following installed:


Python 3.x
pandas
matplotlib
scikit-learn
You can install the dependencies with:


pip install -r requirements.txt
📂 File Structure
kotlin
Copy

├── data/
│   └── noaa_weather_data.csv
├── output/
│   └── noaa_weather_clustered.csv
├── cluster_weather.py
├── README.md
├── requirements.txt
└── cluster_plot.png

🚀 How to Run
Place your NOAA CSV file in the data/ folder.

python cluster_weather.py
Check the output/ folder for the results and the plot window for visual output.

📈 Output Description
Clustered CSV File: Contains original weather records with assigned cluster labels.

Plot: A scatter plot of temperature vs. wind speed, colored by cluster and marked with centroids.

💡 Insights
The K-Means clustering reveals natural groupings in weather data that help categorize different weather conditions like:

Cold & calm

Warm & moderate

Variable or stormy

📄 License
This project is for educational and research purposes.
