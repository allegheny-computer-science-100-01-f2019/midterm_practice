# CMPSC 100 Practice Questions for Midterm Exam
# Name:


##### Note: These are just some practice questions and the number of questions does not represent the length of the exam.


### Question 1
When we say that Java is an object-oriented programming language, what does that mean?


### Question 2
Give examples of two different types of comments in Java.


### Question 3
In Java, what is an identifier? Give an example.


### Question 4
If you are in your home directory and you type the commands "cd mylabs", "cd lab3'', and "cd ..'', what directory do you end up in? (Assume that all of the directories exist.)



### Question 5
Which package do you find Scanner class in?
* a) lang
* b) util
* c) text


### Question 6
True or False. If `var1` is the name of an `int` variable and `var2` is the name of a `double` variable, the following two statements are acceptable to the Java compiler (do not generate errors):
~~~~
var2 = var1 / 3.0;
var1 = (int) var2;
~~~~

- [ ] True
- [ ] False

### Question 7
Complete the following snippet of a program by writing appropriate Java statements that will calculate the area of the circle, converting the mathematical formula `circle = pi × radius^2` into correct Java representation using the Math class's methods.
~~~~
double circle;
double radius;
Scanner scan = new Scanner(System.in);
System.out.print("Enter a radius");
radius = scan.nextDouble();
~~~~


### Question 8
What are the final values of variables num1 and num2 in each of the following Java code segments? For each one, assume the initial values of `num1` and `num2` are given by:
`int num1 = 10;`
`int num2 = 40;`
* a)
~~~~
if (num2 < 4* num1) {
    num1 = num1 + num2;
} else {
    num2 = num2 - num1;
}
~~~~
* b)
~~~~
if (( num1 == 10 && num2 == 40) || num1 > num2) {
    num2 = 2 * num1;
    num1 = num1 - num2;
} else if ((num2 > 40 || num1 < 5)) {
    num1 = 0;
} else {
    num2 = 0;
}
~~~~


### Question 9
If you need to upload an updated program called Test.java to your GitHub repository, what command(s) do you use? You may assume that you are in the same directory as Test.java in your terminal.

### Question 10
Suppose `line` is a String variable containing a line of text. You may assume that the line of text may contain any mixture of letters, spaces, numbers, punctuation marks, etc. You may also assume that the string has at least two characters in it. Complete the Java statements needed to print each of the following values.
* a) The length of the string `line`
* b) The string `line` with all letters changed to upper case
* c) The middle character of `line`. You can assume that the middle position is the length of `line` divided by 2, no matter if the length is even or odd.
* d) The last two characters of `line.`

### Question 11
Which of the following is NOT a computational thinking technique?
* a) Decomposition
* b) Pattern recognition
* c) Pattern recognition


### Question 12
Something is wrong with each of the statements below. In some cases the errors will cause the compiler to emit error messages and prevent you from executing the program. In others, the program will compile without error, but will issue a run-time error during the execution of the program. Find the errors and correct them. (NOTE: assume that all variables are properly declared and initialized - the errors lie in the formation of the `if` and `while` statements themselves, not elsewhere in the program.)

* a)
~~~~
while (num => 10) {
    num++;
  }
~~~~  
* b)
~~~~  
if (num != 10) {
    num ++;
  }; else {
    num--;
  }
~~~~  
* c)
~~~~  
if (num1 && num2 == 2) {
    num++;
}
~~~~  
* d)
~~~~  
while (num < 10) {
    System.out.println("Increasing number");
}
~~~~  
