**Project Title:** Car Dekho: Second Hand Car Selling

**Objective:** To analyze second-hand car sales data and provide insights based on various queries requested by the manager and clients.
The project involves cleaning the data in Excel, importing it into a MySQL database, and performing SQL queries to extract meaningful information.

**Data Overview:**
**Columns:** Name, Year, Selling Price, KM Driven, Seller Type, Transmission, Owner, Mileage, Engine, Max Power, Torque, Seats, Fuel Type.

**Data Preparation:**
1) The data was initially cleaned in Excel to remove inconsistencies, handle missing values, and standardize formats.
2) After cleaning, the data was imported into a MySQL database for further analysis.

**Key Tasks and Queries:**
**1) Car Availability in 2023:**
**. Query:** The manager requested to know how many cars will be available in 2023.
**. SQL Concept Used:** COUNT, WHERE.
**2) Car Availability for 2020, 2021, and 2022:****
**. Query:** The manager asked to find out how many cars were available in 2020, 2021, and 2022.
**. SQL Concept Used:** COUNT, WHERE.
**3) Total Cars by Year:**
**. Query:** The client requested a summary of the total number of cars available each year.
**. SQL Concept Used:** GROUP BY, COUNT, ORDER BY.
**4) Diesel Cars in 2020:**
**. Query:** The client asked for the number of diesel cars available in 2020.
**. SQL Concept Used**: WHERE, AND, COUNT.
**5) Petrol Cars in 2020:**
**. Query:** The client requested the count of petrol cars available in 2020.
**. SQL Concept Used:** WHERE, AND, COUNT.
**6) Fuel Type Cars by Year:**
**. Query:** The manager asked to print the total count of cars by fuel type (Petrol, Diesel, CNG) for all years.
**. SQL Concept Used:** GROUP BY, ORDER BY, COUNT.
**7) Years with More Than 100 Cars:**
**. Query:** The manager wanted to identify which years had more than 100 cars available.
**. SQL Concept Used:** GROUP BY, HAVING, COUNT.
**8) Car Count Between 2015 and 2023:**
**. Query:** The manager requested a complete list of car counts for each year between 2015 and 2023.
**. SQL Concept Used:** WHERE, BETWEEN, GROUP BY, COUNT.
**9) Complete Car Details Between 2015 and 2023:**
**. Query:** The manager needed a detailed list of all cars available between 2015 and 2023.
**. SQL Concept Used:** WHERE, BETWEEN, ORDER BY.

**SQL Concepts Used:**
**COUNT:** To count the number of cars available based on different criteria.
**ORDER BY:** To sort the results by year, count, or other attributes.
**WHERE Clause:** To filter the data based on specific conditions, such as year or fuel type.
**GROUP BY:** To group the data by year or fuel type for aggregate calculations.
**AND:** To apply multiple conditions in queries.
**HAVING:** To filter groups based on aggregate conditions, such as finding years with more than 100 cars.

**Insights:**
**1) Car Availability Trends:** The analysis revealed the number of cars available each year, with specific emphasis on the years 2020, 2021, 2022, and 2023. 
                                This helped in understanding the availability trends over time.
**2) Fuel Type Distribution:** The queries provided insights into the distribution of cars by fuel type, showing that diesel cars were more prevalent in 2020, 
                               but petrol cars also had a significant presence.
**3) Yearly Car Distribution:** By examining the total number of cars available each year, it was found that certain years had more than 100 cars available, 
                                indicating higher second-hand car activity in those years.
**4) Comprehensive Yearly Analysis:** The analysis covered a detailed breakdown of car counts between 2015 and 2023, 
                                      providing a complete overview of second-hand car availability during this period.
**5)Detailed Fuel Type Analysis:** The task to list all fuel types (Petrol, Diesel, CNG) across all years helped in identifying the variations in fuel type preference over time.

**Conclution:** This project provided valuable insights into second-hand car availability and trends over the years. By leveraging SQL queries, the analysis was able to address various business queries, 
                helping managers and clients make informed decisions about the second-hand car market. 

**Tools and Techniques:**  This project was executed using Excel for data cleaning and MySQL for data analysis and querying.
