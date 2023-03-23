# Project-2: Flight Cancellations/Delays-

### Questions:
1. 
2.
3.



### Project Title: Analysis of Flight Cancellation/Delay of 2015

### Team Members of Group 3: Jonathan L, Kevin N, Pratik S, Cheryl Z

![flight-hero](https://user-images.githubusercontent.com/120348065/226772517-a6562c4d-304a-4fdb-88cb-f1040800ca24.jpg)


### Project Description/Outline: 
Our project's goal is to clean the massive datas to deliver a direct database on the delays/cancellation of the flights. We will focus on cleaning the datas, and bringing the datas together to make a clear database. Our objective is to summarize the percentage of delays/cancellation per airport in order to find the most active reason of occurance for cancellation/dalays.

### Datas used:
https://www.kaggle.com/datasets/usdot/flight-delays?resource=download
https://drive.google.com/drive/u/0/folders/1sO-VrUDI7yTd9s5r4WU9LXjrIKL2pfEl

### Cleanup:
Our team initially had difficulties loading the datas to MongoDB, Postgres due the large size of the datas. We found using pandas the easiest way to load/clean our datas. First, the datas were imported as csv files to be observed. Then, datas were carefully cleaned by moving the unwanted columns in the dataframe. By selecting/erasing the useless datas, we can target the type of information we want. We categorized all flights over 30 minutes late from departuring as a delay.

### Summary:
In total, we have 2 jupyter notebook. 
One of the notebook used pandas for cleanup, while the other one uses mongo





