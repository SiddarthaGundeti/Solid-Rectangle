# Solid-Rectangle

Tutorial: Solid Rectangle

The task is to write a program that takes two integers M and N, and prints a solid rectangle pattern of M rows and N columns using the asterisk character (*). Let's get started!

Step 1: Read the Input
The first thing we need to do is to get input from the user. In our case, we need to get two positive integers from the user: the number of rows and the number of columns.

The input() function allows us to take user input from the console. We use the int() function to convert the user's input from a string to an integer. We store the user's input in the variables "rows" and "columns".

Step 2: Print the Solid Rectangle Pattern
Next, we need to print a solid rectangle pattern of M rows and N columns using the asterisk character (*). We will use a while loop to iterate through each row of the rectangle.

The variable "counter" is used to keep track of the number of rows we have printed so far. We start with the first row, which has an index of 0. 

The while loop will continue until the counter is less than the number of rows we need to print. Inside the while loop, we use the print() function to print each row of the rectangle. 

To print the asterisk character (), we use " " and multiply it by the number of columns. The " " represents the asterisk character followed by a space. The multiplication operator () repeats this sequence of characters the specified number of times, which is equal to the number of columns. 

Finally, we increment the counter by 1 in each iteration of the loop.
