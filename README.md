# Getting-Started-With-Java

Name: Gopal Khandelwal 

Basics of Java programming language. 
-------------------------------------------------------------------------

Some Important Questions MCQ 

Question 1: Primitive data type 'long' is having size _______ byte(s) in Java Programming. 
Ans : 8  

Explaination
The size of long is 8 bytes in Java.
-------------------------------------------------------------------------
Question 2: Which of the following data type stores longest decimal number ? 
This problem has only one correct answer
long
float
double
short

Ans Option: C double 8 bytes 

Explaination
Stores the maximum of Decimal Number. Out of all given options, only float and double can hold decimal numbers. Size of the float is 4 bytes and double is 8 bytes (in most of the compilers, as the size of data types is compiler specific). So double can store bigger decimal numbers.

---------------------------------------------------------------------------

Question 3: Which of these values can be assigned to a boolean variable in Java?
This problem has only one correct answer
a. 0 or 1
b. Any integer value.
c. true or false
d. Both options a and c

Ans: C true or false 
Explain
Boolean variable in java can only hold either true or false value.

------------------------------------------------------------------------------
Question 4: Which of these is a valid variable name ? 

This problem has only one correct answer
1var
var1
var@1
2_var

Ans: B var1 In java, you cannot start your variable name with numbers and also they cannot contain any other special character except underscore (_) and dollar ($).

Question 5: What is the output of the following code if the input is : 5 10 ?
Scanner s = new Scanner(System.in);
int a = s.nextInt();
int b = s.nextInt();
System.out.println(a+b);

This problem has only one correct answer
5
10
15
Error

Ans: C 15 

Explaination
"s.nextInt()" scans and returns the next token as int. A token is part of entered line that is separated from other tokens by space, tab or newline. So when input line is : “5 10”, then s.nextInt() returns the first token i.e. “5” as int and s.nextInt() again returns the next token i.e. “10” as int

Question 6: What is the output of the following code if the input string is "Coding Ninjas"?
Scanner s = new Scanner(System.in);
String str;
str = s.next();
System.out.print(str);

This problem has only one correct answer
Coding Ninjas
Coding
Ninjas
The above code fragment does not compile

Ans: B Coding 

Explaination
"s.next()" returns the next token as String. A token is part of entered line that is separated from other tokens by space, tab or newline. So when input line is - “Coding Ninjas” then s.next() returns the first token i.e. “Coding”

Question 7: What is the output of the following code if input is :
10 abc def

Scanner s = new Scanner(System.in);
int a = s.nextInt();
String str = s.next();
System.out.print(a);
System.out.println(str); 

Options
This problem has only one correct answer
10 abc def
10abc
10abcdef
10 abc

Ans 10abs 

Solution Description
"s.nextInt()" scans and returns the next token as int. A token is part of entered line that is separated from other tokens by space, tab or newline. So when input line is - “10 abc def” then s.nextInt() returns the first token as int i.e. “10” and s.next() returns the next token "abc”. 
While printing, in first statement a is printed and then str. There is no space or nextline between both print. Hence output is : 10abc.

Question 8: Integer and String
What is the output of the following code if input is : abc def 10
Scanner s = new Scanner(System.in);
String str = s.next();
int a = s.nextInt();
System.out.print(str + " " + a);
Options
This problem has only one correct answer
abc def 10
abc 10
InputMismatchException
abc InputMismatchException

Ans InputMismatchException 

Solution Description
"s.next()" scans and returns the next token as String. A token is part of entered line that is separated from other tokens by space, tab or newline. So when input line is - “abc def 10” then s.next() returns the first token as String i.e. “abc” and s.nextInt() tries to convert the next token i.e. “def” into an int, which gives InputMismatchException.  





























