Download Link: https://assignmentchef.com/product/solved-cs271-assignment-1
<br>
Write and test a MASM program to perform the following tasks:

<ol>

 <li>Display your name and program title on the output screen.</li>

 <li>Display instructions for the user.</li>

 <li>Prompt the user to enter two numbers.</li>

 <li>Calculate the sum, difference, product, (integer) quotient and remainder of the numbers.</li>

 <li>Display a terminating message.</li>

</ol>

<strong>Requirements</strong>:

<ol>

 <li>The main procedure must be divided into sections:

  <ul>

   <li>introduction</li>

   <li>get the data</li>

   <li>calculate the required values</li>

   <li>display the results</li>

   <li>say goodbye</li>

  </ul></li>

 <li>The results of calculations must be stored in named variables before being displayed.</li>

 <li>The program must be fully documented. This includes a complete header block for identification, description, etc., and a comment outline to explain each section of code.</li>

 <li>Submit your text code file (.<em>asm</em>) to Canvas by the due date. <strong>Notes</strong>:</li>

 <li>A program shell (template) is available on the course website.</li>

 <li>You are not required to handle negative input or negative results.</li>

 <li>You may submit only one of your programs up to 48 hours late without penalty. Try not to use this on the first program.  A second late submission will not be accepted.</li>

 <li>To create, assemble, run, debug, and modify your program, follow the instructions at <u>http://www.kipirvine.com/asm/gettingStartedVS2015/index.htm</u>.</li>

</ol>

(Or other version for different version of Visual Studio)

<ol start="5">

 <li>Find the assembly language instruction syntax in the textbook.</li>

 <li>Find help on using Irvine library procedures in in the textbook.</li>

</ol>




<strong>Example execution (</strong>user input is in <strong><em>italics</em>)</strong>:

Elementary Arithmetic     by Wile E. Coyote

Enter 2 numbers, and I’ll show you the sum, difference, product, quotient, and remainder.




First number: <strong><em>37</em></strong>

Second number: <strong><em>5</em></strong>




37 + 5 = 42

37 – 5 = 32

37 x 5 = 185

37 ÷ 5 = 7 remainder 2




Impressed?  Bye!




<strong>Extra-credit options </strong>(original definition must be fulfilled):

<ol>

 <li>Repeat until the user chooses to quit.</li>

 <li>Validate the second number to be less than the first.</li>

 <li>Calculate and display the quotient as a floating-point number, rounded to the nearest .001.</li>

</ol>




To ensure you receive credit for any extra credit options you did, you must add one print statement to your program output PER EXTRA CREDIT which describes the extra credit you chose to work on. You will not receive extra credit points unless you do this. The statement must be formatted as follows…




–Program Intro–

**EC: DESCRIPTION




–Program prompts, etc—

For example, for extra credit option #2:




Elementary Arithmetic     by Wile E. Coyote **EC: Program verifies second number less than first.




Enter 2 numbers, and I’ll show you the sum, difference, product, quotient, and remainder.




First number: <strong><em>7</em></strong>

Second number: <strong><em>9</em></strong>




The second number must be less than the first!