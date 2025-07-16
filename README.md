# Big_data_analysis
"Company"  : CODTECH IT SOLUTIONS
"Name"     : D.Bhargavi
"Intern ID": CT06DG3032
"Domain"   : Data Analytics
"Durtion"  : 4 weeks
"Mentor"   : Neela Santhosh kumar

Task 1 - Big Data Analysis Using PySpark

->Task Objective:
In this task, I worked on analyzing a dataset using PySpark. The main goal was to show how PySpark can handle big data and do simple analysis easily and faster.

->Tools Used:
- Google Colab (for running code online)
- PySpark (for data analysis)
- Python (programming language)

 -> Dataset
I used a CSV file called `hw_200.csv`. It has the height and weight details of 200 people. The data is not huge, but it helped me practice and understand how PySpark works with real data.

->Steps I Followed
- First, I installed PySpark using pip (just one line of code).
- Then, I started a Spark session inside Colab.
- I uploaded the CSV file and loaded it using `spark.read.csv()`.
- I looked at the data using `.show()` and `.printSchema()` to understand its structure.
- I did some simple analysis like:
  - Counted how many rows are there
  - Found the average height and average weight
  - Filtered people who are taller than 70 in
 
-> Key Insights:
The file had 200 records.
- I got the average height and weight using PySpark functions.
- I could also see how many people are above 70 inches.
- Even though the data was small, I saw how PySpark can make working with big data much easier.

->Conclusion
This was my first task for the CODTECH Internship. I completed it successfully using PySpark in Google Colab. Everything worked well, and I understood how to do simple data analysis using PySpark.
