# ITI_Graduation_Progect_BI_Developer_Track
Implemented a database for e-commerce from scratch,Created data pipelines to load the data
into the data warehouse, extracted useful information by applying different business intelligence solutions, and deployed machine learning models to predict profits.
## project Steps
- Database Design
  - Designed and created an Entity-Relationship (ER) Diagram and mapping to model the database. 
  - Implemented a database using Microsoft SQL Server and added stored procedures, views, functions, and triggers to ensure data consistency and integrity.
- Stored Procedures
  - created 24 stored procedures that allow customers to view and search for products, place orders, and perform other actions. Additionally, business analysts can use     the procedures to view key performance indicators (KPIs) such as sales and profits.
- Data warehouse Design
  - Designed and Implemented a star schema data warehouse in sql server
  - Created data pipelines to load the data into the data warehouse 
- generated an OLAP cube and designed reports
- created interactive dashboards
- Implemented a small desktop application
- deployed a machine learning model on a small website 
## Technical Details
- he database and data warehouse were developed on SQL Server 
- The data pipelines for ETL were implemented using SSIS. 
- the OLAP cube and reports are created using SSAS and SSRS 
- the dashboards of all aspects of the database entities are created using power bi  
    ⭐ Hint you can see the dashboards deployed on Novypro's website from here -> [LINK](https://www.novypro.com/profile_projects/mohamed-rabea-rizq)
- The desktop application uses two libraries: 
  - one to connect to the SQL Server called pyodbc 
  - the other to create the GUI called PyQt5.
  - Through the app, customers can register, log in, place orders, view and search for products, and access their order history.
- implemented machine learning models( LinearRegression - KNeighborsRegressor - SVR - DecisionTreeRegressor - RandomForestRegressor ) using scikit learn
- The Streamlit library was used to deploy the machine learning model.
## Demo
-the ER Diagram and Mapping.
![image](https://user-images.githubusercontent.com/38671671/220419044-e308e896-9e3e-420a-b386-4870e5904df6.png)
![image](https://user-images.githubusercontent.com/38671671/220419145-48c25916-fb40-4813-81a9-7a5c5d2ff818.png)
- implemented the database diagram.
![image](https://user-images.githubusercontent.com/82019926/219908648-b7c18380-afbd-4b06-b57b-316abfc096f9.png)
- Here  SSIS data pipeline that we built, which loads the data into the dimension table in the data warehouse.
![image](https://user-images.githubusercontent.com/38671671/220419635-6b08f1c4-c155-4782-b3d8-a85119e1c2d3.png)
- completed loading all dimensions into the data warehouse, and now the entire structure is in place.
![image](https://user-images.githubusercontent.com/38671671/220420080-2d06e17e-2de0-4dfc-8bad-4e657a846e55.png)
- one of the reports we designed. It shows the sales of each product for every month.
 ![image](https://user-images.githubusercontent.com/82019926/218823344-d4b50612-c8e9-4120-8366-62ff6c55582d.png)
- one of the Power BI dashboards we built, which displays the analysis of orders. 
![image](https://user-images.githubusercontent.com/38671671/220421026-b0d90883-1e20-41f3-a833-6aa87c8ba702.png)
- the final product and it is a website built on the RandomForestRegressor algorithm, it works by outputting the profit for the category after inputting required data. 
![Screenshot_20230205_025628](https://user-images.githubusercontent.com/82019926/218831248-9ce7e6cf-59aa-47bd-bbe9-16b3f5e59308.png)
![image](https://user-images.githubusercontent.com/125575271/220197212-fa5e63e2-e8c5-4add-bdf8-1a318e0cb39d.png)
![image](https://user-images.githubusercontent.com/125575271/220197295-bcd20eeb-1022-4199-a5ac-72fc35790a70.png)
