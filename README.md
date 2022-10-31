# Distributed-Systems-Project4
**Project 4 - Distributed Systems**

**Project Objective:**

1. Implement a native Android application
2. Implement a web service deployed to Heroku that executes all business logic of the Android application.
3. Handle error conditions (ie. invalid inputs, network errors, API unavaibility, API invalid responses, etc.)
4. Log all traffic through webservice and store data in a noSQL database using MongoDB
5. Create HTML webpage dashboard that displays analytics from traffic logs

Diagram of components and interactions:

<img width="500" alt="Project4-Diagram" src="https://user-images.githubusercontent.com/114946651/199077118-e97703ee-1123-44d5-a3b6-dfb0369a4862.png">


**Tasks:**
1. Choose a 3rd party API and create simple Java application that can make a request & receive a JSON response.
2. Create a MongoDB database on Atlas and create a Java application that can:
    - Prompt the user for a string
    - Write the string to the database
    - Read all documents on the database
    - Print the strings in each document. 
4. Create Android application that has the following:
    - Three different types of Views in Layout (ie. TextView, EditText, ImageView, etc)
    - Takes input from user
    - Makes an HTTP request to web service
    - Recieves and parses JSON response
    - Displays new information to user from response
    - Is repeatable (doesn't require restart for another query)
5. Create the webservice that has the following:
    - Implements an API
    - Receives HTTP request from Android application
    - Executes all business logic appropriate to the applicaiton. This includes fetching JSON information from API, and processing the response.
    - Replies to the Android application with JSON response.
    - Deployed to Heroku.
    - Must use Servlets.
6. Application and web service should both test for and handle errors in the following:
    - Invalid input in the Android application.
    - Invalid server-side input (in the case that application input validation did not catch something).
    - Mobile app network failure, or inability to reach server.
    - Third-party API unavailability.
    - Third-party API invalid data or response.

**Topics/Skills covered:**


**Demonstration of completed tasks:**


