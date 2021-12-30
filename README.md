# MovieReview


Movie Review System
Link to Jira Project:
https://agilea101.atlassian.net/jira/software/c/projects/MOV/boards/2/backlog?atlOrigin=eyJpIjoiMWVkNzAxYmQyZjliNDBmMTgwNzYyNWEwODg0NzNmOGUiLCJwIjoiaiJ9

Project Description 
This System should be a movie review system. It allows user to view Trending movies, recently added movie, read reviews of movies, recommend movies according to the user’s taste. The system should have a tab for list of movies that the user wants to watch later. It should also have a favorites tab that has all movies that are favored by the user. The user can rate the movie and leave reviews of the movies. The user should be able to search through all the movies in the database and add filters to the search. Filters could be viewing movies by: Year of Release, Name (alphabetically), and genre. 
The system should offer users the option of logging into the it or creating a new account. Each account should have an email, name, age, phone number. Movies should be restricted according to user’s age. The password for the created account must follow regular password criteria. The system should verify the email and phone number by validating one time code to the phone number and a verifying email that has a verifying link sent to the sign-up email entered to confirm all data.
The homepage should be classified into banners of movies. Each banner should be of a certain category or genre. Each banner should show the official poster of the movie and its title, and it should be scrollable for easy access. When any movie is tabbed, the system should redirect the user to a details page of the selected movie.  
The detailed page should contain all available information on that movie. That includes title, poster, staring actors, director, producer, year of release, genre, rate, duration, a trailer of the movie, a description of the movie, and reviews made by other users. The detailed movie page should also have a section of reviewing the movie yourself and rating it. The detailed page screen should have a “add to favorites” button as well. The system should have an option of booking currently playing movies in the cinema. It should be able to view what movies are playing in different cinemas.





SCRUM Team:
Team 	Name 	Role	Expertise
1	Ola Mohamed	Product Owner	
2	Esraa Mahmoud	Scrum Master	
3	Heba Mohamed	Code 	C++, C#, Java 
4	Malak Mostafa	Database Management	Python, C++, Java, NodeJS
5	Farah Khaled	Design & GUI	NodeJS, Java, SQL
6	Ahmed Youssef	Code	SQL, C#, Python
7	Amr Ahmed	Design & GUI	Java, JavaScript, Python, React
8	Mariam Tamer	Maintenance	UI/GUI design, HTML
9	Salma Osama	Code 	HTML, JavaScript
10	Yousra Waleed	Maintenance	React, JavaScript, HTML
11	Maha Aly	Tester 	Java, Automation Testing, Python
12	Sondos Mostafa	Tester	Java, Python, SQL, HTML



Stakeholders Matrix:

Name	Role	Availability 	Influence 	Engagement 
Rana Ashraf	Sponsor	Low	High	Keep Satisfied
Ahmed Sami	Subject Matter expert	Low	High	Keep satisfied 
Omar Mohamed	Stakeholder	High	Low	Keep Informed 
Hana Tamer	Stakeholder	High	High	Monitor
Yasmine Mostafa	User	Low	Low	Keep Informed




Near Vision for the first 2 sprints:
The first two sprints that will be executed are as follows.
 The first sprint contains user stories:
1.	As a User, I want to be able to create an account from the login page to access the website. (8 story points)
2.	As a User, I want to be able to login into the home page using my premade account to access the homepage. (8 story points)

The second sprint contains user stories:
1.	As a User I want to be able to use the "Forget your password" function to login to an account when you forgot your password (13 story points)
2.	As a User I want the details page to have all available information about the movie to read more about the movie. (5 story points)

The vision that should be completed by the end of the first 2 sprints is that we should have a system that is capable of letting users create accounts and log in. the system should be able to deal with a user that forgot their password and help them log into their account. The system deals with all the verification and creation of usernames, passwords, and accounts during the login stage. After the user is confirmed and logged into their account, they are forwarded to the home page. If the user clicks on a movie, they should be forwarded into the detailed page of that movie with all the available information about that movie including title, poster, rate, etc.


Story Point estimation:
The convention story point estimation that is used is the modified Fibonacci sequence that follows the 1, 2, 3, 5, 8, 13, 20, 40, 100. This allows us to be accurate without being overly precise.  
Usually a 1 – 3 story point is a small story difficulty, from 5 – 8 is medium story difficulty, and from 13 – 20 is large story difficulty.  



The backlog order:
The backlog order is chosen according to how detailed our user stories are, with the most detailed user stories that complete the definition of ready on the top of the back log and the less detailed user story points on the bottom of the stack. We can always change the order of the backlog as we get more details about each story point and how it will be executed. This means that it is easy to change details and/ or add more details to any given user story.

Estimated of Team Speed:
From past experience with this scrum team, we can finish anywhere from 16 to 20 story point per each sprint.
Bases on this estimation we have our first sprint at estimated 16 story points and our second sprint at an estimated 18 story points.


Sprint Document:
On the first sprint the expected output is a working system with the logging in feature complete. That includes saving all the data entered into the database after verification and validation of all the data considering the sign-up feature. When working with the log in features, we must first verify that the person already has an account and that the entered email and password are correct and that the match the information in the database. We then have transitions between the login interface and the sign-up page, between the login page and the homepage after successful login.
In this sprint we faced a problem with the transfer of the data between the interface and the database. This problem was solved but led to a day delay in work. This did not cause a huge problem as the workload of the first sprint was less than that the team could handle. The rest of the sprint went smoothly, and the deliverables were all met.

Workflow diagram
In this system our workflow consists of 3 states. Our first state is the “To Do” state defined by knowing what we will do during this sprint. The tasks are first identified and can be executed along the timeline of the sprint. After identifying the tasks, we can then move tasks to the “In Progress” state. This is where the executing of the task is done. Here we can build the database, edit the interface, write code, and test depending on the task we have. After the progress is done, tasks can be moved to the “Done” state where the tasks are basically ticked off. 
This workflow is a very simple and easy to flow, it doesn’t restrict the team to a single state that they have to follow. This allows the team to choose the actions that they will take on each task during the progress state. This means that they can add more testing actions to a specific task if they see that fit for a specific task, as long as that is identified from the beginning of the sprint.
