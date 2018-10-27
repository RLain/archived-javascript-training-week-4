# javascript-training-week-4
Coursera: JavaScript, jQuery, and JSON - Week 4


MOOC: Coursera - JavaScript, jQuery, and JSON
Prev
Instructor: Charles Severance - University of Michigan
Course Completion date: WIP

Content index:

index.php
- Opening page
- Guides users to the Login page
- Displays profiles and links to an uneditable view.php page
login.php
- Allows users to login
- Password set using md5 Hash
- Form fields with data validation (strlen & strpos)
- Set up to prevent code injection into site
- Error logging
- Requires succcessful login to allow editing of database details
- Flash messages set up

add.php
- Introduction of Javascript 
    - ready(function)
    - click(function(event)
    - event.preventDefault()
    - console.log
    - append()
- Requires successful login to work
- Form fields with data validation (strlen & !is_numeric)
- Set up to prevent code injection into site
- Prepared statements using PDO
- SQl query to insert into database
- Flash messages set up

edit.php
- Requires successful login to work
- Form fields with data validation (!is_numeric)
- Set up to prevent code injection into site
- Prepared statements using PDO
- SQl query to update database
- Flash messages set up
- Guardians set up to ensure specific data requirements are present before changing data
- Introduction of Javascript 
    - ready(function)
    - click(function(event)
    - event.preventDefault()
    - console.log
    - append()
    
delete.php
- Requires successful login to work
- Prepared statements using PDO
- SQl query to delete information in database
- Set up to prevent code injection displaying on site
- Flash messages set up
- Guardians set up to ensure specific data requirements are present before changing data

pdo.php
- Connects to database

logout.php
- Session destroy

util.php
-Function library to prevent code duplication throughout documents
