# php-basics-01

Get to your submission folder under exercises/php-basics-01
You should create a PHP file for each step with the name of the step.

e.g : Step_1.php

COMMIT AFTER EACH STEP, call each commit by the name of the step

Goals

Learn general basic programming syntax as applied to PHP
Competencies:
opening / closing tags
variables
strings
strings concatenation
Integers & Floating numbers
Arrays
simple maths
if, else
User defined functions
Debugging

Step 1 : Opening and Closing tags

Outputting static text without using PHP
On the first line write "Hello world, Help me I am using PHP"
On the Second line open PHP tag <?php
On the Third line close the PHP tag ?>
Run the PHP file

Step 2 : Echo & Print

Outputting text using PHP
Copy & Past the content of the pervious step
Between the PHP Opening & Closing tags and on a new line output "I am getting errors but I can't see the errors".
. Using a different method, output "Search on how to enable PHP Errors";

Step 3 : Variables lvl 1

Creating variables in PHP, String & Number variables
Create a variable called $name and assign your name to that variable
Create another Variable called $email and assign your email to that variable
Output 'My name is "$name" and my email is "$email".' Example: My name is Gaby and my email is info@gabykaram.com
Create a variable called $height and assign to it a numerical value
Create a variable called $width and assign to it another numerical value.
Create a variable called $area and assign to it the multiplication of the two variables $height & $width.
Output the area value.
<?php
$variable_name = 'something';
$another_variable_name = 12;

// Output
echo $variable_name;
?>

Step 4 : Strings Concatenation

PHP have 4 ways to concatenate strings, in this step we will be going over 3 of them.
Create a 3 variables, name, position & github_url and assign them there with respective values.
Output the 3 variables using the 3 methods below, the output should be similar to this one Hello, I'm Gaby, I'm a tech consultant please check my github link https://github.com/gk-git.
Using the double quotation " and the .
Using the double quotation " and without using the .
Without using the double quotation ".
(Optional) try to output the previous without using the . and without using the previous answer from any of the previous solutions

Step 5 : Data types - lvl 1

Variables can store data of different types, and different data types can do different things.
Create a String $course_name variable and assign to a course title that you like to learn.
Create an Integer $enrolled_students variable and assign to it the number of enrolled students.
Create a Float $price variable with the course price. A float variable is a decimal number ( 12.33, -1.123, 99.99)
Create a Boolean $on_discount vaiable that will say if the course is on discount
Output the course information
Course title: Rust, the language of no bugs
Enrolled Students: 20
Course price: 30 $ USD
Course on discount: Yes / No

Step 6 : PHP User defined Functions

In all programming and scripting language, a function is a block of statements that can be used repeatedly in a program. In PHP, the concept of the function is the same as in another language like 'C'. There are more than 1,000 in-built functions into the standard PHP distribution. Besides these, we can define functions as per our requirements. These are called 'User Defined Function'.
Create a PHP function calculateArea.
The calculateArea function should takes 2 parameters $height, $width.
The function should output "Area is 25" if $height = 5 & $width = 5.
Call the function by passing two values 5 for height & 3 for width.

Step 7 :PHP Control Statements -  If / else

The if statement execute a single statement or a group of statements if a certain condition is met. It can not do anything if the condition is false. For this purpose else is used.
Create an Integer birth_year and assign it to any random year.
Create an Integer current_year and assign the current year to it.
Write an if else statement that check if the different between the two variables is greater than 18.
If thr difference is greater than 18, output "You can drive" otherwise output "You still a kid, go and play GTA`

Step 8 : PHP Data types - Array

In PHP there is two kinds of arrays : indexed array and associative array. The only difference is that numeric values are used as 'keys' in indexed array start from zero (0) and in associative array, strings are used as 'keys'. PHP does not differentiate between indexed and associative arrays, therefore a PHP array may contain strings as well as integers as 'keys'

Step 8 - a : PHP Data types - Indexed Array

Create an Indexed Array of grocery with the following items: Eggs, Milk, Cheese, Water Pack, Tissues, Watermelon.
Output the first 3 items of the array and the last item using the following message, Hello Sir, do you have Eggs, Milk, and Cheese? Also if you sell fruits can I find a Watermelon?

Step 8 - b : PHP Data types - Multidimensional Array

Create a Multidimensional Array with the following items: egss ( 'balade', 'mazere3' ), milk ('Fresh', 'Taanayel'), water-pack ( 'Tanoureen', 'Reem')
Output the following sentence, "Hey Sir, Please I need 1 pack of balade eggs and 3 Reem Water Pack.
Output the prvious syntax using the array previously declared.

Step 9 : PHP Debug - die() and var_dump()

Debugging in PHP
Create a variable name assign it to your name.
Write var_dump($name);
Run the programme
Add another variable under var_dump 
Hints
To run a php file, on the terminal run php <path-to-php-file>
example php ./basic-01/step-1.php
