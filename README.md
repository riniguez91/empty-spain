# "Empty Spain"

Application that analyzes various sources of information (news/reviews etc.) about dying rural towns in Spain and offers the user various functionalities depending on its privileges, aimed to offer a solution in order to stop rural towns dying from lack of population. 

Currently the machine learning model (Logistic Regression) has been trained with a dataset of 146 documents obtained through the Pentaho scrapper built, and we decided to use this model based on the performance obtained by it and various others in RapidMiner.
As part of our university coursework subjects "Computing Projects I, II and III" we will finish the project by May 2021 and we will implement the application using Angular and Flask along with Laravel and mySQL for the back-end and sentiment analysis for the information obtained.

User functionalities we plan on including:
* Login/register
* Tab with existing solutions to the problem, which include ones such as Hyundai ("proyecto Vive"), "Adopt an olive" etc.
* Rural tourism with routes established by the administrator (in the future the user can see what the towns have in common or different to make their own route and if it is accepted by the administrator it becomes official for people to join, possible implementation with google maps)
* Route scoring system (upvote, downvote) and comments/reviews of this routes
* Present in a user-friendly way the services of these towns (hotels, restaurants etc.)
* Based on nearby towns, services and reviews obtained by TripAdvisor offer the user our opinion on whether we recommend visiting or living in the area with the last being aided by idealistalabs API: https://www.idealista.com/labs/
* Frequent Q&A
* Admin dashboard with website statistics

# Authors
* github.com/riniguez91
* github.com/victor00hs
* github.com/rubenoritznieto
