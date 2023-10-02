# IA
# Unit 4 Project: Game review app


## Criteria A: Planning

## Problem definition(Client identification)
My client is a grape farmer. He is willing to have a system that will give transparency to his product. He wants his customers to have access to more information about his product. The information will be the general grape information(eg. sweetness, production area), cultivation history, and pest control history. My client is working as a group of grape farmers. Therefore, he also wants to share information about each producer in the group. 
However, there are several issues when implementing this system. First, the client is currently keeping his product data in an Excel file. However, in order to use the data in the system, the data needs to be transferred into a database but the client has no knowledge to do that. Secondly, he does not have a system that could store and manage information about each grape and producer. Lastly, the current situation is that there are no easy methods for the customer to access this information.
By having this system my client’s customers will have enough information to ensure the quality and safety of my client's product. This is very important in order to add transparency to his products.



## Proposed Solution
To tackle the problem defined above, I proposed to create a grape traceability system. Traceability refers to the ability to identify, track, and trace a product as a customer. 

The product will be delivered in the shape of a web application. This is chosen because it allows both stakeholders to access the product very easily since the only requirement is to be connected to the internet.

The back end of the product will be developed by Python. This is chosen for its security, open-source nature, and extensive capabilities. This makes Python a preferable option over Javascript, which has potential security risks. Flask will be used to host the website. It is because it offers high scalability and excellent code control. For data storage, we will use SQLite, known for its proficiency in handling small to medium HTTP requests. It also has the ability to function independently after installation. For the front end (UI), we will create it by using HTML and CSS. It allows us to design and structure the website in detail.

In this system, there will be two stakeholders, the producer and the customer. By using this the producer will be able to manage their product information more effectively and easily. For the customers, the system will allow them to have easy access to a great amount of information about the product, thus greater transparency of the product.



[^3]:Ijaz, Arslan. “JavaScript Vs. Python: Which One is Better? | by Arslan Ijaz | CodeX.” Medium, 20 September 2022, https://medium.com/codex/javascript-vs-python-which-one-is-better-b873f4e69583. Accessed 19 May 2023.

[^4]:Shah, Hardik. “6 Reasons Why Flask is Better Framework for Web Application Development.” Able, 1 December 2021, https://able.bio/hardikshah/6-reasons-why-flask-is-better-framework-for-web-application-development--cd398f73. Accessed 19 May 2023.

[^5]:SQL is 43 years old - here's 8 reasons we still use it today.” Blog, 28 April 2017, https://blog.sqlizer.io/posts/sql-43/. Accessed 19 May 2023.

[^6]:Goyal, Yashi. “Advantages of HTML | Top 10 Amazing Advantages of HTML.” eduCBA, https://www.educba.com/advantages-of-html/. Accessed 19 May 2023.

[^7]:“What Is CSS and Why Should You Use It?” Devmountain, https://devmountain.com/blog/what-is-css-and-why-use-it/. Accessed 19 May 2023.



## Success Criteria
| No. | Success criteria	         | Issue tackled       |
|----------------------------|---------------------------------|----------------|
| 1 | The system will store all information(sweetness, produced area, etc) for each grapes.  | "he does not have a system that could store and manage information about each grape and producer."  | 
| 2 | The system will store all information(maker,product,their self introduction,etc) about each producer. | "he does not have a system that could store and manage information about each grape and producer." | 
| 3 | The program will add the collected data to the database.  | " the data needs to be transferred into a database but the client has no knowledge to do that"  | 
| 4 | The customer can access the information about the producer.  |"he also wants to share information about each producer in the group." | 
| 5 | The customer can access the information about the grape through a barcode.  | "the current situation is that there are no easy methods for the customer to access this information." | 
| 6 | The customer can access the information about the grape by searching with the grape ID. | "the current situation is that there are no easy methods for the customer to access this information.” | 



# Criteria B: Design

## System Diagram
![system](IA1system.png)
## Data Storage
![er](er.png)
## UML Diagram
![uml](uml.png)
## Wireframe
![wireframe](wireframe.png)

