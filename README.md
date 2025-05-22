<h1>MLB Player Performance Analysis</h1>

<h2>Description</h2>
This project analyzes 2024 MLB player performance by applying clustering and regression techniques to uncover patterns in offensive metrics. The notebook uses KMeans clustering and PCA dimensionality reduction to segment players into performance-based clusters such as Power Sluggers, Contact Hitters, Balanced Contributors, and Low-Production Players. In addition to clustering, linear regression was used to explore relationships between variables like OPS, HR, SLG, and Strikeout Rate. Residual analysis and correlation plots help evaluate the strength of these relationships and provide deeper insights into individual and team performance.

<h2>Languages and Libraries Used</h2>

- <b>Python</b>  
- <b>Pandas</b>  
- <b>NumPy</b>  
- <b>Matplotlib</b>  
- <b>Scikit-learn</b>  

<h2>Environments Used</h2>

- <b>Google Colab</b>  
- <b>Jupyter Notebook</b>  
- <b>Python 3.11+</b>

<h2>Models Implemented</h2>

- <b>KMeans Clustering:</b> Used to segment players into four performance-based groups using features like Home Runs (HR), Batting Average (AVG), On-base Plus Slugging (OPS), and Strikeouts (SO).  
- <b>Principal Component Analysis (PCA):</b> Used to reduce the dimensionality of the data to 2D for effective visualization of cluster separation.  
- <b>Z-Score Normalization:</b> Applied to compare top-performing players within each cluster on a standardized scale.  
- <b>Elbow Method:</b> Applied to determine the optimal number of clusters (k) for KMeans.
- <b>Linear Regression:</b> Used to examine relationships between key offensive metrics and predict On-base Plus Slugging (OPS). Included residual analysis to evaluate model performance.

<h2>Visualizations</h2>

<p align="center">

<b>1. PCA Projection of Players by Cluster</b><br/>
<img src="https://imgur.com/VeBn5uZ.png" width="80%" alt="PCA Clustering"/><br/><br/>

<b>2. Top Player Comparison by Cluster (Z-Score Normalized)</b><br/>
<img src="https://imgur.com/pygdQT9.png" width="70%" alt="Cluster 0"/>
<img src="https://imgur.com/RyujJqc.png" width="70%" alt="Cluster 1"/>
<img src="https://imgur.com/Eoqkgbd.png" width="70%" alt="Cluster 2"/>
<img src="https://imgur.com/E5Hxfnx.png" width="70%" alt="Cluster 3"/>
<br/><br/>

<b>3. OPS vs Strikeout Rate</b><br/>
<img src="https://imgur.com/RhnL4IF.png" width="70%" alt="OPS vs Strikeout Rate"/><br/><br/>

<b>4. Residuals vs Predicted OPS</b><br/>
<img src="https://imgur.com/Dykb2vr.png" width="70%" alt="Residuals vs Predicted OPS"/><br/><br/>

<b>5. Team-Level Analysis: Average OPS by Team</b><br/>
<img src="https://imgur.com/mOScj8J.png" width="80%" alt="Team OPS"/><br/><br/>

<b>6. Scatterplot Matrix of Key Metrics with Regression Lines</b><br/>
<img src="https://imgur.com/oWK99fy.png" width="95%" alt="MLB Metric Correlations"/><br/><br/>

<b>7. Correlation Heatmap of MLB 2024 Batting Stats</b><br/>
<img src="https://imgur.com/uDkeZ5w.png" width="60%" alt="Correlation Heatmap"/>

</p>
