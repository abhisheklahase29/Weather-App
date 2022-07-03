# Weather-App
                           
                                                                                                                        
  
               1. INTRODUCTION

Weather is what is happening in the atmosphere at any time or short period of time. Weather conditions can change suddenly. Today may be warm and sunny, tomorrow may be cool and cloudy. Weather conditions include clouds, rain, snow, sleet, hail, fog, mist, sunshine, wind, temperature and thunderstorms.

Weather is driven by the heat stored in the Earth's atmosphere, which comes from energy from the Sun. When heat is moved around the Earth's surface and in the atmosphere because of differences in temperature between places, this makes winds. Winds form part of larger weather systems, the most powerful of which is the hurricane. Other weather features like the thunderstorm also develop because of the movement of heat in the atmosphere. Some thunderstorms in the United States give birth to tornadoes.

Like energy, water is moved between the Earth and the atmosphere. The Earth's water cycle plays an important role in the development of many weather features like dew, fog, clouds and rain.

Scientists measure the weather so they can forecast it. This involves plotting weather information on special charts. Weather radar and satellites are now also used to help predict the weather.

This app provides almost accurate weather information of the place you want from all around the world. 







                                                                                                                          
                                                                                                                        


1.3 Objectives of the Project


    • To help people know the weather of a location.
      
    • To provide the ability to display the weather minute basis accurately hourly, weekly or even monthly.



1.4 Feature of weather app Project



    • Time to time update weather
       
    • change weather in every hours as according to weather changes.
    • provide accurate data information about weather.  
    • user can search weather anytime and anywhere.
    • any places data can be search and provide information as according to weather.
    • help user to travel 
      










                                                                                                                   

     
            2. LITERATURE REVIEW

 2.0 General 

Weather forecasting has been one of the most challenging difficulties around the world because of both its practical value in popular scope for scientific study and meteorology. Weather is a continuous, dynamic ,multi-dimensional chaotic process, and data-intensive and these properties make weather forecasting a stimulating challenge. It is one of the most imperious and demanding operational responsibilities that must be carried out by many meteorological services all over the globe. Various organizations / workers in India and abroad have done demonstrating using supported time series data manipulation. 

The various methodologies viz. statistic decomposition models, Exponential smoothing models, ARIMA models and their dissimilarities like seasonal ARIMA models, vector ARIMA models using flexibletime series, ARMAX models i.e. ARIMA with following informative variables etc., which has been used for forecasting purposes. 

Many trainings have taken place within the analysis of pattern and circulation of rainfall in many regions of the world. Totally altered time series methods with different purposes are used to investigate weather information in many different literatures.Accurate and timely weather forecasting is a major challenge for the scientific research. Weather prediction modelling involves a combination of many computer models, observations and acquaintance of trends and designs.

Using these methods, practically accurate forecasts can be made up. Regression is a statistical experimental technique and it must be widely used in many business, the behavioural sciences, social and climate recasting and many other areas





                                                                                                                    
                                                                                                                         
 
         ADVANTAGES AND DISADVANTAGES


 ADVANTAGES


    • There are several benefits of using the weather apps, rather than relying on the regular news broadcasts.

    •  It makes information available 24*7 in a few taps. 

    • Since the advent of smartphones, several weather broadcasting apps have sprawled up in recent times.


DISADVANTAGE 

    • This app will not provide you 100% accurate weather information .

    • This app will take some time to find your current location weather .

    • Cannot detect wind independently 

    • Weather is extremely difficult to forecast correctly


                                                                                                                      


                                                                                                                    
    
                                                                                                                       
  COST AND FEATURES OF WEATHER APP 


