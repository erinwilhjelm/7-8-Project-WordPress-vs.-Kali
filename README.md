# 7-8-Project-WordPress-vs.-Kali

1. Cross-Site Scripting (XSS) 

Summary: 
Vulnerability types: XSS
Tested in version: 4.2.2
Fixed in version: 4.2.3

![Alt Text](https://github.com/erinwilhjelm/7-8-Project-WordPress-vs.-Kali/blob/master/xss-1.gif)

Steps to recreate: While creating a post or page, enter in the follwing code in the html "text" section. 


2. User Enumeration
Summary:
Vulnerability types: User Enumeration
Tested in version: 4.2.2
Fixed in version: N/A

![Alt Text](https://github.com/erinwilhjelm/7-8-Project-WordPress-vs.-Kali/blob/master/User%20Enumeration.gif)


Steps to recreate: When entering in a username that is not in the database Wordpress will prompt the error "ERROR: Invalid username. Lost your password?" however when entering a username that is in the database, e.g admin. Wordpress will display the error "ERROR: The password you entered for the username admin is incorrect. Lost your password?" hence exposing vaild usernames. Note that you also must enter in a password inorder to recieve these errors. 

3.  Cross-Site Scripting (XSS) 
Summary: 
Vulnerability types: XSS
Tested in version: 4.2.2
Fixed in version: 4.2.X


![Alt Text](https://github.com/erinwilhjelm/7-8-Project-WordPress-vs.-Kali/blob/master/xss-2.gif)

Steps to recreate: Another version of xss can be down on wp through the comment section. Insert the code in the comments of a post.
