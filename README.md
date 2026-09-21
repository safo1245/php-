# php-

Week 1: PHP Programming Practice

This folder contains my Week 1 PHP practice work and screenshots from the Web Application Development - PHP & MySQL course.
The exercises in this week focus on PHP syntax, output statements, variables, constants, and control structures.

1. PHP Output with Echo and Print
Screenshot Name
PHP_Output_Echo_Print.png
Description
This exercise demonstrates different ways of displaying information in PHP using echo and print.
It also demonstrates how PHP can display HTML elements.
Concepts Covered

Using echo to display text.

Using print to display text.

Displaying HTML elements with PHP.

Using different types of output statements.

Code Example
<?php

echo "Good morning!";

print "Learning PHP is interesting.";

echo '<h2>Welcome to my PHP practice</h2>';

?>
Output
Good morning!
Learning PHP is interesting.
Welcome to my PHP practice
Screenshot
PHP Output Echo Print

2. PHP Variables and Constants
Screenshot Name
PHP_Variables_Constants.png
Description
This exercise demonstrates how PHP variables and constants can be used to store and display information.
Variables can contain values that may change, while constants store values that remain fixed.
Concepts Covered

Creating variables using the $ symbol.

Assigning values to variables.

Displaying variable values.

Creating constants using define().

Displaying constant values.

Code Example
<?php

// Variables
$name = "Safiya Suleiman";
$age = 21;

echo "Student Name: $name";
echo "Student Age: ", $age;
 
// CONSTANT

    define("UNiversity_Name", "Jamhuuriya UNiversity");

    echo "UNiversity" . UNiversity_NAME . "<br /><br />";

?>
Output
Student Name: Safiya Suleiman
Student Age: 21
UNiversity: Jamhuuriya UNiversity
Screenshot
PHP Variables and Constants

3. PHP Conditional Statements
Screenshot Name
PHP_Control_Structures.png
Description
This exercise demonstrates how PHP conditional statements are used to make decisions based on different conditions.
The main conditional structures practiced are if, elseif, else, and switch.

If / Elseif / Else Statement
The if, elseif, and else statements allow a program to check conditions and execute different code depending on the result.
Code Example
<?php

$score = 78;

if ($score >= 90) {

    echo "Excellent result.";

} elseif ($score >= 70) {

    echo "Good result.";

} else {

    echo "You need more practice.";

}

?>
Explanation

The program checks the value stored in $score.
If the score is 90 or higher, it displays:
Excellent result.
If the first condition is false but the score is 70 or higher, the elseif statement is executed.
Otherwise, the else statement is executed.
For example, when:
$score = 78;
the output will be:
Good result.

Switch Statement
The switch statement can be used when a program needs to compare one value with several possible cases.
Code Example
<?php

$day = "Monday";

switch ($day) {

    case "Monday":

        echo "Start of the week.";

        break;

    case "Friday":

        echo "Weekend is near.";

        break;

    case "Sunday":

        echo "It is a relaxing day.";

        break;

    default:

        echo "It is a normal day.";

}

?>
Explanation

The program checks the value stored in $day.
For:
$day = "Monday";
the matching case is:
case "Monday":
Therefore, the program displays:
Start of the week.
The break statement stops the switch after the matching case has been executed.
The default section runs when the value does not match any of the listed cases.
Screenshot
PHP Control Structures

4. Complete Week 1 Practice

The following code combines the PHP concepts practiced during Week 1.
Complete Code
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHP Week 1 Practice</title>
</head>

<body>

    <?php

    // OUTPUT

    echo "Good morning!";

    print "Learning PHP is interesting.";

    echo '<h2>Welcome to my PHP practice</h2>';


    // VARIABLES

    $name = "Safiya Suleiman";

    $age = 21;

    echo "Student Name: $name <br />";

    echo "Student Age: $age <br />";


    // CONSTANT

    define("UNiversity_Name", "Jamhuuriya UNiversity");

    echo "UNiversity" . UNiversity_NAME . "<br /><br />";


    // IF / ELSEIF / ELSE

    $score = 78;

    echo "<b>Score Evaluation:</b><br />";

    if ($score >= 90) {

        echo "Excellent result.<br />";

    } elseif ($score >= 70) {

        echo "Good result.<br />";

    } else {

        echo "You need more practice.<br />";

    }


    // SWITCH

    $day = "Monday";

    echo "<br /><b>Day Evaluation:</b><br />";

    switch ($day) {

        case "Monday":

            echo "Start of the week.<br />";

            break;

        case "Friday":

            echo "Weekend is near.<br />";

            break;

        case "Sunday":

            echo "It is a relaxing day.<br />";

            break;

        default:

            echo "It is a normal day.<br />";

    }

    ?>

</body>

</html>

5. What I Practiced
   
During this week's practical work, I practiced:

Displaying text using echo.

Displaying text using print.

Creating and using PHP variables.

Creating constants using define().

Using if, elseif, and else.

Using switch, case, and default.

Using break in a switch statement.

Combining PHP code with HTML.

6. Learning Outcome
   
After completing these exercises, I gained a better understanding of basic PHP programming concepts.
I learned how to display information, store data using variables and constants, and use conditional statements to make decisions in a PHP program.

8. Files and Screenshots

The Week 1 folder contains the following practical files and screenshots:
Week1/
│
├── php_output.php
├── php_variables.php
├── php_control_structure.php
│
├── screenshots/
│   ├── php_output.png
│   ├── php_variables.png
│   └── php_control_structure.png
│
└── README.md
10. Progress

Topic	Status
PHP Output	        ✅ Completed
Echo and Print      ✅ Completed
Variables        	  ✅ Completed
Constants	          ✅ Completed
If / Elseif / Else  ✅ Completed
Switch Statement	  ✅ Completed

 Week 1 Completed


