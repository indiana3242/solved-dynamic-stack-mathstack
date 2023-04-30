Download Link: https://assignmentchef.com/product/solved-dynamic-stack-mathstack
<br>
Carefully review Program 18-2 in your textbook, MathStack (starting on page 1071 in the 8th edition and on page 1051 in the 7th edition). This is a <em>static </em>stack, meaning that the size of the stack is set at the beginning of the program (see line 11, page 1073): MathStack stack(5).

modify this program as follows:

1. Implement it as a dynamic stack (do not use a static stack as it is designed in the book).

2. Add functionality for Mult, Div, Pop, and Display.

Make looping menu-driven program to demonstrate your code so that the user has the choice of:

1. Push (an integer onto the stack)

2. Pop (an integer off the stack)

3. Add (the top two values in the stack and replace those two values with the sum)

4. Subtract (the top two values on the stack and replace those two values with the difference)

5. Mult (same as above)

6. Div (same as above but check for div by 0)

7. Display Stack

8. End

<em>Make sure you have both high and lower-level validation. Watch out for division by 0 and not having enough integers on your stack to do the operation. Make sure to only allow integers on your stack. I would suggest that you implement low-level errors the way we did in Chapter 17 (by returning a status flag, -1 if there’s an issue). Finally, make sure main() is properly organized into functions and don’t forget to document your code including your class.</em>