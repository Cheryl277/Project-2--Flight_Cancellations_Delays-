# Project 2: Flight Cancellations/Delays-


### Project Title: Analysis of Flight Cancellation/Delay of 2015


### Team Members of Group 3: Jonathan L, Kevin N, Pratik S, Cheryl Z

![flight-hero](https://user-images.githubusercontent.com/120348065/226772517-a6562c4d-304a-4fdb-88cb-f1040800ca24.jpg) 


### Note:
-  1 notebook used pandas, while the other 1 uses mongo for aggregration 
- All flights that are 30 minutes late, counts as a delay
- A cleaned csv file was used to extract datas


### Questions:

By observing the 3 data cleanups; the metrics of cancellation/delays, in order to understand the performance of the airports/airlines, we formulated several questions: 
1. What are the top 10 airports/airlines with the highest percentage cancellation?
2. What are the top 10 airport delays due to security?
3. What are the worst performing airlines with the most delays?
4. Which state has the worst weather delays?


### Project Description/Outline: 
Our project's goal is to clean the massive database to deliver a direct database on the delays/cancellation of the flights. We will focus on cleaning the datas, and bringing the datas together to make a clear database. Our objective is to summarize the percentage of delays/cancellation per airport/airlines in order to find the most occurance for cancellation/dalays per state.

### Datas used:
https://www.kaggle.com/datasets/usdot/flight-delays?resource=download

https://drive.google.com/drive/u/0/folders/1sO-VrUDI7yTd9s5r4WU9LXjrIKL2pfEl  (This is cleaned data from the 3 csv file from Kaggle, the data is cleaned, selected, and put together)

### Cleanup:
First, the datas were imported as csv files to be observed. Then, datas were carefully cleaned by deleting the unwanted columns in the database. By selecting/erasing the useless datas, we can target the type of information we want to get our questions answered. We categorized all flights over 30 minutes late from departuring as a delay, and counted all the cancellations of the flights. After selecting the particular datas needed, the cleaned database was made into a new csv file. The cleaned csv was imported as csv file to find our answers.  


### Answers:

### 1. What are the top 10 airports/airlines with the highest percentage cancellation?

When we masured cancellations, we were observing the airports/airlines with the highest cancellation percentage. Below are hte top 10 cancelations of the airports/airlines. As you can see, most airports' cancellation is above 7%. While most airlines' cancellation is below 5%, we can interpret that the reason for cancellation is based on the airports instead of the airlines.



![image](https://user-images.githubusercontent.com/120348065/227396214-8a7bb4ef-a780-469a-9976-a0bcb6e03a34.png)  ![image](https://user-images.githubusercontent.com/120348065/227396381-c5545165-badd-4cc7-9534-339ed24821e8.png)

### 2. What are the top 10 airport delays due to security?

After we measured the delays, we targeted security delays (airline is independent variable that has nothing to do with security of the aiport), and therefore, we measured security delay by airport, below; it is the 10 worst airport delay due to security. The graph shows that most airports have a low percentage of security delays, with the exception of 2 outliers (Adak Airport and Gistavus Airport). 


![image](https://user-images.githubusercontent.com/120348065/227397819-954ba479-50c5-4254-8faa-c8e04a5b10ff.png)



### 3. What are the worst performing airlines with the most delays?

While we were aggregating the datas on airline delays. We found out that spirit airlines has the worst airline delays. While Delta Airlines has the least airline delays. This graph also reflect the airlines' liability, and passengers' faith in them. 


![image](https://user-images.githubusercontent.com/120348065/227399701-82de90b1-576b-4dca-a0fe-3029b984dc21.png)



### 4. Which state has the worst weather delays?

In order to answer this, we aggregated the weather delays by airports, after getting our results, we look up the percentage of the flights delayed by state. After comparing datas, we found out that the 'percentage of flight delayed state weather' database corresponded with the 'percentage of the delayed flights by weather' database. Showing correlation to our answers. For example, Wilmington Aiport is located in Delaware, Ralph Wien Memorial Airport is located in Arkansas. The states that have the most delays are subjected to bad weather. This finding supports the idea that the weather has a major impact on delays for the airports/flights.

![image](https://user-images.githubusercontent.com/120348065/227401571-928b8275-ef66-47ee-ae90-eba1f537efc6.png)
![image](https://user-images.githubusercontent.com/120348065/227401542-f9b322be-8a05-4f45-bdc2-26501f2ec67e.png)
  




