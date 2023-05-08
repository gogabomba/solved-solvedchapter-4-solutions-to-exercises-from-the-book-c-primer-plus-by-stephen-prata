Download Link: https://assignmentchef.com/product/solved-solvedchapter-4-solutions-to-exercises-from-the-book-c-primer-plus-by-stephen-prata
<br>
Exercise 1:

Write a program that asks for your first name, your last name, and then prints the names in the format last, first.

Exercise 2:

Write a program that requests your first name and does the following with it:a. Prints it enclosed in double quotation marksb. Prints it in a field 20 characters wide, with the whole field in quotes and the name at the right end of the fieldc. Prints it at the left end of a field 20 characters wide, with the whole field enclosed in quotesd. Prints it in a field three characters wider than the name

Exercise 3:Write a program that reads in a floating-point number and prints it first indecimal-point notation and then in exponential notation. Have the output usethe following formats (the number of digits shown in the exponent may bedifferent for your system):

a. The input is 21.3 or 2.1e+001.b. The input is +21.290 or 2.129E+001.

Exercise 4:

Write a program that requests your height in inches and your name, and thendisplays the information in the following form:

Dabney, you are 6.208 feet tall

Use type float, and use / for division. If you prefer, request the height incentimeters and display it in meters.

Exercise 5:

Write a program that requests the download speed in megabits per second (Mbs)and the size of a file in megabytes (MB). The program should calculate thedownload time for the file. Note that in this context one byte is eight bits.Use type float, and use / for division. The program should report all threevalues (download speed, file size, and download time) showing two digits to theright of the decimal point, as in the following:

At 18.12 megabits per second, a file of 2.20 megabytes downloads in 0.97 seconds.

Exercise 6:

Write a program that requests the user’s first name and then the user’s lastname. Have it print the entered names on one line and the number of letters ineach name on the following line. Align each letter count with the end of thecorresponding name, as in the following:

Melissa Honeybee7 8

Next, have it print the same information, but with the counts aligned with thebeginning of each name.

Melissa Honeybee7 8

Exercise 7:

Write a program that sets a type double variable to 1.0/3.0 and a type floatvariable to 1.0/3.0. Display each result three times—once showing four digitsto the right of the decimal, once showing 12 digits to the right of the decimal,and once showing 16 digits to the right of the decimal. Also have the programinclude float.h and display the values of FLT_DIG and DBL_DIG. Are the displayed values of 1.0/3.0 consistent with these values?

Exercise 8:

Write a program that asks the user to enter the number of miles traveled andthe number of gallons of gasoline consumed. It should then calculate anddisplay the miles-per-gallon value, showing one place to the right of thedecimal. Next, using the fact that one gallon is about 3.785 liters and onemile is about 1.609 kilometers, it should convert the mile- per-gallon valueto a liters-per-100-km value, the usual European way of expressing fuelconsumption, and display the result, showing one place to the right of thedecimal. Note that the U. S. scheme measures the distance traveled per amountof fuel (higher is better), whereas the European scheme measures the amount offuel per distance (lower is better). Use symbolic constants (using const or#define) for the two conversion factors.