# CodeClause_Project_Calculator
This code creates a GUI window using Tkinter to build a basic calculator. It consists of an entry widget to display the input and output, number buttons from 0 to 9, operator buttons for addition, subtraction, multiplication, and division, an equal button to evaluate the expression, and a clear button to reset the input.

The button_click function is called whenever a number or an operator button is pressed. It retrieves the current input from the entry widget, appends the clicked button's value to it, and updates the entry widget with the new value.

The button_clear function clears the entry widget.

The button_equal function evaluates the expression entered in the entry widget using the eval() function. If the expression is valid, the result is displayed in the entry widget. If the expression is invalid, an error message is displayed.

Note that the eval() function is used here for simplicity, but it's important to exercise caution when using it, as it can execute arbitrary code. In a production environment, it's recommended to implement a safer and more controlled way to evaluate expressions.




