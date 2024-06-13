# Capstone_Guvi
Guvi_Capstone_01_Project
Census Data Analysis Dashboard
This Streamlit web application provides an interactive dashboard for analyzing census data from the year 2011. It connects to a MySQL database and allows users to explore various demographic and socio-economic indicators at the district and state level in India.

Table of Contents
Features
Installation
Usage
Queries Implemented
Technologies Used
Future Enhancements
Contributing
License
Features
Dynamic Query Selection: Users can select from a dropdown menu to view different demographic statistics such as total population, literacy rates, household characteristics, and more.

Data Visualization: Results from SQL queries are displayed using Pandas DataFrames, providing clear insights into the census data.

Error Handling: Includes robust error handling for database connectivity and query execution failures, ensuring smooth user experience.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/SivaAdigiri/Capstone_Guvi.git
cd census-data-analysis
Install dependencies:

Ensure you have Python 3.7+ installed. Install required packages using pip:

bash
Copy code
pip install -r requirements.txt
Database Setup:

Create a MySQL database named Census_DB.
Update the get_db_connection() function in app.py with your MySQL username, password, host, and port.
Run the application:

bash
Copy code
streamlit run app.py
Open the provided local host URL in your web browser to access the dashboard.

Usage
Upon running the Streamlit application, the dashboard will appear.
Select a category from the dropdown menu to view corresponding census data.
The application will execute SQL queries in real-time and display the results in tabular format.
Queries Implemented
The following SQL queries are implemented in the application to fetch census data:

Total Population by District
Literate Males and Females by District
Percentage of Workers by District
Households with LPG or PNG as Cooking Fuel by District
Religious Composition by District
Households with Internet Access by District
Educational Attainment Distribution by District
Households with Access to Various Modes of Transportation by District
Condition of Occupied Census Houses by District
Household Size Distribution by District
Total Number of Households in Each State
Households with Latrine Facility within the Premises by State
Average Household Size by State
Owned vs. Rented Households by State
Distribution of Different Types of Latrine Facilities in Each State
Drinking Water Source Near the Premises Facility in Each State
Average Household Income Distribution in Each State Based on the Power Parity Categories
Percentage of Married Couples with Different Household Sizes in Each State
Households Below the Poverty Line in Each State Based on the Power Parity Categories
Overall Literacy Rate (Percentage of Literate Population) in Each State


Technologies Used
Streamlit: Frontend UI framework for building interactive web applications in Python.
Pandas: Data manipulation and analysis library.
SQLAlchemy: SQL toolkit and Object-Relational Mapping (ORM) for Python.
MySQL: Relational database management system used to store census data.
Future Enhancements
Include more advanced data visualizations such as charts and graphs.
Implement user authentication and access control for different datasets.
Expand database support to include other SQL databases like PostgreSQL or SQLite.
Contributing
Contributions are welcome! Fork the repository and submit a pull request for any proposed enhancements.
