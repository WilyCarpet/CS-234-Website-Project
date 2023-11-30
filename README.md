# CS-234-Website-Project
A project for my CS 234 Database and WebSystems Development class where I used HTML, PHP and SQL to create my website called "Picture Talk."

This is the login page where I take in a username and password from the user and use PHP to communiate with a SQL database that has a record of usernames and passwords. The PHP checks if the password matches the password stored with the input username. If correct then it will redirect the user to the Home page.

![Alt text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Login%20page.png)

If the password or username entered is incorrect it will then send a cookie that will make a paragraph element visible telling the uesr that either username or password entered is incorrect

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Login(wrong%20user%20or%20pass).png)

If the user doesn't have an account they can then go to the registation page where they will enter a username and password. If the username enterd isn't in the table it will then use PHP to encrypt the eneterd password and put it into the registration table.

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Register%20page.png)


If the user enteres a username alraedy in the registration table then it will send a cookie that will make a paragraph element visible telling the user that the username is already taken.

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Register%20(user%20exists).png)

Once the correct username and password is enterd or a valid username and password it used to register then it will send the user to the home page. The user can't access the home page unless they either logged in or registered. The home page is where you can see comments that everybody has posted. You can also like a comment which will be stored in a userlikes table that stores the users username and the id of the comment they liked.

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Home%20page.png)

From home you can access your profile page which shows your username, the ability to created a new comment, and all comments that you've posted.

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Profile%20page.png)

When you click on new comment button it will send you to the new comment page where you can enter what you want to say and when you click post comment it will send you back to the home page where you'll see your new post at the bottom of the page.

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Create%20new%20comment%20page.png)

When you log in with the admin account, the home page will have an admin button that will take you to the admin page.

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Home%20page(Admin).png)

From the admin page you can create a new user by inputing a username and password, or you can choose one the existing account to access their user information.

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/Admin%20access%20page.png)


From the user info page you can change thier username, their password, delete their account, and see all comments that they've posted.

![Alt Text](https://github.com/WilyCarpet/CS-234-Website-Project/blob/main/user%20info%20page.png)

From your profile page, you can log out will will clear the session and allow them to enter a new username and password.


