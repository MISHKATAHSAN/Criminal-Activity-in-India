# Criminal-Activity-in-India

Criminal Activities in India: Analytics

This project aims to analyze criminal activities in India using various datasets obtained from Kaggle. The analysis includes data cleaning, exploratory data analysis (EDA), visualization, and creating interactive dashboards to uncover insights and trends in criminal activities.

**Datasets**

The project utilizes the following datasets:


1) Crime Against Women

2) Crime Against Children

3)Murders Cases

4) Victims of Murder

5) Kidnapping and Abduction

6) Violent Crimes

7) IPC Crimes in City

8) IPC Crimes in States

9) Total Complaints Received



**Criminal-Activities-in-India/**

**├── data/**


│   ├── crime_against_women.csv  

-> https://drive.google.com/file/d/1ekdyvBIAawFNQZWjbQKyeGSvK30_B4RW/view?usp=drive_link

│   ├── crime against children.csv 

-> https://drive.google.com/file/d/1wt_iKQW8pxatYBtIDJiMuYP7ai1p6p6V/view?usp=drive_link

│   ├── murders_cases.csv  

-> https://drive.google.com/file/d/18hmD3zAc1hH-z-YXLgEtruDsjt_uT8Qk/view?usp=drive_link

│   ├── victims_of_murder.csv  

-> https://drive.google.com/file/d/1OUsqgTZsQDNCJyEoOwq5roDnl2AifXXm/view?usp=drive_link

│   ├── kidnapping_abduction.csv 

-> https://drive.google.com/file/d/1Ez-zsARhhMZG6eOSNxWvomHmRjF1FQJa/view?usp=drive_link

│   ├── violent_crimes.csv 

-> https://drive.google.com/file/d/1JNPwYB0TSXsNZeKkUV8zB3DOmcCeEs_S/view?usp=drive_link

│   ├── ipc_crimes_in_city.csv  

-> https://drive.google.com/file/d/1YTkwikxqAGL58khMAMGDvXQH4-5AsX4j/view?usp=drive_link

│   ├── ipc_crimes_in_states.csv  

-> https://drive.google.com/file/d/1NjgupvDrPnsdpNjAtL1i-pOK8am2hUAH/view?usp=drive_link

│   ├── total_complaints_received.csv 

-> https://drive.google.com/file/d/1uNqjCLu3x1iwzufQuvnYxq84K4L9ULLD/view?usp=drive_link


.

**├── notebooks/**



│   ├── EDA_Crime_Against_Women_&_children.ipynb 

-> https://colab.research.google.com/drive/1YLj1XR5bKgvckCOkNTF3jtqQtTPU4Yww?usp=drive_link



│   ├── EDA_Murders_Cases_&_victims_of_murders.ipynb 

-> https://colab.research.google.com/drive/19lSlZTgcJrRblKoLt79P-vLPpzuf9LbB?usp=drive_link



│   ├── EDA_Violent_Crimes_&_Kidnapping_Abduction.ipynb 

-> https://colab.research.google.com/drive/1trziLLChFX9jEfgFsezpg47Fx5AbSiIo?usp=drive_link



│   ├── EDA_IPC_Crimes_in_City_&_states_&_Total_complaints_received.ipynb  

-> https://colab.research.google.com/drive/1RO0R1LRWirLA-LP56Ggg4hi5aVfrruyd?usp=drive_link





**├── dashboards/**


│   ├── Crime_Against_Women_Dashboard.twb 

-> https://public.tableau.com/app/profile/md.mishkat.ahsan/viz/CriminalActivitiesinIndia_17161056241530/Dashboardwomen 


│   ├── Children_Crimes_Dashboard.twb 

-> https://public.tableau.com/app/profile/md.mishkat.ahsan/viz/CriminalActivitiesinIndia_17161056241530/Dashboardwomen

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


