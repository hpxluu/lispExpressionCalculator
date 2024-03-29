# lispExpressionCalculator

A LISP expression 4 function calculator implemented with Java by Huy. This project utilizes the application of stack data structures to solve basic and nested arithmetic operations.
Programmed during the Summer of 2022.

# Required procedures
Make sure the version is JDK 8 
- (https://adoptium.net/temurin/releases/?version=8) 
during installation, enable **JAVA_HOME variable** and then click on the X drop down and select **Entire feature will be installed on local hard drive**.  
This will save the hassle to manually set the PATH from the environmental variables 

# Compiling the program
Navigate to the directory where the program folder is located then compile 

Mac/Linux: 
```
javac Main.java
javac lispEvaluation.java
javac lispEvaluation2.java
```
Windows: 
```
javac *.java
```

# Running the program
In the specific directory where the program folder is located then run these commands

Mac/Linux/Windows: 
```
Main java
```

# Behaviors 
- Addition operator(+) 
  - (+ a b c d ...) returns $a+b+c+d+ ...$ 
  - (+) returns 0
- Substraction operator(-) 
  - (- a b c d ...) returns $a-b-c-d - ...$
  - (-a) returns $-a$ (*must use at least one operand*) 
- Multiplication  operator(*) 
  - (* a b c d ...) returns $a * b * c * d * ...$ 
  - (*) returns 1 
- Division operator(/) 
  - (/ a b c d ...) returns $a/b/c/d - ...$
  - (/a) returns $1/a$ (*must use at least one operand*) 
  
  LISP expressions are valid when they are balanced (equal numbers of open and closed parenthesis) and proper operators usage on the operands.
  The program will throw a RunTimeException when the user LISP expression does not adhere to the behaviors listed above. 
