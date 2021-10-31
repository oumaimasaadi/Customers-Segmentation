# Customers-Segmentation

The goal of this project is to understand a store's dataset, do transformations and features engineering, use clustering algorithms (Using IBM SPSS Modeler) then analyze the results.


First of all,I had to understand the dataset's columns so that I can find which important features I can extract from them. 

Dataset Columns




![image](https://user-images.githubusercontent.com/56233947/139600266-4208df67-242b-4bae-a8d1-5bf67bd61699.png)


The next Step was Cleaning the dataset and extract the features that can help us to find differences between the customers.



Dataset after the feature extraction step



![image](https://user-images.githubusercontent.com/56233947/139600446-abd6a74a-7fc0-4580-8123-2cb8db12791b.png)


Nbr_d'achats: How much products the customer bought.


Total_Sales: The sum of money spent by the customer in our store.


Récense: difference between The current date and the date of the customer's last order (This feature helps us to find which customers we lost and which are still buying our products)


Tenure: difference between the dare of the customer's last order and the customer's first order


Diversité_de_produit: Number of distinct product categories that the customer had ordered . 


Nombre_de_visites: Number of customer's orders


Furniture_Sales_sum: The sum of money did the customer spent on The furniture category products


Technology_Sales_Sum: The sum of money did the customer spent on The Technology category products


Office_Supllies_Sales: The sum of money did the customer spent on The Office supplies category products



The third Step was to use K-means Algorithm to find customers groups
To choose the best number of clusters we used The Autocluster that helps us to find the number of clusters that gives the highest silhouette


![image](https://user-images.githubusercontent.com/56233947/139600929-40232e22-68fc-4e6a-bedd-eb162c6f0c5f.png)


The Quality of the algorithm was 40%


![image](https://user-images.githubusercontent.com/56233947/139600961-4371ecb7-0380-46eb-a5c8-776d96c5cf3a.png)



            


