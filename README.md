## 🎥 Project Presentation Video

You can watch the full video presentation of the **Traffic Pattern Analysis using HDBSCAN** project here:

👉 **Video Link:** [Watch Presentation](<https://drive.google.com/file/d/1SH49hr4EICZPKXj52jTo6ExSONlNad3W/view?usp=sharing>)




#       Traffic Pattern Analysis Using HDBSCAN



This project applies unsupervised machine learning to analyze real-time traffic patterns using the HDBSCAN clustering algorithm. The goal is to identify congestion hotspots in Vijayawada based on vehicle density, speed, time, and location.



#### Objectives:

✔ Identify peak traffic timings  

✔ Detect high-density congestion zones  

✔ Compare congestion based on road type \& vehicle types  

✔ Extract insights without labeled data using clustering







#### Dataset:

A synthetic dataset (1200 rows) representing Vijayawada traffic was generated with the following features:



| Feature | Description |

|--------|-------------|

| Latitude, Longitude | Geographical position of vehicle |

| Speed (km/h) | Vehicle speed |

| Hour | Time of day (0–23) |

| Day | Day of week |

| RoadType | Highway / Main Road / Service Road |

| VehicleType | Car / Truck / Bike |

| VehicleCount | Number of vehicles passing |

| CongestionScore | Calculated based on speed, vehicle and road density |



Dataset location: `/dataset/traffic\_vijayawada.csv`







#### Algorithm — HDBSCAN:

HDBSCAN (Hierarchical Density-Based Spatial Clustering of Applications with Noise) is used because:



🔹 Automatically detects number of clusters  

🔹 Handles high-density + low-density areas together  

🔹 Ignores noise / outliers  

🔹 Works perfectly for real-world messy traffic data







#### Implementation:

Notebook location: `/code/Traffic\_Pattern\_Analysis\_HDBSCAN.ipynb`



Steps performed:

1\. Load dataset

2\. Data preprocessing

3\. Apply HDBSCAN clustering

4\. Visualize clusters on scatter plot

5\. Extract insights







#### Output:

Visualization generated at: `/outputs/cluster\_output.png`



Insights file: `/outputs/insights.txt`







#### Key Findings:

✔ High congestion mostly at \*\*8–10 AM\*\* and \*\*5–7 PM\*\*  

✔ \*\*Main \& service roads\*\* show more traffic buildup  

✔ \*\*Truck density strongly correlates with congestion\*\*







#### Future Scope:

🔹 Connect with live traffic APIs  

🔹 Include weather \& festival data  

🔹 Build live monitoring dashboard



#### 

#### Author

Gopichand Alavala — CSE Student






