# Market Segmentation in Insurance

### Objective  :
The goal of this project is to develop a customer segmentation model that can provide tailored recommendations for financial services such as saving plans, loans, and wealth management. By analyzing the behavior of credit card holders, we aim to identify distinct customer groups and understand their unique financial needs.
<img align="center" src="https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png" alt="image">
### Data Description : 
This project uses a dataset containing the usage behavior of approximately 9,000 active credit card holders over the past 6 months. The dataset includes 18 behavioral variables at the customer level, which are used to segment customers into different groups.
### Data :  
Use the below link to download the Data Set:[here](https://github.com/Consti23/MarketSegmentation/blob/main/Clustered_Customer_Data.csv) 
It summarizes various behavioral aspects such as spending patterns, repayment behavior, credit limit utilization, and more.
### Algorithms used :  
In this dataset i've used five clustering algorithm to perform segmentation.These algorithms are given below.
- [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
- [Spectral Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.SpectralClustering.html)
- [DBSCAN Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)
- [GaussianMixture Model based clustering](https://en.wikipedia.org/wiki/Mixture_model)
### Final Model  :
After experimenting with the above clustering algorithms, a final model was selected based on performance metrics and business interpretability. The selected model has been integrated into a Streamlit application, which allows users to input customer details and receive the corresponding cluster assignment. This helps in identifying the most appropriate financial services for each customer group.
### Streamlit Application
The Streamlit application provides a user-friendly interface where users can input customer details and receive the cluster assignment along with recommendations. The app leverages the trained clustering model to predict the customer segment in real-time.
### Getting Started
1. Installation: Clone the repository and install the required dependencies.
git clone <repository-link>
cd customer-segmentation
pip install -r requirements.txt
2. Running the Application: Start the Streamlit app by running the following command:
streamlit run app.py
3. Usage: Once the app is running, enter the customer details in the provided fields and submit to see which cluster the customer belongs to and the corresponding financial recommendations.
### Conclusion
This project provides a robust customer segmentation model that can help financial institutions deliver more personalized services. By understanding the unique characteristics of each customer group, businesses can better meet their customers' needs and improve customer satisfaction.
### License
This project is licensed under the MIT License. See the LICENSE file for details.
### Acknowledgements
We would like to thank the creators of the dataset and the developers of the clustering algorithms used in this project.
