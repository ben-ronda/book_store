# Galactic Books [![TeamCity CodeBetter](https://img.shields.io/teamcity/codebetter/bt428.svg?maxAge=2592000)]()

## An app for reviewing Star Wars novels.
#### Created by: [Ben Ronda](https://github.com/ben-ronda)
***
## Description

Galactic Books is a Drupal Web App for reviewing novels in the Star Wars franchise.

### Technologies Used
* Drupal 7
* MAMP  

***
## Installation and Setup

1. Open your terminal and run `git clone https://github.com/ben-ronda/book_store.git`  
2. Download and Install MAMP here: https://www.mamp.info/en/  
3. Launch MAMP and navigate to Preferences>Web Server then Click the little folder icon and choose the folder you cloned from GitHub earlier.  
4. Go to localhost:8888/phpMyAdmin in your Browser
5. Go to the Import tab and import the database file stored in the sites>db_backup within the project directory  
6. After the Database is imported go to the privileges tab and create a user with the following criteria:
* Username: book_admin
* Password: reading
* Set the Host field to localhost
* Hit Go!
7. Now when you visit localhost:8888 everything should show up!

***
## Additional Information
Site Maintenance Info:  
* Username: admin  
* Password: Password

Example Review Role Account:  
* Username: the_review_guy  
* Password: password  


***
## License
[![DUB](https://img.shields.io/dub/l/vibe-d.svg?maxAge=2592000)]()  
Copyright (c) Ben Ronda

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
