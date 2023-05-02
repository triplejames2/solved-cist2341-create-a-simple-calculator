Download Link: https://assignmentchef.com/product/solved-cist2341-create-a-simple-calculator
<br>
In this exercise, you will create a form that accepts two numbers and an operator from the user and then performs the requested operation.

<ol>

 <li>Start a new project named SimpleCalculator</li>

 <li>Add labels, text boxes, and buttons to the default form and set the properties of the form and its controls so they appear as shown above. Controls are to have meaningful names.</li>

 <li>When the user presses the Enter key, the Click event of the Calculate button fire. When the user presses the Esc key, the Click event of the Exit button fire.</li>

 <li>Rename the form to frmSimpleCalculator. When ask to modify any references to the form, click the Yes button.</li>

 <li>Code a private method named Calculate that performs the requested operation and returns a decimal value. This method should accept the following arguments:</li>

</ol>

Argument                     Description

<strong>decimal num1</strong>                                 The value entered for the first operand.

<strong>string operator1</strong>                              One of these four operators: +, -, *, or /.

<strong>decimal num2</strong>                                 The value entered for the second operand.

<ol start="6">

 <li>Create an event handler for the Click event of the Calculate button. This event handler should get the two numbers and operator the user enters, call the Calculate method to get the result of the calculation, display the result rounded to four decimal places, and move the focus to the Number 1 text box.</li>

 <li>Create an event handler for the Click event of the Exit button closes the form.</li>

 <li>Create an event handler that clears the Result text box if the user changes the text in any of the other text boxes.</li>

 <li>Add a try-catch statement in the btnCalculate_Click event handler that will catch any exceptions that occur when the statements in that event handler executed. If an exception occurs, display a dialog box with the error message, the type of error, and a stack trace. Test the application by entering a nonnumeric value for one of the operands.</li>

 <li>Add three additional catch blocks to the try-catch statement that will catch a FormatException, an OverflowException, and a DivideByZeroException. These catch blocks display a dialog box with an appropriate error message.</li>

 <li>Test the application again by entering a nonnumeric value for one of the numbers. Then, enter 0 for the second operand number to see what happens.</li>

 <li>Code methods named IsPresent, IsDecimal, and IsWithinRange work like the methods described in chapter 7 of the book.</li>

 <li>Code a method named IsOperator to check the text box passed to it contains a value of +, -, *, or /.</li>

 <li>Code a method named IsValidData checks the Number1 and Number 2 text boxes contain a decimal value between 0 and 1,000,000 (non-inclusive) and tOperator text box contains a valid operator.</li>

 <li>Use block or single comments to comment out (do not delete the code) all of the catch blocks from the try-catch statement in the btnCalculate_Click event handler except for the one that catches any exception. Then, add code to this event handler that performs the calculation and displays the result only if the values of the text boxes are valid.</li>

 <li>Test the application to be sure it works correctly.</li>

 <li>Include a header with your name, date, and purpose of the program and meaningful comments throughout the program.</li>

 <li>Zip the entire project folder before submitting to the drop box. Do not go inside the folder created when the project created. To zip right click on the folder -&gt; Click Sent to -&gt; Click Compressed (zipped) folder. Do not go inside the zipped folder to run the program the program compressed. To run the program again, go back to the original folder not zipped.</li>

</ol>







[Project must be completed using Visual Studio using C# .Net language using create a new windows form option in visual studio.]