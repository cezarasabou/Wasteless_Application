# Wasteless_Application
This is a full-stack Angular and Spring Boot web Application which helps users manage their food waste.
Once a user is authenticated he can input grocery lists and see reports of how much food is wasted weekly and monthly. 
A grocery list item has a name and a quantity as well as a calorie value, purchase date, expiration date and consumption date. 
The system also allows users to track goals and minimize waste by sending reminders if waste levels are too high based on ideal burndown rates.
The ideal burndown rate for 100 calories worth of groceries due to expire in 5 days is 20 calories worth of groceries per day. 
The system should provide you with options to donate excess food to various local food charities and soup kitchens 
and notify you of them prior to item expiration.

In this version of the application, the Abstract Factory Pattern was used in order to generate reports in two different formats: text files
and json files.