## Record of Tasks
| Task No  | Planned Action  | Planned Outcome | Time estimate  | Target completion date  | Criterion |
|:----------|:-------------------------|:----------|:----------|:----------|:----------|
| 1  | Planning: Writing the problem definition | Record the problem definition in the repository | 30 mins  | 2023.07.20    | A   |
| 2  | Planning: Write down the success criteria | record the success criteria and how it is refering the problem definition  | 30 mins  | 2023.07.20    | A  |
| 3  | Design: Create a prototype wireframe and ER diagram |  Get a specific idea of what the website will be looking like   | 30 mins  | 2023.07.20    | B |
| 4  | Development: Coding the template page with html|  Get a specific design for the heading and siddebar which is common through the customer page.   | 30 mins  | 2023.07.20    | C |
| 5  | Development: Create database in SQL |  Create all database needed in the website   | 30 mins  | 2023.07.21    | C |
| 6  | Development: Coding the info block |  Get a specific design of the info block   | 30 mins  | 2023.07.21    | C |
| 7  | Development: Coding the history block |  Get a specific design for the hitory screen   | 30 mins  | 2023.07.21    | C |
| 8  | Development: Create the function for the info block |  get a functional maker block which it shows the info of the grape.   | 30 mins  | 2023.07.22    | C |
| 9  | Development: Create the function for history block |  Get a functional history block where you can see the planting history of the grape   | 30 mins  | 2023.07.22    | C |
| 10  | Development: Coding the Share Screen |  Get a specific design for the Share page   | 30 mins  | 2023.07.22    | C 
| 11 | Development: Create the function for Share Screen |  Get a specific design for the Share page where you can create posts   | 30 mins  | 2023.07.24    | C |
| 12 | Development: Coding the Share Screen |  Get a specific design for the Share page   | 45 mins  | 2023.07.24    | C 
| 13 | Development: Create the function for Share Screen |  Get a specific design for the Share page where you can create posts   | 30 mins  | 2023.07.25    | C |
| 14 | Development: Coding the Add Screen |  Get a specific design for the Add page   | 45 mins  | 2023.07.25    | C 
| 15 | Development: Create the function for Add Screen |  Get a specific design for the Add page where you can add games to your owned list.   | 30 mins  | 2023.07.25    | C |
| 16 | Development: Coding the Profile Screen |  Get a specific design for the Profile page   | 30 mins  | 2023.07.25    | C 
| 17 | Development: Create the function for Profile Screen |  Get a specific design for the Add page where you can see what game you own and posts you created.   | 30 mins  | 2023.07.26    | C |
| 18 | Development: Create the searching function |  Create a search bar and make it functionable.  | 30 mins  | 2023.07.26    | C |
| 19 | Development: Finish all theCSS |  Finish the design of the UI  | 30 mins  | 2023.07.26    | C |
| 20 | Design: Complete the UML diagram |  Show relation of classes  | 30 mins  | 2023.07.27    | B |
| 21 | Design: Complete the flow diagram |  Create three flow charts  | 60 mins  | 2023.07.27    | B |
| 22 | Design: Complete the ER diagram |  Show relation between databases  | 30 mins  | 2023.07.28    | B |
| 23 | Design: Complete the wireframe |  Show relations between each screens and how it works  | 30 mins  | 2023.07.28    | B |
| 24 | Evaluate: Get feedback from client |  Gather feedback from a none client person which is a new perspective  | 10 mins  | 2023.07.28   | B |
| 25 | Evaluate: Get feedback from other users(besides client) |  Gather feedback from a none client person which is a new perspective  | 15 mins  | 2023.07.28    | B |






## Flow Diagrams
### login function
![login](login.png)

### register function
![login](register.png)

### search function
![login](search.png)
## Test Plan
| Instruction                        | Category     | Input example / code                               | Description                                                                                                        | Expected output                                                         | Success criteria |
|------------------------------------|--------------|----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|------------------|
|Test the login   | Unit testing  | Email: banana password: banana  | The user is able to login to the application and the home screen is displayed when they enter | The user logs in if the username and password is correct and the home screen is displayed with a cookie being created as well(The password is for testing)   |2, 3 | 
|Test the login with wrong password | Unit testing  | username: banana Password: melon (wrong password) | The user inputs the wrong password when trying to login | Error message shows the password is wrong | 2  | 
|Test the login with wrong username | Unit testing  | username: melon(does not exist) Password: banana | The user inputs the wrong username | Error message shows the user does not exist | 2  | 
|Test the registration | Unit testing | username: banana password: Melon123 check password: Melon123  | The user inputs their email and passwords and try to sign up | The user is able to sign up and their email and password (which is hashed) is saved in the database 
|Test the registration with wrong inputs | Unit testing | username: bananapass password: abc check password: abc | The user doesnt input the password that reaches the requirement. | An error message is displayed on the user interface 	| 2  | 
|Test the registration with unmatching confirmation | Unit testing | username: bananaconfirm password: Melon123 check password: Banana123 | The user doesnt input matching confirm passport. | An error message is displayed on the user interface 	| 2  | 
|Test the login, registeration, home screen, new posts and profile page  | Integration testing   | uswername: banana Password: Melon123  Check password: Melon123  title: MHXX publisher: Capcom content: Very good | The user is able to signup and then login, letting them go to the home screen where they are able to view everyone's posts and then they are able upload new posts | They are able to signup and login and create a new post that is displayed in the home screen and profile page  | 1, 2, 3, 6 |
|Test the adding function	|Unit testing 	| n/a	| This enables the user to add the games they own to their own list. | The information will be added in the database and user can check them in their profile page.	| 4  | 
| Test the search function  | Unit testing  | Word searched in search bar MHXX   | The user inputs a search word in the search bar which searches the database   | The posts with including the search term is outputted in the home page |  5 |  
|Test the profile page | Unit testing | n/a  | The user clicks the profile button in the sidebar 	| The user is able to see the games they own and the posts that they have posted in the past 	| 6  | 



