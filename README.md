# CS5373-TTU-CS-outreach-website
Step by step guide on how to run the program:
1. Download open source platform called XAMPP on your local machine:
http://sourceforge.net/projects/xampp/files/latest/download
2. Start XAMPP Control Panel (Apache and MySQL options must be started) *.
3. Copy the folder “CS_Outreach” from the source to “C:\xampp\htdocs” assuming that XAMPP is installed on your local C drive. The link to download source code from the
dropbox:
https://www.dropbox.com/sh/97ok3xwng3vls7u/AACmqrrGZlxaNLkSGAXzJBU9a?dl=0
4. Create a database called "cs" and table called "new_student" where the table will have six columns called “name”, “age”, “email”, “username”, “password” and “gender” with email as the primary key. If you have trouble making a MySQL database please watch this tutorial: https://www.youtube.com/watch?v=ueWpNe0PG34
5. In the web browser, go to "http://localhost/xampp" assuming that you are using the default port i.e. 80. The XAMPP homepage should open.
6. In the same browser, enter: http://localhost/CS_Outreach/home.php you should be able to see the homepage on your browser.
7. Once you open the login page: http://localhost/CS_Outreach/login_student_page.php you should be able to login using a valid username and password, the one from the table “new_student” from the database “cs”.
8. After the login, you should be able to browse all the WebPages of the website.
* P.S.: If you have any problem with XAMPP, please refer to this website for step by step tutorial on how to run the program: https://blog.udemy.com/xampp-tutorial
