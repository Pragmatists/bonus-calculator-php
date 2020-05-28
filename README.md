Bonus Calculator Kata
==================

## Build
You can build this project using `composer`. You can download composer package manger from: https://getcomposer.org/download/  

Project uses phpunit version 9 that requires a PHP 7.3 or PHP 7.4 (https://phpunit.de/getting-started/phpunit-9.html)

Build project  
``composer install``

Run tests   
``composer tets``

## Requirements

### Individual Bonus
To calculate the bonus, you need to know the salesperson's total sales amount, their quota, their bonus percentage and any tax that must be deducted.

*Examples:*

|Sales	|Quota|	Bonus Percentage|	Tax Percentage | Resulting Value|
|-------|-----|----------------------|-------------------------|---|
|12000	| 11000 |	10        |			            10|		        90.0|
|12000	| 15000 |	10 |			            10|		        0.0|
|12000	| 12000|	10 |		            10|		        0.0|


### Team Bonus
A member of a sales team can get a bonus if their team's total sales exceeds their team's quota.

*Examples:*

|Sales|	Quota|	Bonus Percentage|	Team Members|	Resulting Value|
|-----|------|---------------------|-------------|-----------------|
|12000|	11000|	10			           | 4		       | 25.0|
|12000|	15000|	10			           | 4		       | 0.0|
|12000|	12000|	10			           | 4		       | 0.0|
|12000|	11000|	10			           | 0		       | 0.0|