# Criteria C: Development

## Existing Tools
| Software/Development Tools | Coding Structure Tools          | Libraries      |
|----------------------------|---------------------------------|----------------|
| PyCharm                    | Encryption                      | Flask          |
| Relational databases       | Objects, attributes and methods | sqlite3        |
| SQLite                     | If statements                   | passlib        |
| Python                     |                                 |                |
| Chat GPT                   |                                 |                | 
## List of techniques used

1. Flask library/routes
2. For loops
3. If statements
4. Password hashing
5. Interacting with databases
6. Lists
7. Cookies






## Success criteria
### 1 The system will store all information(sweetness, produced area, etc) for each grapes.
### 2 The system will store all information(maker,product,their self introduction,etc) about each producer.
### 3 The program will add the collected data to the database.
### 4 The customer can access the information about the producer.
### 5 The customer can access the information about the grape through a barcode.
### 6 The customer can access the information about the grape by searching with the grape ID.

### Pattern recognition

### Abstracttion
### Decomposition
I applied decomposition by tackling each success criteria individualy and putting it together afterwards. It made me easier to find the solution of error since individual functions makes it easier to identify the error happening.


## Problem encountered

# Criteria D: Functionality

## Demonstration Video

# Critieria E: Evaluation

## Evaluation table

### Client (Record of this is in the appendix) 
| Critieria | Met or not?        | Feedback       |
|----------------------------|---------------------------------|----------------|
|1. The user can upload their own review towards the game as a social media post. The post includes the title, publisher and content  |Met      |Met, no suggestions	|
|2. There is a login and registration page for each user  | 	Met	| Met, no suggestions		| 
|3. The user can view other social media post  | Met		| Better if you could add photos or videos of gameplay  | 
|4. Users are able to store the games they own.  | Met		| It would be great if you could make a post from your own list| 
|5. Users can search game reviews by title, post creator and publisher.  | Met		|no suggestions			| 
|6. User can have their own profile page that displays their own posts and the game they own.  | Met			| Make the user owned list look better.	| 

### Other user (Record of this is in the appendix) 

| Critieria | Met or not?        | Feedback       |
|----------------------------|---------------------------------|----------------|
|1. The user can upload their own review towards the game as a social media post. The post includes the title, publisher and content  |Met      |Met, no suggestions	|
|2. There is a login and registration page for each user  | 	Met	| Met, no suggestions		| 
|3. The user can view other social media post  | Met		| Better if you could see the other users profile.  | 
|4. Users are able to store the games they own.  | Met		| Mabye make a wish list.| 
|5. Users can search game reviews by title, post creator and publisher.  | Met		|no suggestions			| 
|6. User can have their own profile page that displays their own posts and the game they own.  | Met			| no suggestion	| 

This was after I showed this to my online gaming friend.

## Suggestions for future development

### Post from your own list
The first suggestion was to make it able to create a post from your own list. This could be done by adding a function in the profile page which will redirect to the sharing screen with the selected information(such as title and publisher).

### Images 

The second suggestion was to make it able to share photos and videos in the post. This would be useful since users will be able to give more detail on what they are mentioning in the post. For example if the user is talking about a bug in the gamr they can actualy show the video of it.


# Appendix

## Client interview (planning and design) 
![sp](sp.png)
![sr](sr.png)
*Client and the Developer agreeing to the success criteria*
## Client interview (Feedback) 
![feedback](feedback.png)
*Developer collecting feedback from client*
