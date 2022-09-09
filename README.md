# INVENTORY_MANAGEMENT_SYSTEM
(class 12 project) #note: 1)only compatible with windows! 2)the installer.pyw module is not part of the project! it exists only to setup the tables and create a user in the mysql and to download(?) the programs and images needed for it

#requirements: 1)pillow module (pip install pillow)

#flow of execution of code 1)first run the installer.pyw program 2)enter your mysql credentials and proceed 3)close the window after(only after) getting a prompt that all tables and user have been created succesfully

in the background , the program creates all the neccesary database and tables and creates a new user with username admin and password bav. after closing the window , the program creates and extracts and then deletes two zipfiles which had stored all the images and the programs. (these zipfiles were stored within two corresponding variables within the program itself)

4)run the main.pyw and enter the username and password

usernames and passwords: there are 3 types of users, i)employee , ii)admin, iii)developer

1)employee: username = first name of any student of 12 A (except aditya , nikhil & indrajith) password = 'emp123'

2)admin: (username , password) = [('indrani vinod','admin123'),('adithya s','adithya123'),('nikhil rajiv','thor@123'),('indrajith lal','indrajith69420')]

3)developer: same as of admins!

everything from here is self-explanatory!

