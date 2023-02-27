## Here's an example program in Ruby that calculates a person's age and the number of days until their next birthday:

## This program will prompt the user for their date of birth, and then it will calculate current age, the day of the week you were born on, and the number of days until your next birthday.

## To use the program, simply run it in a IDE or code editor environment and follow the prompts.


# Version: 1.0.2
## Here's an optimized version of the Ruby program that reduces the number of method calls and eliminates unnecessary variables: This version of the program reduces the number of calls to Date.today by using the value returned by the first call in subsequent calculations. It also eliminates the today variable, since its value is only used once. Finally, we remove the unnecessary whitespace to make the code more concise. These changes do not affect the functionality of the program, but can help improve its performance and readability.


# Version: 1.0
## In this program, we use the require 'date' statement to import the Date class, which is used to parse the input date and perform calculations on it. We prompt the user to enter their birthdate, and then parse it using the strptime method with the format %m/%d/%Y. We get today's date using the today method, and calculate the age by subtracting the birth year from the current year, adjusting for cases where the user hasn't had their birthday yet this year. Finally, we calculate the number of days until the next birthday by adding one year to the age, getting the date of that birthday, and subtracting today's date. We output the results using the puts method, which prints each message on a separate line. We use the strftime method to format the birthdate day of week as a string in the format %A. Overall, this program is concise and easy to understand, and should work correctly for a wide range of input dates.


## Ray C. Turner