# PhonePe-Transaction-Insights

PHONEPE PULSE DATA VISUALIZATION AND EXPLORATION
Introduction
PhonePe is an Indian digital payments and financial services company headquartered in Bengaluru, Karnataka, India. It was founded in December 2015, by Sameer Nigam, Rahul Chari and Burzin Engineer. The PhonePe app, based on the Unified Payments Interface, went live in August 2016. 
Developed a Streamlit application for analyzing transactions and user data from the Pulse dataset cloned from the PhonePe Pulse GitHub repository. Explored data insights on states, years, quarters, districts, transaction types, and user brands. Visualized trends and patterns using plots and charts to optimize decision-making in the Fintech industry.

About PhonePe-Pulse Data:
This data has been structured to provide details of following three sections with data cuts on Transactions, Users and Insurance of PhonePe Pulse - Explore tab.
1.	Aggregated - Aggregated values of various payment categories as shown under Categories section
2.	Map - Total values at the State and District levels.
3.	Top - Totals of top States / Districts /Pin Codes

Approach:
1. Data extraction:
•	Clone the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a suitable format such as CSV or JSON.
2. Data transformation:
•	Use a scripting language such as Python, along with libraries such as Pandas, to manipulate and pre-process the data.
•	This may include cleaning the data, handling missing values, and transforming the data into a format suitable for analysis and visualization.
3. Database insertion:
•	Use the "mysql-connector-python" library in Python to connect to a MySQL database and insert the transformed data using SQL commands.
4. Dashboard creation:
•	Use the Streamlit and Plotly libraries in Python to create an interactive and visually appealing dashboard.
•	Plotly's built-in geo map functions can be used to display the data on a map and Streamlit can be used to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.
5. Data retrieval:
•	Use the "mysql-connector-python" library to connect to the MySQL database and fetch the data into a Pandas dataframe.
•	Use the data in the dataframe to update the dashboard dynamically.
6. Data Visulation:
•	Connect mysql-connector with powerbi for Visulaization using POWERBI Dashboard.

Technologies:
•	Github Cloning
•	Python
•	Pandas
•	MySQL
•	mysql-connector-python
•	Streamlit
•	Plotly
•	Powerbi
