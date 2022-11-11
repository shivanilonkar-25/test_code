## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
ANS:
Python is a versatile language that can be used for building a range of applications including web services, websites, and enterprise applications.
And high-level means it's easy for humans to understand.

Q2. Why is Python called a dynamically typed language?
ANS:
 Python don't have any problem even if we don't declare the type of variable. It states the kind of variable in the runtime of the program. So, Python is a dynamically typed language.

Q3. List some pros and cons of Python programming language?
ANS:
Pros:
Python is easy to learn and read
Python enhances productivity
Python has a vast collection of libraries
Python is free, open-source, and has a vibrant community
Python is a portable programming language
Python is an interpreted language
Cons:
Python has speed limitations(Slower than compiled languages)
Python is not so strong with mobile computing
Python can have runtime errors
Python consumes a lot of memory space
Python is not easy to test

Q4. In what all domains can we use Python?
ANS:
1. Web and softwarevdevelopment
2. Data science
3. OS development
4. Scientific programming
5. Gaming

Q5. What are variable and how can we declare them?
ANS:
Variable is nothing but name given to memory location
How to declare Variable: Just give a name to value assign the value to that name and datatype of that variable will be considered based on their datatype
Example:
 x= 10 # integer variable
 str="Hello World" # string variable

Q6. How can we take an input from the user in Python?
ANS:
We can take input from user using the in-build function input()
Below is example taking the input from user
name=input("Enter your name:")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
ANS:
Default datatype is String

Q8. What is type casting?
ANS:
Type Casting is the method to convert the variable data type into a certain data type

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
ANS:
No

Q10. What are keywords?
ANS:
Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes. These keywords are always available—you'll never have to import them into your code.

Q11. Can we use keywords as a variable? Support your answer with reason.
ANS:
We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language.
If we use them as variable then it will throw the error

Q12. What is indentation? What's the use of indentaion in Python?
ANS:
Indentation refers to the spaces at the beginning of a code line.
Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
ANS:
We can throw the some output in python using print function
Example:
Print("Welcome")

Q14. What are operators in Python?
ANS:
Operators are used to perform operations on variables and values.
Below are the diffrent types of Operators
Arithmetic operators
Assignment operators
Comparison operators
Logical operators

Q15. What is difference between / and // operators?
ANS:
/ is used for float division
// used for integer division

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
ANS:
str1="iNeuron"
str2=str1*4
print(str2)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
ANS:
num=input("Enter the Number:")
print("Your enter number is :",num)
num=int(num)
if num % 2 == 0:
    print("Enter number:",num,"is Even")
else:
    print("Enter number:",num,"is odd")

Q18. What are boolean operator?
ANS:
Boolean Operators are those that result in the Boolean values of True and False. These include and, or and not.

Q19. What will the output of the following?
```
1 or 0 ANS:-->1

0 and 0 ANS:--> 0

True and False and True ANS:--> False

1 or 0 or 0 ANS:--> 1
```

Q20. What are conditional statements in Python?
ANS:
Conditional statements are also known as decision-making statements. We need to use these conditional statements to execute the specific block of code if the given condition is true or false.

Q21. What is use of 'if', 'elif' and 'else' keywords?
ANS:
if: It checks for a given condition, if the condition is true, then the set of code present inside the if  block will be executed otherwise not.
elif: Multiple conditions can be checked by including one or more elif checks after your initial if statement. Just keep in mind that only one condition
else:else is response that will execute if the condition is false


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
ANS:
age=input("Enter your age:")
print("You enter age is :",age)
if int(age) >= 18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ANS:
numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for i in numbers:
    if i%2 == 0 :
        sum=sum+i
print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ANS:
a=int(input("Enter the first Number:"))
b=int(input("Enter the second Number:"))
c=int(input("Enter the third Number:"))

if a>b and a>c :
    print("Greatest Number is :", a)
elif b>a and b>c:
    print("Greatest Number is :", b)
elif c>a and c>b:
    print("Greatest Number is :", c)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ANS:
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i>500:
        break
    if i>150:
        pass
    elif i%5 == 0 :
        print(i)