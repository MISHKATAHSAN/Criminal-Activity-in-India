# Criminal-Activity-in-India

Criminal Activities in India: Analytics

This project aims to analyze criminal activities in India using various datasets obtained from Kaggle. The analysis includes data cleaning, exploratory data analysis (EDA), visualization, and creating interactive dashboards to uncover insights and trends in criminal activities.


**Table of Contents**

Datasets
Project Structure
Installation
Usage
EDA and Insights
Visualizations
Dashboards
Contributing
License
Datasets
The project utilizes the following datasets:

Crime Against Women
Crime Against Children
Murders Cases
Victims of Murder
Kidnapping and Abduction
Violent Crimes
IPC Crimes in City
IPC Crimes in States
Total Complaints Received


Project Structure
kotlin
Copy code

Criminal-Activities-in-India/

**├── data/**


│   ├── crime_against_women.csv

│   ├── children.csv

│   ├── murders_cases.csv

│   ├── victims_of_murder.csv

│   ├── kidnapping_abduction.csv --> https://drive.google.com/file/d/1Ez-zsARhhMZG6eOSNxWvomHmRjF1FQJa/view?usp=drive_link

│   ├── violent_crimes.csv --> https://drive.google.com/file/d/1JNPwYB0TSXsNZeKkUV8zB3DOmcCeEs_S/view?usp=drive_link

│   ├── ipc_crimes_in_city.csv

│   ├── ipc_crimes_in_states.csv

│   ├── total_complaints_received.csv  --> https://drive.google.com/file/d/1uNqjCLu3x1iwzufQuvnYxq84K4L9ULLD/view?usp=drive_link



**├── notebooks/**


│   ├── EDA_Crime_Against_Women.ipynb

│   ├── EDA_Children.ipynb

│   ├── EDA_Murders_Cases.ipynb

│   ├── EDA_Victims_of_Murder.ipynb

│   ├── EDA_Kidnapping_Abduction.ipynb

│   ├── EDA_Violent_Crimes.ipynb

│   ├── EDA_IPC_Crimes_in_City.ipynb

│   ├── EDA_IPC_Crimes_in_States.ipynb

│   ├── EDA_Total_Complaints_Received.ipynb



**├── dashboards/**


│   ├── Crime_Against_Women_Dashboard.twb

│   ├── Children_Crimes_Dashboard.twb

│   ├── Murders_Cases_Dashboard.twb

│   ├── Victims_of_Murder_Dashboard.twb

│   ├── Kidnapping_Abduction_Dashboard.twb

│   ├── Violent_Crimes_Dashboard.twb

│   ├── IPC_Crimes_in_City_Dashboard.twb

│   ├── IPC_Crimes_in_States_Dashboard.twb

│   ├── Total_Complaints_Received_Dashboard.twb


├── README.md

├── requirements.txt

└── presentation/

     ├── Project_Presentation.pptx
     
     └── Project_Report.pdf



Usage
Navigate to the notebooks directory and open google Collab or  the Jupyter notebooks to explore the EDA for each dataset:

sh
Copy code
jupyter notebook notebooks/EDA_Crime_Against_Women.ipynb
The dashboards directory contains Tableau workbooks for interactive visualizations. Open these files using Tableau.


EDA and Insights

Each dataset was analyzed to answer specific questions and derive insights. Some of the key questions include:


How many States and UTs are there in the dataset?

What are the numbers of crimes in 2019, 2020, and 2021?

Which states have the highest and lowest number of crimes?

Are crimes increasing or decreasing over the years?

What is the gender distribution of victims?

Detailed analysis and visualizations for each question are available in the respective Jupyter notebooks.


Visualizations

We used Seaborn and Matplotlib for visualizing trends and distributions. The visualizations help in understanding crime patterns and identifying hotspots.


Dashboards

Interactive dashboards were created using Tableau for each dataset, providing an intuitive way to explore the data. The dashboards include:


Crime trends over the years

Crime distribution by state/region

Gender distribution of victims

Age distribution of victims

Types of crimes

Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


