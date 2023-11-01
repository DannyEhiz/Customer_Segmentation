# **Customer Segmentation**
### Clustering, An Unsupervised Learning
Clustering is a powerful, undirected data mining technique used in business analytics for identifying hidden patterns and structures in a vast volume of data without formulating a specific hypothesis. It has a wide range of applications and can effectively deal with a variety of issues and goals, from the smallest to the most complicated. There are several popular clustering types for each application, but we will place a focus primarily on client clustering for the purpose of this project.<br>
It's a method of organizing individuals based on their behavior, routines, preferences, values, socioeconomic class, location, and demographics, among other factors. With Clustering, organizations optimize the quality of the messages they convey to the general public, such as product promotions with greater purchasing potential or an after-sales service tailored to the customer’s prior purchase. This strengthens consumer relationships, which consequently raises sales. <br>

![image](https://user-images.githubusercontent.com/111154738/189182842-dfb53348-8c1d-4c7d-8e67-4a25cf86a7bd.png) <hr>
**This project was based mainly on segmenting customers into clusters, analysing the cluster** <br>
 <p>  


### Steps I took in carrying out the project <br>
1. Imported Data
2. Cleaning and Data Transformation
3. Dimensionality Reduction with Principal Component Analysis (PCA)
4. KMEANS Clustering and 2D/3D Visualization
5. t-SNE (t Stochastic Distributed Embedding) for Visualization
6. Gaussian Mixture Model and 2D/3D Visualization
7. BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies) and 2D/3D Visualization
8. General Metrics with Silhoutte Score, Davies Bouldin Index, and Calinski Harabasz Score
9. Model Interpretation and Findings
10. General Deductions and Propositions

Visualization of clusters with t-SNE and 3D plot
![image](https://github.com/DannyEhiz/Customer_Segmentation/blob/main/WhatsApp%20Image%202023-11-01%20at%2000.21.14.jpeg?raw=true)<hr>

Visualization of clusters with Gaussian Mixture Model and 3D plot
![image](https://github.com/DannyEhiz/Customer_Segmentation/blob/main/WhatsApp%20Image%202023-11-01%20at%2000.23.32.jpeg?raw=true) <hr>
<br>
Findings are:
<ul>
<li>Cluster Class 0: This is the cluster of customers who earn the highest income at an average of $69200, <br>
have an average of no kid at home, and makes the most purchases at an average of 838 purchases annually.</li>
<li>Cluster Class 1: This is the cluster of customers who earn the lowest income at an average of $30000, <br>
have an average of just one kid at home and makes the least purchases at an average of 42 purchases annually.
</li>
<li>Cluster Class 2: This is cluster of customers who earn high income and makes average of 306 purchases annually, <br>
and have an average of 1 child at home</li>
<li>Cluster Class 3: This is the cluster of customer who earns a low income at an average of $38600 annually, <br>
has an average of two children at home, and also makes an average of 48 purchases annually. </li>
</ul>

NOTICE: Most of the visualization was done using Plotly, an interactive python plotting library. Github doesnt display interactive visuals, and so all visualizations done will not be visible on. However, I made alternative arrangements to get the development file from my LinkedIn page at linkedin.com/in/daniel-ehiz
