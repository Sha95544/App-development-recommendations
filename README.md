# App development recommendations
## Problem Statement
In this example scenario we are aiding an aspiring mobile app developer seeking guidance on the next type of mobile app to build for the Apple App Store based on data driven insights. The analysis is done using SQL

## Entire project walkthrough
A full length aritcle on the entire project can be found on Medium.com at the following link:

https://medium.com/@shaheer-kamal/using-data-driven-insights-to-guide-app-development-ab79c1e67e41

## Dataset
For this project we are using an online dataset from Kaggle which gives us descriptions about the apps available on the app store.

Link to the dataset: https://www.kaggle.com/datasets/ramamet4/app-store-apple-data-set-10k-apps/data

The data comprises of two tables: 'AppleStore.csv' and 'appleStore_description.csv'.

The table 'AppleStore.csv' comprises the following columns as shown below:

![image](https://github.com/Sha95544/App-development-recommendations/assets/62758405/a5b3fbe9-234f-474c-b2c7-c782c88862e0)

Some of the details which will be important in our analysis are shown below:

id: the unique id for each app mentioned.

track_name: Showing the app name.

size_bytes: the memory size of the app in bytes.

price: price for the app in USD, '0' incase its free.

user_rating: the user rating for the app on the App Store.

rating_count_tot: the total number of users who gave the ratings for the app on the AppStore.

prime_genre: the genre for the app such as 'Games', 'Entertainment' etc.

lang_num: the total number of languages that particular app supported within the app.

The table 'appleStore_description.csv' comprises the following columns as shown below:

![image](https://github.com/Sha95544/App-development-recommendations/assets/62758405/2a7f2cd9-2003-49f4-8f2d-25693b3fd563)

Some of the details shown here are:

id: The unique id for each app mentioned.

track_name: Showing the app name.

size_bytes: The memory size of the app in bytes.

app_desc: This gives the description of the app as visible on the App Store.

## Key insights generated
The entire analysis process reveals the following key insights:

The games and entertainment genres have the highest number of apps overall with games having more than 3000 apps in total listed on App Store. So, building a new app within these genres that will also be successful will be very competitive as compared to other app genres. But these results do show the app categories preferred most by users.

Paid apps having higher rating than free ones could signal that in general users perceive a higher return on value from paid apps as compared to free ones and thus are inclined to give better ratings overall and are better engaged within the app. This could offer the developer room to experiment with pricing tiers, offering different levels of features or premium versions at varying price points.

We also saw that apps supporting between 10–30 languages had a much higher rating than those supporting 10 languages only or those supporting a much greater number than 30. This could signal that it's not necessary to include every possible language within a new app rather focus on including the right languages instead which a larger user segment is comfortable with.

A positive correlation between the length of the app description and the average user ratings meanns that users were in general more inclined to rate those apps higher which had longer detailed descriptions. A detailed description provide users with more detailed information about the app's features, functionality, and benefits. This transparency can lead to more informed decisions by users, potentially resulting in higher satisfaction and ratings.
