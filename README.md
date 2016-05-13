#To Do List

####By Aundra Miller

##Description
This applciation was developed as a school project to train us to write PHP code using technologies like MySQL, Silex, Twig, and PHPUnit.

**This project may be incomplete. Its sole purpose was to be a class exercise.**

##Setup / Installation Requirements
To work properly, this application requires:
* Composer
* MAMP (or an alternative - used for local server and MySQL database)

Setup Instructions:

1. Clone this repository to your local computer.
2. Navigate to the root directory.
3. Run `composer install` in the terminal to collect dependencies.
4. Start MySQL server:
  1. Run `mysql.server start`.
  2. Run `apachectl start`.
5. If a database exists, import it:
  1. Navigate to `localhost:8080/phpmyadmin` and login to your MySQL admin.
  2. Select the Import tab and choose the .sql file in the project directory.
  3. Select `Go`.
6. Start the PHP server
  1. In the terminal, navigate the `web` folder.
  2. Run `php -S localhost:8000`
  3. Open `localhost:8000` in a browser.

**Notice: The port numbers may be different on your computer.**

##Support and Contact
If you have questions, contact me at miller.aundra@gmail.com

##License
The MIT License (MIT)

Copyright (c) 2016 Aundra Miller
