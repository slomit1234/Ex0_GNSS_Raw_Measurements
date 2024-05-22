# Ex0_GNSS_Raw_Measurements

<img width="224" alt="image" src="https://github.com/slomit1234/Ex0_GNSS_Raw_Measurements/assets/42152443/aec02578-4052-49ab-91b7-14b39c9c5108">

# Summery:
In this project I have built an Python script that processes Raw Measurements GNSS log files to compute the receiver's position and outputs the results in both CSV and KML formats.

# Sources:
https://www.johnsonmitchelld.com/2021/03/14/least-squares-gps.html
https://github.com/johnsonmitchelld/gnss-analysis/tree/main/notebooks

# Environment: 
Anaconda, Jupyter Notebook.

# Requirements:
Jupyter notebook

1. Python Navpy
2. Python Pandas
3. Python Numpy
4. Python unlzw3
5. Python georinex
6. Python simplekml

Note: you can ensure all requirements on Jupyter Notebook terminal using this command:

pip install pandas numpy navp unlzw3 georinex

Example:
 ![image](https://github.com/slomit1234/Ex0_GNSS_Raw_Measurements/assets/42152443/c52f16cb-2e31-466f-81ee-28d5fc71a771)

# GitHub repo:https://github.com/slomit1234/Ex0_GNSS_Raw_Measurements

# AutoRun: 
Extract my GitHub repo to your computer and do a quick test run just to see that everything is working properly.
Make sure:
1.	You have all the packages that mentioned under “requirements”. 
2.	All of the GNSS log data are in the same repository as the script (if you extracted all of the repo properly that this is a no-brainer).
3.	Run the script “FinalScript.ipynb”
4.	It will generate an output file for each log:
Driving (gnss_log_2024_04_13_19_53_33.txt):
 	gnss_log_2024_04_13_19_53_33.kml 
 	gnss_log_2024_04_13_19_53_33.csv
Fixed (gnss_log_2024_04_13_19_51_17.txt):
 	gnss_log_2024_04_13_19_51_17.kml
 	gnss_log_2024_04_13_19_51_17.csv
Walking(gnss_log_2024_04_13_19_52_00.txt):
 	gnss_log_2024_04_13_19_52_00.kml
 	gnss_log_2024_04_13_19_52_00.csv
It should look like this:
![image](https://github.com/slomit1234/Ex0_GNSS_Raw_Measurements/assets/42152443/e99b465e-9020-4faf-9ba5-65fb07d4dd20)
 