Sometimes beauty cannot be defined in just words and statements.
Those lovely flowers and blossoms in the spring, warm sunshiny days in the summer, freezing mornings and the beautiful snow in the winter. 
Certain changes in weather are always wonderful and cherishable. In some or other way our daily lives are dependant on the weather conditions. 
It has been always essential to know the regular updates of weather, as it continuously varies with every passing day.
No one can imagine how the weather is going to be on a subsequent day. Definitely, the Weather forecast is a big thing that enabled many of us to stay notified about the changes in climatic conditions beforehand. 
It can be said that it is one of the greatest advancements of all time, mothered by innovative technologies and creative thoughts. 
The furtherance of the weather forecasting is the weather app development.
:Earth timelapse: The changes in the weather conditions across the globe are simply displayed by using images and pictures. This feature explains the previous climatic conditions, at the present moment and how it will be in the next consequences.
Predictions about the rainfall: This is another fundamental attribute that shows the forecasts for the rain. It also showcases the percentage of likelihood of the rainfall and it is classified into various elements like cloudy, sunny, semi-cloudy, etc.
Time of sunrise and sunset: This feature shows the duration of day and night. It will also mention the sunrise time and the sunset time.
Predictions of Wind: This feature is an added benefit for the fishermen, sailors, windsurfers, paragliders. Also, people who are planning to spend their weekends in outside places are also profited. For general users, this attribute is not that useful.
Updates about Humidity: For, the people who are planning for a long drive or to have a long journey. 
It is always essential to monitor the humidity level and to start the journey.
Map about Climatic conditions: You can get a clear picture of the climate data with this feature. It comprises of humidity level, the temperature of the surroundings, and level of carbon dioxide. This attribute is highly beneficial for scholarly people who are carrying out scientific experiments.
Weather Forecast: It is a fundamental factor of any weather app. This feature displays the prevailing status of the weather on a weekly, monthly, daily and hourly basis.
                                                                                                                         
                                             

   

      




                                                                                                                    
                                                                                                                        
                            
                                 DEVELOPMENT PROCESS

In this project, we will be building a weather application. This application will show the temperature of a location. To fetch weather information we will need an API. An API(Application Programming Interface) is a function that allows applications to interact and share data using various components and micro services. For this project, we will be using Weather Bit API for fetching weather data. Weather Bit API provides a fast and elegant way to fetch weather data. Note that we are going to implement this project using the javascript language.
Project Overview

In this project, we will build an app that will find the device’s location coordinates Then we will send this data to the API via an API key(which we will see later). The API will send us a Open weather map  from which we will extract the required data that is the temperature and city of the location.
















                                                                                                                          
Step 2: Before going to the coding section first you have to do some pre-task

Go to the app > res > drawable file and paste this image to this file. Now right-click on the drawable folder > New > Drawable resource File and name the file as btn_bg6. Below is the code for the btn_bg6.xml file.


Step 3: Get the API key 
 

To get the API key simply sign-in on Open Weathermap and subscribe for a free API of Current Weather Data API. After doing so you will receive an API key and you are good to go.





 



Step  4: Go to browser and search POSTMAN > Downlaod Postman application > Create account on it > Paste your Weather Api key in url section to check if your Weather Api key is working or not.

If Api key is working then copy this key and paste in Android Studio






Step 5: Building the Layout

 

We will add a Button and Text View in the one and only screen of the application. 
When the user will click the Button the temperature and city of that location will be shown in the TextView. See the code below:

                                                                                                               

Step 6: Working with the MainActivity.java file


Go to the MainActivity.java file and refer to the following code. 
Below is the code for the MainActivity.java file. Comments are added inside the code to understand the code in more detail




                        
















                                      

                                                                                                                 
            
                            CONCLUSION

With the advancement of technology weather forcast has developed to its level best, but there is yet to develop , 
as far as a nature is so unpredictable. Natural calamities and weather disturbances causing devastating destructions surprisingly. 
To save our mother earth scientists and meterorologist are also advancing their knowledge about weather forcasting. 







                                                                






                         
                                                                                                                        
                                                                                                                    

                     REFERENCES

    • GeeksforGeeks at youtube : https://youtu.be/q7NF-2gtfEU

    • Open weather map api key : https://openweathermap.org/api

    • Postman: https://www.postman.com/

    • Wikipedia: https://en.wikipedia.org/wiki/Weather_forecasting                                                                                                                                                                       














                                                                                                                         Page 25
