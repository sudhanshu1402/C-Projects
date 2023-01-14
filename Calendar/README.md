# Calendar

## Libraries used
- iostream : basic input and output
- cstdlib : this is a general utilities library. Various integer arithmetics, memory management dynamic functions, etc are included in the library.
- iomanip : the functions in this library are used to manipulate the output of the C++ programs.

## Leap Year
- leap_year  : This function checks if the entered year is a leap year or not using the formula.

## Month Functions
- start_day() : This function calculates and returns the start day of the year specified.
- number_days_month() : The number of days depending on the month entered are calculated and returned by this function.
- print_month_name() : For presenting the calendar, this function prints the month name.
- print_month() : This function actually prints the date numbers below the month title for each month.

## Other functions
- skip() : This function is used to add spaces and make the output presentable in calender format.
- error() : This function is used to handle cases of incorrect values respective to the problem and stop the execution (eg month > 12 or month < 1)

## Variables and Function calls
- The user input as the specific year is taken and stored in variable ‘year’.
- The ‘for’ loop is run for 12 times (once for each month) and for each iteration the functions are called to calculate number of days for the month, print month name and print the month dates.

## Input
Input Year = 2000
![run 1](https://user-images.githubusercontent.com/99204211/182341372-2876ae12-5410-4e85-aa94-1ccba38a2c2f.jpeg)

## Output
![o1](https://user-images.githubusercontent.com/99204211/182341400-2d594ea7-d02a-4fbf-b92b-1d6a61c37869.jpeg) 
![o2](https://user-images.githubusercontent.com/99204211/182341405-759ddb74-9747-4b55-8bf9-3d8f00635189.jpeg) 
![o3](https://user-images.githubusercontent.com/99204211/182341410-bb80d775-2b3f-4718-812a-91829e47feed.jpeg)
