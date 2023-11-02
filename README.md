# INVENTORY MANAGEMENT SYSTEM
# Note:
<p>
1. Only compatible with windows!<br>
2. The installer.pyw module is not part of the project! it exists only to setup the tables and create a user in the mysql and to download(?) the programs and images needed for it
</p>

# Requirements:

1)Pillow module (pip install pillow)

# Flow of execution of code :
<p>
1. First run the installer.pyw program <br>
2. Enter your mysql credentials and proceed <br>
3. Close the window after(only after) getting a prompt that all tables and user have been created succesfully <br>



In the background , the program creates all the neccesary database and tables and creates a new user with username admin and password bav. after closing the window , the program creates and extracts and then deletes two zipfiles which had stored all the images and the programs. (these zipfiles were stored within two corresponding variables within the program itself)

4. Run the main.pyw and enter the username and password
</p>
<p>Usernames and Passwords: there are 3 types of users<br>
<ol>
<li>Employee <br></li><li>Admin <br></li><li>Developer</li>
</ol>
</p>
<p>
1. Employee: <br>Username = first name of any student of 12 A (except aditya , nikhil & indrajith) <br>   Password = 'emp123' <br>
2. Admin: <br>(username , password) = [('indrani vinod','admin123'),('adithya s','adithya123'),('nikhil rajiv','thor@123'),('indrajith lal','indrajith69420')] <br>
3. Developer: <br>Same as of admins! <br>
</p>

Everything from here is self-explanatory!


© Nikhil Rajiv
