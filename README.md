Download Link: https://assignmentchef.com/product/solved-cse-110-assignment-5
<br>
<strong>Topics:</strong>

<ul>

 <li>implementing classes</li>

 <li>implementing methods</li>

 <li>object construction</li>

 <li>constructors</li>

</ul>




Your programming assignments require <strong>individual </strong>work and effort to be of any benefit. Every student must work independently on his or her assignments. You must work alone on the assignments – no collaboration of any kind is permitted. <strong>You cannot use Google, StackOverflow, Chegg or any other on-line resources</strong> to look up for the solution. Sharing your assignments with others in any way is <strong>NOT </strong>permitted. Violations of the University Academic Integrity policy will not be ignored.




Violations of the University Academic Integrity policy will not be ignored.     The university academic integrity policy is found at <u>https://provost.asu.edu/academic-integrity</u>

<strong><u>Important Note: </u></strong>All submitted assignments must begin with the descriptive comment block.  To avoid losing trivial points, make sure this comment header is included in every assignment you submit.

/*————————————————————————-

// AUTHOR: your name

// FILENAME: title of the source file

// SPECIFICATION: description of the program

// YOUR Lab Letter and Name of the TA for your Closed lab

// FOR: CSE 110- homework #- days and time of your class

// TIME SPENT: how long it took you to complete the assignment

//———————————————————————-*/

Reasonably good amount of comments should be added in your program so that it is easy for other people to understand it. Please see the comment style in the textbook.

<strong>Part 1: There are no written exercises in this assignment</strong>

<strong><u> Part 2: Programming (20 points):</u></strong>

Write a class definition (not a program, there is no main method) named Geek (saved in a file Geek.java) that models a person who is a geek. For our purposes, a geek is someone who delights in answering all sorts of questions, such as “what is the reverse of a string?”, “what is the sum of all numbers between two numbers?”, “what is a prime number?”, among other things. A Geek has a <strong>name a</strong>nd keeps track of how many <strong>questions</strong> s/he has answered.




Your Geek class must have <strong><u>only two instance variables</u></strong> – the <strong>Geek’s name </strong>and <strong>number of questions </strong>asked so far

<table width="658">

 <tbody>

  <tr>

   <td width="342"><strong>Methods</strong></td>

   <td width="316"><strong>Description of the methods</strong></td>

  </tr>

  <tr>

   <td width="342">public Geek (String name)</td>

   <td width="316">the Geek’s name, the number of questions is assigned to zero</td>

  </tr>

  <tr>

   <td width="342">public String getName()</td>

   <td width="316">takes no parameters and returns the Geeks’s name as a String (don’t count this request in the total questions)</td>

  </tr>

  <tr>

   <td width="342">public int getNumberOfQuestions()</td>

   <td width="316">takes no parameters and returns as an int how many questions s/he has been asked (don’t count this request in the total)</td>

  </tr>

  <tr>

   <td width="342">public boolean isEven (int num)</td>

   <td width="316">takes an integer and returns a boolean value indicating if the num is even or not.Count it as a request.</td>

  </tr>

  <tr>

   <td width="342">public String muliConcat(String text, int count)</td>

   <td width="316">takes a String and integer as parameters and returns a string that consist of the string parameter concatenated with itself count times, where count is the integer parameter. For example if the parameter values are “hi” and 4, the return sting is “hihihihi”. Return the original string if the integer parameter is less than 2. Count it as a request.</td>

  </tr>

  <tr>

   <td width="342">public int sumRange (int num1, int num2)</td>

   <td width="316">takes two integers and computes and returns an int which is the sum of the integers in that range (exclusive)– for full credit this method should return zero if  the two numbers are the same or if the first number is larger than the second.  Also, you cannot assume which number will be greater.Count it as a request.</td>

  </tr>

  <tr>

   <td width="342">public boolean sorted(int num1, int num2, int num3)</td>

   <td width="316">Takes three integers and returns true if they are in order, smallest first , otherwise returns false. Count it as a request.</td>

  </tr>

  <tr>

   <td width="342">public int countA(String text)</td>

   <td width="316">Takes a string and counts and returns the number of times the character ‘A’ is found in the string. It should count lowercase and uppercase ‘a’. Count it as a request.</td>

  </tr>

  <tr>

   <td width="342">public int countDigits(int num)</td>

   <td width="316">Takes an integer and determines number of digits in the number num. Count it as a request.</td>

  </tr>

  <tr>

   <td width="342">public boolean isPrime(int num)</td>

   <td width="316">Takes an integer and returns true if the num is prime and false otherwise. Count it as a request. </td>

  </tr>

 </tbody>

