# Project-2: Flight Cancellations/Delays-


### Project Title: Analysis of Flight Cancellation/Delay of 2015


### Team Members of Group 3: Jonathan L, Kevin N, Pratik S, Cheryl Z

![flight-hero](https://user-images.githubusercontent.com/120348065/226772517-a6562c4d-304a-4fdb-88cb-f1040800ca24.jpg)

### Note:
-  2 notebook used pandas, while the other 1 uses mongo for aggregration 
- All flight that is 30 mins late, counts as a delay


### Questions:
By observing the 3 data cleanups; the metrics of cancellation/delays, in order to understand the performance of the airports/airlines, we formulated several questions: 
1. What are the top 10 cancellations of the airports/airlines?
2. What are the top 10 airport delays?
3. What are the worst performing airlines with the most delays?
4. What are the worst performing states due to weather delays for the airports?


### Project Description/Outline: 
Our project's goal is to clean the massive database to deliver a direct database on the delays/cancellation of the flights. We will focus on cleaning the datas, and bringing the datas together to make a clear database. Our objective is to summarize the percentage of delays/cancellation per airport/airlines in order to find the most active reason of occurance for cancellation/dalays.

### Datas used:
https://www.kaggle.com/datasets/usdot/flight-delays?resource=download

https://drive.google.com/drive/u/0/folders/1sO-VrUDI7yTd9s5r4WU9LXjrIKL2pfEl  (This is cleaned data from the 3 csv file from Kaggle, the data is cleaned, selected, and put together)

### Cleanup:
First, the datas were imported as csv files to be observed. Then, datas were carefully cleaned by deleting the unwanted columns in the database. By selecting/erasing the useless datas, we can target the type of information we want to get our questions answered. We categorized all flights over 30 minutes late from departuring as a delay, and counted all the cancellations of the flights. After selecting the particular datas needed, the cleaned database was made into a new csv file. The cleaned csv was imported as csv file to find our answers.  


Answers:

1. What are the top 10 cancellations of the airports/airlines?

![image](https://user-images.githubusercontent.com/120348065/227396214-8a7bb4ef-a780-469a-9976-a0bcb6e03a34.png)







1. When we measured cancellations, below are the top 10 cancellations of the airports/airlines (summarized)
3. After we understand the delays, we measure security delay by airport delays (airline is independent variable that has nothing to do with security of the aiport), and therefore, we measured security delay by airport, below: it is the 10 worst airport delay (supported with top percentage) 
4. What are the worst performing airlines that has most delays? We aggregated datas by airline delays. 
7. weather delay, by airports. What are the worst performing airports due to weather delays? In order to answer this, we aggregated the weather delays by airports.
8. What are the worst performing states due to weather delays for the airports? 





