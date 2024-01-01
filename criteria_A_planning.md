## Criteria A: Planning

## Problem definition(Client identification)
My client is a grape farmer. He is willing to have a system that will give transparency to his grape. He wants his customers to have access to more information about his grape. The information will be the general grape information(eg. sweetness, grape, production area), cultivation history, and pest control history. My client is working as a group of grape farmers. Therefore, he also wants to share information about each producer in the group. He also wants a system that will help him analyze the data to give him better idea of how his business is going.
However, there are several issues when implementing this system. First, the client is currently keeping his grape data in an Excel file. However, to use the data in the system, the data needs to be transferred into a database but the client has no knowledge to do that. Secondly, he does not have a system that could store and manage information about each grape and producer. Lastly, the current situation is that there are no easy methods for the customer to access this information.
By having this system my client’s customers will have enough information to ensure the quality and safety of my client's grape. This is very important to add transparency to his grapes. These problems were identified through a face-to-face meeting and email(See appendix for evidence). Throughout this IA, the word "client" will refer to the client himself. The word "producer" will refer to all the farmers under the client's group including the client himself. The word "customer" will refer to the person who is buying the grapes made by the producers.



## Proposed Solution

To tackle the problem defined above, I proposed to create a grape traceability system. Traceability refers to the ability of the customers to identify, track, and trace a grape's information. The information will include, who was the producer, the quality of the grape, etc. This grape will give customers more traceability on the client's grapes.

The grape will be delivered in the shape of a web application. As the stored data would need to be accessible from multiple stakeholders, the grape needed to be hosted on the internet. Considering how the system will be used, it is obvious that the system needs to have mutual interaction with the client. Therefore, a web application would suit this system the most.

Python will develop the back end of the grape. The back end will be the part of the program where it will operate the application and will not be accessed by the users. Python was chosen for the following reasons. First, it is supported by powerful web development frameworks (Django, Flask) that simplify backend tasks and it has a higher security as its frameworks have more built-in security features. Secondly, I am more than familiar with it, which means less time will be needed to understand the code behavior, syntaxes, and grammar. First, python has better accessibility. Thirdly, according to the TIOBE programming index, [^8]Python is the most popular programming language in the world. This means that it is easier for the client to reach out to a Python developer in case further changes are needed. Here we can see Python gives more extensiveness. Flask will be used to host the website. It is because it offers simple and high-speed performance compared to others. Also, it is very Python-friendly as it is included in the Python libraries. This is why Flask was chosen among other alternatives. For data storage, we will use SQLite. It is very lightweight and also can function independently after installation. For the front end (GUI), we will create it by using HTML and CSS. It allows us to design and structure the website in detail.

In this system, there will be two stakeholders, the producer and the customer. By using this the producer will be able to manage their grape information more effectively and easily. For the customers, the system will allow them to have easy access to a great amount of information about the grape, thus greater transparency of the grape.



[^3]:Ijaz, Arslan. “JavaScript Vs. Python: Which One is Better? | by Arslan Ijaz | CodeX.” Medium, 20 September 2022, https://medium.com/codex/javascript-vs-python-which-one-is-better-b873f4e69583. Accessed 19 May 2023.

[^4]:Shah, Hardik. “6 Reasons Why Flask is Better Framework for Web Application Development.” Able, 1 December 2021, https://able.bio/hardikshah/6-reasons-why-flask-is-better-framework-for-web-application-development--cd398f73. Accessed 19 May 2023.

[^5]:SQL is 43 years old - here's 8 reasons we still use it today.” Blog, 28 April 2017, https://blog.sqlizer.io/posts/sql-43/. Accessed 19 May 2023.

[^6]:Goyal, Yashi. “Advantages of HTML | Top 10 Amazing Advantages of HTML.” eduCBA, https://www.educba.com/advantages-of-html/. Accessed 19 May 2023.

[^7]:“What Is CSS and Why Should You Use It?” Devmountain, https://devmountain.com/blog/what-is-css-and-why-use-it/. Accessed 19 May 2023.

[^8]:"TIOBE Index for November 2023",https://www.tiobe.com/tiobe-index/



## Success Criteria
| No. | Success criteria	         | Issue tackled       |
|----------------------------|---------------------------------|----------------|
| 1 | The client will be able to store their grape info and producer info in a database and manage(add, delete, edit) them. | "he does not have a system that could store and manage information about each grape and producer."(This will only give the producer the access to modify stored data.)  | 
| 2 | The system will have a secured login function for the info managing screen. | "he does not have a system that could store and manage information about each grape and producer."(This will only give the producer the access to modify stored data.)  | 
| 3 | The program will add the collected data to the database by converting a CSV file into a suitable format.  | "The data needs to be transferred into a database but the client has no knowledge to do that"  | 
| 4 | The client's customers can view the information about the grapes and producer.  |"he also wants to share information about each producer in the group.","He wants his customers to have access to more information about his grape" | 
| 5 | The client's customers can view the information about the grape through a barcode, allocated to each branch of grapes.  | "the current situation is that there are no easy methods for the customer to access this information." | 
| 6 | The customer can view the information about the grape by searching with the grape ID. | "the current situation is that there are no easy methods for the customer to access this information.” | 
| 7 | The client will be able to see his data in  | "the current situation is that there are no easy methods for the customer to access this information.” | 



| No. | Success criteria	         | Issue tackled       |
|----------------------------|---------------------------------|----------------|
| 1 | The client will be able to manage there  | "he does not have a system that could store and manage information about each grape and producer."(This will only give the producer the access to modify stored data.)  | 
| 1 | The system will have a secured data managing screen for the producer.  | "he does not have a system that could store and manage information about each grape and producer."(This will only give the producer the access to modify stored data.)  | 
| 2 | The client will be able to manage its grape info and producer info. | "he does not have a system that could store and manage information about each grape and producer." | 
| 3 | The program will add the collected data to the database.  | " the data needs to be transferred into a database but the client has no knowledge to do that"  | 
| 4 | The customer can access the information about the grapes and producer.  |"he also wants to share information about each producer in the group.","He wants his customers to have access to more information about his grape" | 
| 5 | The customer can access the information about the grape through a barcode.  | "the current situation is that there are no easy methods for the customer to access this information." | 
| 6 | The customer can access the information about the grape by searching with the grape ID. | "the current situation is that there are no easy methods for the customer to access this information.” | 

