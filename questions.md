## Personal details

Name: Deepak Rathi

Country: India

Hourly Rate: $9 USD

Timezone: GMT +5.30

Skype Id: deepak_ibeam

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?

Yes I can available
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 

Git -  7

PHP 5 - 8

CakePHP framework - 8

MySQL -  8

Javascript - 8 

jQuery -  8

HTML - 7

CSS - 7

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?

=> Declare the function outside the class or doing something as classname :: method();

- How do you create a child class of BaseClass ?

=> childClassName extends MainClass(){} 
 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?

=> git reset

- If you want to switch to another branch, what command you need to execute?
=> git checkout -b newbranch
   git branch newbranch
 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.

=> if(isset($var) && ($var != null) && is_numeric($var))

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"

function create_log() {

$fw = fopen('createlog.txt', "w"); 
$addtext = '['.date('Y-m-d H:i:s').']'.' '."- Status OK";
fwrite($fw,$addtext);

}

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
=> /app/Config/database.php

- How you can get the value of a session variable with key "foo" using CakePHP ?

=> $this->Session->read('foo');

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.

Select * from users as U1 Left Join users_data as U2 on U1.ID = U2.USER_ID

- Write a single query to retrieve all the queries that are currently running on the server .

SHOW PROCESSLIST

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
=> document.getElementById("some_img").alt;

- What is the protocol name behind ajax?

=>  XmlHTTPRequest

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.

=>  $(document).ready(function) { $('#ID').fadeIn(); });

- How do you remove an element from the DOM using jQuery?
 =>   remove();
## Questions about HTML

- Which is the doctype syntax for HTML5?

<!doctype html>

- Which is the attribute and value required on forms to allow file uploads?

enctype="multipart/form-data"

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?

=>  overflow-y: hidden

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?

=> clear: both
## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
=> slogin, ssh, and scp

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory

=>  find . -name "*.ctp" -maxdepth 1 grep -l 'ads' 