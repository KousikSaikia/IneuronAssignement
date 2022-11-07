## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

it's simpler and more intuitive for a human to use. They are not written in machine-readable language, Python programs need to be processed before machines can run them.

Q2. Why is Python called a dynamically typed language?

It is beacuse there is no declaration of variable in Python.

Q3. List some pros and cons of Python programming language?

Pros -

Python is easy to learn and read
Python has a vast collection of libraries.

Cons-
Python has speed limitations.
Python can have runtime errors.

Q4. In what all domains can we use Python?

Python is used in  artificial intelligence, machine learning and deep learning.

Q5. What are variable and how can we declare them?

Variables are the basic unit of storage in a programming language. These variables consist of a data type, the variable name, and the value to be assigned to the variable.

Q6. How can we take an input from the user in Python?

Using input() function we can take input from user.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

string

Q8. What is type casting?

Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Yes we can take multiple inputs in pythin using the split function with input function.

Q10. What are keywords?

Special reserved words that have specific purpose and meanings.

Q11. Can we use keywords as a variable? Support your answer with reason.

We cannot use keywords as varibale as they are used to define the syntax and structure of the python language.

Q12. What is indentation? What's the use of indentaion in Python?

Spaces at the begining of the code is called indentation. In python it is used to incate a block of code.

Q13. How can we throw some output in Python?

using the print() function

Q14. What are operators in Python?

Special symbols in Python that carry out arithmetic or logical computation.

Q15. What is difference between / and // operators?

/ means divion with give the full value whereas // gives on the Quoteint.

Q16. Write a code that gives following as an output.
iNeuroniNeuroniNeuroniNeuron
```
print('iNeuron'*3)

```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
```
var1 = int(input('Enter a number : '))
if(var1%2==0):
    print('Its a Even number')
else:
    print('Its an Odd number')
```
Q18. What are boolean operator?

The logical operators and, or and not are also referred to as boolean operators.

Q19. What will the output of the following?
```
1 or 0
1
0 and 0
0
True and False and True
False
1 or 0 or 0
1
```

Q20. What are conditional statements in Python?

These statements guide the program while making decisions based on the conditions encountered by the program.

Q21. What is use of 'if', 'elif' and 'else' keywords?

They are used in conditional statements.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
```
age = int(input('Enter age : '))
if(age>=18):
    print('I can vote')
else:
    print('I can\'t vote')
```


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
total =0
for num in numbers:
    if(num%2==0):
        total+=num
    else:
        total+=0
print(total)
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

```
var1,var2,var3=input("Enter three numbers separated by ,: ").split(',')
print(max(int(var1),int(var2),int(var3)))
```

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```

numbers = [12, 75, 150, 180, 145, 525, 50]
for n in numbers:
    if n > 500:
        exit()
    elif n%5==0:
        print(n)
    else:
        continue
```
