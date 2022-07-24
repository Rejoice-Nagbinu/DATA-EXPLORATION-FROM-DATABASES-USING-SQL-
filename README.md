# DATA-EXPLORATION-FROM-DATABASES-USING-SQL-
Exploring data from databases using SQL 

## INTRODUCTION 
Data exploration is a series of steps taken to effectively query our database to get the data we need at every particular time from our database, data exploration lets us see our data while we query the database to effectively get the needed data we want to use for analysis
, As this is the first step we take Before cleaning and then analyzing our data it is very important, as it determines if we are going to get the data we need for our analysis and not some other data we do not need at that point in time, so this is a prerequisite for a successful data analysis as it helps us get the right data for analysis to make data-driven good business decisions

In this project I'll walk you through the various steps I took in exploring this data from our database, the database is stored locally in my PostgreSQL database. The whole time I'll be exploring the dataset based on my Managers request

#### Getting familiar with our data set 
Our dataset contains 5 tables, it is the dataset of an imaginary company John&Johnsons that sells papers, the tables are all related together through their foreign and primary keys, here is the ERD(Entity Relationship Diagram) diagram for our dataset below, and an overview of tables in our dataset.
![Screenshot_20220722-214139_1](https://user-images.githubusercontent.com/107328546/180627372-2dd2fa05-bd30-47fe-8394-2b52b719d4ce.jpg)

![Screenshot_20220722-222935_1](https://user-images.githubusercontent.com/107328546/180627405-6051318f-fedc-45fc-b17a-95748edb4bbf.jpg)
![Screenshot_20220722-223146_1](https://user-images.githubusercontent.com/107328546/180627431-5fced17f-a9f2-4874-ab72-b62da53b27fd.jpg)

![Screenshot_20220722-223816_1](https://user-images.githubusercontent.com/107328546/180627434-2277b4b5-9b5f-46d8-a2ac-84114a6a8ea0.jpg)
![Screenshot_20220722-223827_1](https://user-images.githubusercontent.com/107328546/180627443-56cdc317-efe0-4057-9aaf-cdea4f1fb0b1.jpg)

![Screenshot_20220722-224858_1](https://user-images.githubusercontent.com/107328546/180627457-c33e9e36-67e8-49b1-9d85-e74ab4441a89.jpg)
![Screenshot_20220722-224858_2](https://user-images.githubusercontent.com/107328546/180627465-946db352-6f13-41b7-a398-da127ef40414.jpg)

![Screenshot_20220722-225205_1](https://user-images.githubusercontent.com/107328546/180627477-825cccb1-3c85-460d-839a-056df86a521c.jpg)
![Screenshot_20220722-225205_2](https://user-images.githubusercontent.com/107328546/180627487-034c87b3-9b82-4d15-a74d-9cb8955cd6de.jpg)

![Screenshot_20220722-225407_1](https://user-images.githubusercontent.com/107328546/180627501-8f60a0fd-b75b-4efe-a860-8a565f4a13ec.jpg)
![Screenshot_20220722-225407_2](https://user-images.githubusercontent.com/107328546/180627503-2b7db638-df58-45b3-8869-c1f1ced92a29.jpg)

##EXPLORING OUR DATASET: At this point i'll take you through how i write codes to query databases, explore dataset and answer on demand questions from my manager

1. My Manager wants to see the time a web channel is being used, it's account ID, and the channel name for the first 15, obviously I wouldn't need to get the whole data, just a limited one for the first 15
![Screenshot_20220722-230603_1](https://user-images.githubusercontent.com/107328546/180627542-168e6775-38b2-43cf-881d-c076e8e3a2e0.jpg)
![Screenshot_20220722-230603_2](https://user-images.githubusercontent.com/107328546/180627545-8c7a87f5-a682-499f-afe5-13a1bd736139.jpg)





