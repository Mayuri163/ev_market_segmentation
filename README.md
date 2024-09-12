# ev_market_segmentation
### This project analyzes and segments the electric vehicle market based on key performance attributes, charging capabilities, seating capacity, and pricing. Using clustering techniques, the electric vehicles were grouped into distinct categories, providing valuable insights into different market segments.

**Project Overview**
The aim of this project is to categorize electric vehicles into meaningful clusters based on their specifications. The analysis focuses on various features such as:

1. Acceleration (0-100 km/h)
2. Top speed (km/h)
3. Range (km)
4. Efficiency (Wh/km)
5. Fast charging speed (km/h)
6. Seating capacity
7. Price (Euro)
These clusters help in understanding the diverse range of electric vehicles in the market and identifying groups with similar performance characteristics.

**Data**
The dataset contains information on 103 electric vehicles, with the following columns:

1. Brand: Manufacturer of the vehicle
2. Model: Model name
3. AccelSec: Time taken to accelerate from 0-100 km/h
4. TopSpeed_KmH: Maximum speed of the vehicle in kilometers per hour
5. Range_Km: Maximum range of the vehicle in kilometers
6. Efficiency_WhKm: Energy efficiency in watt-hours per kilometer
7. FastCharge_KmH: Speed of fast charging (km/h)
8. RapidCharge: Whether the vehicle supports rapid charging (Yes/No)
9. PowerTrain: Type of powertrain (e.g., AWD, RWD, FWD)
10. PlugType: Type of plug used for charging (e.g., Type 2 CCS)
11. BodyStyle: Vehicle body style (e.g., SUV, Sedan, Hatchback)
12. Segment: Segment type (e.g., B, C, D)
13. Seats: Number of seats in the vehicle
14. PriceEuro: Price of the vehicle in Euros
    
**Methodology**
1. Data Preprocessing
The dataset was preprocessed to extract the relevant numeric features for clustering. The features were standardized using StandardScaler to ensure consistency in scale.

2. Clustering
K-Means clustering was applied to group the vehicles into distinct segments based on their performance attributes and pricing. The Elbow Method was used to determine the optimal number of clusters, resulting in three distinct clusters.

3. Cluster Interpretation
Cluster 0: Vehicles with balanced performance attributes—moderate acceleration, top speed, range, and efficiency, fast charging capabilities, and higher price points.
Cluster 1: Vehicles with lower performance attributes—slower acceleration, lower top speed, shorter range, and lower prices.
Cluster 2: Premium vehicles—fastest acceleration, highest top speed, longest range, fast charging capabilities, and the highest prices.

4. Insights
The clustering results provide valuable insights for various stakeholders in the electric vehicle industry:

Manufacturers can better understand the market segmentation and cater to different consumer needs by offering targeted products.
Consumers can make informed purchasing decisions based on their preferences and budget constraints.
Policymakers can design regulations and incentives to promote electric vehicle adoption across all segments.

**Technologies Used**
Python
Pandas for data manipulation
Scikit-learn for clustering and data preprocessing
Matplotlib for visualization

**Results**
The electric vehicles were successfully segmented into three clusters with distinct performance profiles and pricing:

Cluster 0: Balanced performance and moderate price
Cluster 1: Lower performance, lower price
Cluster 2: High performance, premium price
The segmentation helps identify various market needs, guiding manufacturers in product development and consumers in making informed choices.

**Conclusion**
This project demonstrates how clustering techniques can be effectively applied to segment the electric vehicle market. The analysis provides actionable insights for stakeholders in the EV industry, helping them better understand the market landscape and respond accordingly.
