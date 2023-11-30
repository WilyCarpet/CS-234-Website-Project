# CS-234-Website-Project
A project for my CS 234 Database and WebSystems Development class where I used HTML, PHP and SQL to create my website called "Picture Talk."

This is the login page where I take in a username and password from the user and use PHP to communiate with a SQL database that has a record of usernames and passwords. The PHP checks if the password matches the password stored with the input username. If correct then it will redirect the user to the Home page.

![Alt text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Login%20page.png)

If the password or username entered is incorrect it will then send a cookie that will make a paragraph element visible telling the uesr that either username or password entered is incorrect

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Login(wrong%20user%20or%20pass).png)

If the user doesn't have an account they can then go to the registation page where they will enter a username and password. If the username enterd isn't in the table it will then use PHP to encrypt the eneterd password and put it into the registration table.

![Alt Text](

If the user enteres a username alraedy in the registration table then it will send a cookie that will make a paragraph element visible telling the user that the username is already taken.

