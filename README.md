# surfs_up
Analyzing weather data using SQLite, VSCode, SQLAlchemy, Python and Flask


## Overview of Project
Hawaii is the most precious jewel in the world. Planning to set up a Surf and Shake shop serving surfboards and ice cream to locals tourists. Invest some of my savings but need some real investor backing to get this off the ground. W. Avy, who is famous for and his love of surfing but he has some concerns about the weather because of past experience. I would like to analyze the one year weather data using hawaii.sqlite database. 

Tools and technologies used: 

* Python

* SQLite

* SQLAlchemy 

* VSCode

* Flask


### Analysis Results: 
* Retrieved keys using Base.classes.keys(). Observed 'Measurement' and 'Station' are the keys.  

![Screen Shot 2022-10-21 at 5 17 52 PM](https://user-images.githubusercontent.com/44387918/197310900-76229f3d-1cb1-4a5a-a98d-98202c2b7866.png)


* Retrieved the amount of precipitation for the year (timedelta(days=365)) and stored in a dataframe.  

![Screen Shot 2022-10-21 at 5 31 19 PM](https://user-images.githubusercontent.com/44387918/197310914-87599a0e-ac8a-4d7d-8300-9f51f8d856b1.png)

* Observed maximum precipitation is 6.7 which is in the last quarter based on the statistics summary and below image. 

![Screen Shot 2022-10-21 at 5 37 41 PM](https://user-images.githubusercontent.com/44387918/197310922-c57281ef-a155-4e6b-a371-763d5bfd6295.png)


![Screen Shot 2022-10-21 at 5 33 15 PM](https://user-images.githubusercontent.com/44387918/197310930-5cd8a89c-7590-4927-a3cb-4d6c9867a842.png)

* Average temperature is 73 °F and the maximum is 83°F based on the temperature data which is good for surfing and no wetsuit required. 

![Screen Shot 2022-10-21 at 5 43 04 PM](https://user-images.githubusercontent.com/44387918/197310952-54db0b49-56e6-46ff-a5a2-9062b776ab2a.png)

![Screen Shot 2022-10-21 at 5 39 26 PM](https://user-images.githubusercontent.com/44387918/197310963-7271d2c9-e019-41e3-b304-c293626a7f94.png)

##  June and December temp data observations. 
1. There’s not much difference observed in terms of Average and Maximum temperatures based on the below data. 

![Screen Shot 2022-10-21 at 6 01 12 PM](https://user-images.githubusercontent.com/44387918/197311003-a2e9bf89-0b07-4622-998f-73b3296e9b5e.png)![Screen Shot 2022-10-21 at 6 01 20 PM](https://user-images.githubusercontent.com/44387918/197311012-22813d8d-5354-43d7-bf0c-d7026bf5a75d.png)


2. December count data is less when compared with June. It may increase /decrease the temp difference. So the current data is not completely accurate. 

3. Minimum temperature is better in June compared to december. 

#### Below is the precipitation data for June and December. 


![Screen Shot 2022-10-21 at 6 21 17 PM](https://user-images.githubusercontent.com/44387918/197311062-a5117752-11b9-4180-8cac-ccf7b7ae2448.png)
![Screen Shot 2022-10-21 at 6 21 08 PM](https://user-images.githubusercontent.com/44387918/197311066-0a2fb741-5c3c-45c5-bc42-80b737cbf0d0.png)


## Summary
Although not much difference is observed in terms of June and December temperatures but variance observed in precipitation. December max precipitation is 6.4 which may or maynot good weather to surf. Current data is insufficient to conclude the good weather. Tourists consider other important factors like tides and wind speed to surf. Would be nice to analyze those data for a better conclusion on the weather.    
