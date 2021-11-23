# Java-Chatbot

Functionality and design:
We used Swing in Java which is graphical user interface (GUI) toolkit to create a GUI of our chatbot. For our main programming language we used Java programming language. The bot give response and act according to user input. After running our JFrame based code the square box prompt appears which gives us area for text as well as send button. The text area and button combined are used to register user input in our chatbot. And, after chatbot receive the code, it will give output with respect to given input data. 


Api and library:
We connected to weathermap to get data from more than 40,000 weather stations.
Needed an API Key to connect and get the weather data from specific city. To get those information we first added java library form OpenWeatherMap.org Weather APIs in our chatbot project. After that we created weatherApi.java class which consists all the method which can extract live information of weather. Here, we are putting our api key created by signing up in OpenWeatherMap.org.


Dependency:
We added dependencies for httpclient, okhttp, gson,retrofit and converter-gson to get or library up and running to its full potential and adding those dependency is absolutely imperative in order to import pakages.



steps to run our chatbot.
Step 1: Pull the code from gitlab https://gitlab.griffith.ie/ChickenSLAYER94/Java-Chatbot

Step 2: Make sure every code is its place.

Step 3: add owm-japis-2.5.3.0.jar library which is java library form OpenWeatherMap.org.

Step 4: Press run in your emulator.

Step 5: Given user input to the chatbot.

step 6: To get weather information for 5 location, simply give 5 location in the chatbot prompt like tokyo,paris,berlin,istanbul,cairo.


