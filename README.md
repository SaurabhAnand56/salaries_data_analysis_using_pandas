 ![pandas for data analysis](pandas1.png)
                                            <br>**Fig. 1** 

   Welcome to my Repo. In this repo, I have analyzed [Salary Dataset](Salaries.csv) using Pandas Library with lesser code in Jupyter Notebook so that you can observe the function of every methods in pandas from the basic level.<br>
   <br>
   <br>First of all let's understand "what is data analysis and why should we use pandas for analysis ?".
   
### What is data analysis?
   Suppose you are working in a company which daily generates a lot of data of customers and you are assigned a task to extract some useful information from it with a certain deadline. What will you do if you have very limited time you can not extract information just by looking into the dataset because the size of the data is huge. So you asked for help from your colleague he said just read about pandas for data analysis. You studied pandas and you found that pandas makes your life easier than just looking at dataset and finding useful informations.
### What does pandas actually do?
   This official documentation says- <br>
   pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real-world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open-source data analysis/manipulation tool available in any language. It is already well on its way toward this goal.
   <br>
   <br>
   pandas is well suited for many different kinds of data:
   * Tabular data with heterogeneously typed columns, as in an SQL table or Excel spreadsheet.
   * Ordered and unordered (not necessarily fixed-frequency) time series data.
   * Arbitrary matrix data (homogeneously typed or heterogeneous) with row and column labels.
   * Any other form of observational/statistical data sets. The data actually need not be labeled at all to be placed into a pandas data structure.

### Dependencies-
   ```
   pip install pandas 
   ```
  
### Introduction to pandas :

  <br>
   Pandas is used as a data-cleaning tool in the field of data science. You can do whatever operation you want in the dataset with this tool. Now question arises, can we clean or change the value in the dataset manually? The answer is yes we can if the size of the dataset is small. What if we have a large dataset then we can not do it manually it will take a lot of time. Pandas makes data science very easy and effective.
   <br>
   To use pandas you need to first import the pandas module in your program
   ```
     import pandas as pd 
   ```
  <br>  
  
  
####  Reading CSV and Excel sheets:
**d=pd.read_csv("path"):**
   * pd.read_csv() is the function to read the CSV(Comma separated values) file from your computer.
   * In the function you have to pass "path" of the CSV file under quote.
   * Store the dataframe in any variable, here I stored it in variable "df".
   * read_csv() function makes the CSV file into dataframe so that you can access it just like a dictionary. <br>
 
 **df=pd.read_excel("path") :**
   * It is the same as the read_csv() but it reads Excel sheet or file. Here I am using the weather dataset which has all the data of Salary of Employee. In my case, Salaries.csv file is in my current directory that's why the path of the file is file name itself.
   ```
   df=pd.read_csv('Salaries.csv')
   print(df)
   ```
 <br>
 
 # Objective:
 1. Display Top 10 Rows of The Dataset
2. Check Last 10 Rows of The Dataset
3. Find Shape of Our Dataset (Number of Rows And Number of Columns)
4. Getting Information About Our Dataset Like Total Number Rows, Total Number of Columns, Datatypes of Each Column And Memory Requirement
5. Check Null Values In The Dataset
6. Drop ID, Notes, Agency, and Status Columns
7. Get Overall Statistics About The Dataframe
8. Find Occurrence of The Employee Names  (Top 5)
9. Find The Number of Unique Job Titles
10. Total Number of Job Titles Contain Captain
11. Display All the Employee Names From Fire Department
12. Find Minimum, Maximum, and Average BasePay
13. Replace 'Not Provided' in EmployeeName' Column to NaN 
14. Drop The Rows Having 5 Missing Values
15. Find Job Title of ALBERT PARDINI
16. How Much ALBERT PARDINI Make (Include Benefits)
17. Display Name of The Person Having The Highest BasePay
18. Find Average BasePay of All Employee Per Year 
19. Find Average BasePay of All Employee Per JobTitle 
20. Find Average BasePay of Employee Having Job Title ACCOUNTANT  
21. Find Top 5 Most Common Jobs
 <br>

<script defer src="https://use.fontawesome.com/releases/v5.6.3/js/all.js" integrity="sha384-EIHISlAOj4zgYieurP0SdoiBYfGJKkgWedPHH4jCzpCXLmzVsw1ouK59MuUtP4a1" crossorigin="anonymous"></script>   
<i class="fab fa-github"></i> [SaurabhAnand56](https://github.com/SaurabhAnand56)
<i class="fab fa-linkedin"></i>[Saurabh Anand](https://www.linkedin.com/in/saurabhanand56/)
