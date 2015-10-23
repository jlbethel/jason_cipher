#jason_cipher
#####jason_cipher website

####By Jason Bethel

##Description

jason_cipher is a Drupal website with Shift Cipher module enabled. The user clicks on the Shift Cipher link in the navigation sidebar, and is directed to a new page with a form. The form fields include the shift value (how many spots in the alphabet the letters will be shifted), the shift direction (right or left), and the phrase that is to be shifted. After hitting the "shift" button, the user is taken to a new page where the new "shifted" phrase is displayed.

##Setup

1. Clone repository from GitHub (to put on the desktop in terminal run ```cd ~/Desktop``` , then run ```git clone https://github.com/jlbethel/jason_cipher.git```.
2. Run MAMP and point the server to the ```jason_cipher``` directory.
3. Bring up phpMyAdmin in your browser by typing ```localhost/phpmyadmin```
4. Import the bookstore_database from ```jason_cipher/sites/db_backup/jason_cipher.sql.zip```.
5. Create a user by clicking the ```privileges``` tab.
6. Set the username to "epicodus" and the password to "epicodus".
7. In another tab of your browser, navigate to ````http://localhost:8888/``` and enjoy the site!


##Usernames and Passwords
MySql:

Username: epicodus
Password: epicodus

Drupal:

Administrator
Username: epicodus
Password: epicodus


##Technologies Used

Drupal 7, MySql

###Legal

Copyright (c) 2015 Jason Bethel

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