</table>




Save the Geek class in a file called Geek.java and use the following program stored in <u>Assignment5.java,</u> which has the main method to create new Geek object and to test the methods in the class Geek. A sample output is shown below

Important Notes: Your class should have exactly the method headers that are described or otherwise your class will not work with the test driver program (Assignment5.java) that is provided. You should <strong><u>never change the test driver</u></strong> program if the test driver is provided but instead make changes to Geek class to make it work.




<strong> </strong>

<strong>Helpful hints for doing this assignment: </strong>

<ul>

 <li>work on it in steps – write one method, test it with a test driver and make sure it works before going on to the next method</li>

 <li>always make sure your code compiles before you add another method</li>

 <li>your methods should be able to be called in any order</li>

</ul>




Assignment5.java will ask a user to enter one of the following commands. Based on the user’s choice, the program needs to perform corresponding operation. This will be done by using a method you defined in the Geek class. The program will terminate when the user enters ‘q’.




<h1>Here is a sample output: Input is in RED</h1>




Command Options

———————————–

a: Get name b: Num of questions asked c: Is it even d: Multi concat

e: Range between two integers f: Is sorted g: Count a h: Count digits i: Is it prime ?: Display

q: Quit







Please enter a command or type ?

<ul>

 <li>Eisenstein</li>

</ul>




Please enter a command or type ?

<ul>

 <li>0</li>

</ul>




Please enter a command or type ? <strong>c </strong>

Enter a number: <strong>67</strong>

67 is not even




Please enter a command or type ?

<strong>d </strong>

Enter a string: <strong>Fun</strong>

Enter an integer: <strong>4 </strong>

FunFunFunFun




Please enter a command or type ?

<strong>e </strong>Enter the first number: 3

Enter the second number:<strong> 6</strong>

Sum of integers 3 and 6 is 9




Please enter a command or type ? <strong>e </strong>Enter the first number: 3

Enter the second number: 5

Sum of integers 3 and 5 is 4




Please enter a command or type ?

<strong>f </strong>

Enter three integers: <strong>4 2 8 </strong>

Not sorted!




Please enter a command or type ?

f

Enter three integers: 2 4 8

It is sorted!




Please enter a command or type ? g Enter a string: java

The string “java” has 2 a(s)




Please enter a command or type ? g Enter a string: object

The string “object” has 0 a(s)




Please enter a command or type ? h Enter an integer: 76543

Number of digits in 76543 is 5




Please enter a command or type ?

i

Enter a number: 77

77 is not prime




Please enter a command or type ?

i

Enter a number: 13

13 is prime




Please enter a command or type ?

<strong>? </strong>




Command Options

———————————–

a: Get name b: Num of questions asked c: Is it even d: Multi concat

e: Range between two integers f: Is sorted g: Count a h: Count digits i: Is it prime ?: Display

q: Quit







Please enter a command or type ?

q




<strong>Submit your homework by following the instructions below: </strong>

*********************************************************************************

<ul>

 <li>Upload your <strong><u>java and Geek.java </u></strong>files on GradeScope. The link is provided on Canvas</li>

 <li>java should have the following in order:</li>

 <li>In comments, the assignment Header described in “Important Note”.</li>

 <li>The working Java code requested in Part #2.</li>

 <li>The Assignment5.java file must compile and run as you submit it. You can confirm this by viewing your submission results.</li>

 <li>Please check your code after you submit your assignment and make sure you are passing the two test cases.</li>

</ul>







<strong>Important Note: </strong>You may resubmit to Gradescope as many times as you like until the deadline, but we will only mark your last submission.

<strong>No late assignment will be accepted. </strong>

<strong> </strong>

<strong>.</strong>


