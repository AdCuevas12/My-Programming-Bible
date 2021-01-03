# **INTRODUCTION TO PROGRAMMING**

## **History of C Language**

C was created at the Bell Telephone  Laboratories in 1972 by Dennis Ritchie. It was developed into such a  powerful and flexible language that its use quickly spread beyond Bell  Labs. The C language is so named because its predecessor was called B.  The B language was also developed at Bell Labs, by ken Thompson.

There are several reasons why many  computers professionals feel that C is on top of the heap among the  other high-level programming languages.

- **C is an efficient language** – It is a concise language that lets you say what you mean in fewer  words. The final code tends to the compact and to run quickly.
- **C has a lot desirable design features** – C programming language use sound programming techniques such as  top-down planning, structured programming and modular design. The result is a more reliable, understandable program.
- **C is a powerful and flexible language** – C programming language is used for projects as diverse as operating  systems, word processors, graphics and even compilers for other  languages.
- **C is a popular language** – It is by far the preferred language among professional programmers.  As a result, there are a wide variety of C compilers and helpful  accessories available.
- **C is oriented toward programmer needs** – C allows the programmer to have access to hardware. It lets you  manipulate individual bits in memory. It has a rich selection of  operators that let you express yourself. It has a large library of  useful functions that are generally available on most C implementations.
- **C is a portable language** – Portable means that a C program written for one computer system can  be complied and run on another system with little or no modification.

#### **What is programming?**

Programming is instructing a computer  to do something for you with the help of a programming language. The  role of a programming language can be described in two ways:

***Technical:\*** It is a means for instructing a Computer to perform Tasks

***Conceptual:\*** It is a framework within which we organize our ideas about things and processes.

According to the last statement, in programming we deal with two kind of things:

1.  data, representing ``objects'' we want to manipulate
2.  procedures, i.e. ``descriptions'' or ``rules'' that define how to manipulate data.

# Complete Definition

It is the process of writing, testing, and maintaining the source code of computer programs. The source code  is written in programming language. This code may be a modification of  existing source or something completely new, the purpose being to create a program that exhibits the desired behavior. The process of writing  source code requires expertise in many different subjects, including  knowledge of the application domain, specialized algorithm and formal  logic. 

**The Program Development Life Cycle (PDLC)**

   Creating new programs is called program development. The process associated with creating successful applications programs is called the program  development life cycle (PDLC).

1.  ***Problem Analysis\***

- Applications software development  normally begins with reviewing the program specifications indicating  what the new system should do—a process called problem analysis. During  this stage, the systems analyst and programmer review the specifications and possibly talk with users in order to fully understand what the  software should do.
- Documentation resulting from this  phase consists of the program specifications, timetable, which language  will be used, how the program will be tested, and what documentation is  required.

1.  ***Program Design\***

- During program design, the  specifications are used to express the algorithm needed to solve the  problem, usually in the form of any number of program design tools,  discussed shortly.
- Good program design is very important to make the development process go more smoothly, as well as to make  future revisions easier.
- Program Design Tools - Program design tools are planning tools. Many such tools have been developed, but two  of the most important are program flowcharts, and pseudo-code.

**2.1.1.** 

 ***Program flowcharts\*** use geometric symbols and familiar relational operators to provide a  graphic display of the sequence of steps involved in a program. The  steps in a flowchart follow each other in the same logical sequence as  their corresponding program statements will follow in a program.

**2.1.2.** ***Pseudo-code\*** uses English-like statements in place of the graphic symbols of the  flowchart. Unlike a flowchart, pseudo-code is easy to modify and can be  embedded into a program as comments. No standard set of rules exists for writing pseudo-code, although a number of conventions have been  developed.

**2.2.** ***Control Structure.\***

**2.2.1.** A ***sequence control structure\*** is simply a series of procedures that follow one another.

**2.2.2.** The ***selection (if-then-else) control structure\*** involves a choice: if a certain condition is true, then follow one  procedure; else, if false, follow another. When more than two possible  choices exist, the case control structure can be used instead.

**2.2.3.** A ***loop\*** is an operation that repeats until a certain condition is met. A  looping (iteration) control structure can take two forms. With the  do-while structure, the loop is executed as long as a condition is true; with the do-until structure, the loop continues until a certain  condition becomes true.

1.  ***Program Coding\***

- Coding is the actual process of creating the program in a programming language.
- One of the first steps in the coding  process is deciding which programming language to use. Languages for  specific applications are often chosen with respect to such criteria as  suitability, compatibility with other applications, organizational  standards, programmer availability, portability, and speed.

1.  ***Program Debugging and Testing\*** 

- Debugging is the process of making sure a program is free of errors, or “bugs.”
- Preliminary debugging begins after  the program has been entered into the computer system. Rarely is a  program error-free the first time it runs. Two common types of errors  are syntax errors and logic errors.

**4.1.** A ***syntax error\*** occurs when the programmer has not followed the rules of the language.

**4.2.** A ***logic error\***, or execution-time error, results when the command syntax is correct but the program is producing incorrect results.

1.  ***Program Maintenance\***

- Virtually every program, if it is to last a long time, requires ongoing maintenance.
- Program maintenance is the process of updating software so that it continues to be useful. It is a costly  process, but can be used to extend the life of a program.
- Documentation resulting from this  step consists of the amended program package reflecting what problems  occurred and what program changes were performed.

# **FUNDAMENTALS OF C- PROGRAM**

**The following are the terminologies used in C- program.** 

### **Identifiers**

​    \- one or more characters used  to identify or name data elements such as variables, constants, arrays,  records, and subprograms.

​    \- an identifier is a  combination of alphanumeric characters, the first being a letter of the  alphabet or an underscore, and the remaining being any letter of the  alphabet, any numeric digit, or the underscore.

### **Constant**

- a data item that remains unchanged throughout the execution of the program.
- a memory location whose constants stay the same during the execution of the program.

### **Variable**

- a named data item, the value of which may change during the execution of the program.
- a memory location whose contents can be filled and changed during the execution of the program.

**Data Type** – a definition or interpretation of a set of data specifying the  possible range of values of the set, the operation that can be performed on the rules and the way in which values are stored in the memory.

# **Expressions**

​      It is a combination of values, variables, operators and  functions that are interpreted according to the particular rules of  precedence and of association for a particular programming language,  which computes and then produces  another value.

#  Kind of Expressions

1.  ***Arithmetic\*** – an expression that contains arithmetic operators and operands which can be reduced to a single numeric value.
2.  ***Relational\*** – an expression constructed by connecting constants, variables and/or other expressions by a relational operator.
3.  ***Logical\*** –  an expression constructed by combining individual conditional variables  or expressions into a more complex statements by combining them with a  logical operator.

 

## Arithmetic operator

- a symbol used to represent a mathematical operation.

| Operator |   Operation    |                            Action                            |     Example     |
| :------: | :------------: | :----------------------------------------------------------: | :-------------: |
|    ++    |   Increment    |                   Increment operands by 1                    |       i++       |
|    --    |   Decrement    |                    Decrement operand by 1                    |       i--       |
|    +     |    Addition    |                     Adds its 2 operands                      |       a+b       |
|    -     |  Subtraction   |        Subtracts the 2nd operand from the 1st operand        | Gross-deduction |
|    *     | Multiplication |                  Multiplies its 2 operands                   |  Grade * units  |
|    /     |    Division    |          Divides the 1st operand by the 2nd operand          |   Total / 100   |
|    %     |    Modulus     | Gives the remainder when the 1st operand is divided is divided the 2nd operand |  Minutes % 60   |

### **Order of Precedence**

| Operators | Precedence |
| :-------: | :--------: |
|  ++, --   |     1      |
|  *, /, %  |     2      |
|   +, -    |     3      |

## Relational operator

- a symbol used to compare operands and yields either true or false.

| Operator |       Operation       |     Example      |
| :------: | :-------------------: | :--------------: |
|    ==    |         Equal         |      x ==y       |
|    >     |     Greater than      |      x > y       |
|    <     |       Less than       |      x < y       |
|    >=    | Greater than or Equal | Income >= 25000  |
|    <=    |  Less than or equal   |  Grade <= 1.75   |
|    !=    |       Not Equal       | Allowance != 100 |

## Logical operator

- a symbol that defines the logical connection between two or more conditions.

| Operator |                      Meaning                       |
| :------: | :------------------------------------------------: |
|    !     | ***not*** (reverse the truth value of a condition) |
|    %%    |      ***and*** (both conditions must be true)      |
|   \|\|   |   ***or*** (at least one condition must be true)   |

# Control String

- Contains characters to be displayed or format codes that tell how to display the rest of the argument.

| Format Code |           Meaning            |
| :---------: | :--------------------------: |
|  %d or %I   |      Display an integer      |
|     %ld     |    Display a long integer    |
|     %f      |       Display a float        |
|     %lf     |       Display a double       |
|     %c      |     Display a character      |
|     %s      |       Display a string       |
|     %o      |   Display an octal number    |
|     %x      | Display a hexadecimal number |

### Backslash Characters

| Code |      Meaning       |
| :--: | :----------------: |
|  \n  |      newline       |
|  \t  |   Horizontal tab   |
|  \a  | Alert (ring sound) |
|  \\  |     Backslash      |

# Conditional Statement

 **Conditional Statements**

​     Conditional Statements checks an expression then may or may not execute a statement a group of statements depending on the result of the Boolean expression.

​    Boolean Expression is expression, which are answerable by  TRUE or FALSE. A Boolean Expressions must have a relational operator to  evaluate these things.

## **if Statement**

​	The if statement is the simplest of C’s selection structure. It uses a conditional expression to determine whether a given statement should be executed. If condition evaluates to TRUE, the statement or block that  forms the target of the will be executed; otherwise, if it exist. The  statement or block that forms the target of the else will be executed.  Only the code associated with the if or the code associated with the  else will be executed, never both.

C’s IF statement has the following constructs: 

SYNTAX:

```c
if (<condition>)
    <statement/s A>; 
else:{
    <statement/s B>;
}
```

EXAMPLE:

```c
if (x == 0)
  Printf(“The value is not negative”;
else if (x = = 1){
  sum = sum + x;
  next = next + 1;
}
else if (x  >=10){
  printf(“Enter another value”);
  scanf(“%d”, &y);
}
```

## if  else – if construct or nested if

SYNTAX:

```c
if(<condition>)
    <statement/s A>
else if (<condition >)
    <statement/s B>;
else:{
    <statement/s C>;
}
```

where:

***condition\*** – logical expression that determines whether the action is to be executed.

***statements A\*** – action/actions to be performed if the logical expression is TRUE.

**statement B** – action/actions to be performed if the logical expression is FALSE.

EXAMPLE:

``` c
int Num1, Num2, Num3;

printf("Input your first integer: ");
scanf("%d", &Num1);
printf("Input your Second integer: ");
scanf("%d", &Num2);
printf("Input your Third integer: ");
scanf("%d", &Num3);

if ((Num1 > Num2) && (Num1 > Num3)){
    printf("%d\n", Num1);
}
else if ((Num1 < Num2) && (Num2 > Num3)){
    printf("%d\n", Num2);
}
else if ((Num1 < Num3) && (Num2 < Num3)){
    printf("%d\n", Num3);
}
```

## **switch Statement**

​    The switch statement is a built – in multiple – branch  decision statement where variable is successively tested against a list  of integer or character constants. When a match is found, the statement  or statement associated with the constant is executed.

SYNTAX:

```c
switch(<expression>) 
```

EXAMPLE:

```c
int month;
printf("***** Calendar******\n\n\n");
printf("Input an Integer from 1-12: ");
scanf("%d", &month);
switch(month){
    case 1:
        printf("%s\n", "January");
        break;
    case 2:
        printf("%s\n", "February");
        break;
    case 3:
        printf("%s\n", "March");
        break;
    case 4:
        printf("%s\n", "April");
        break;
    case 5:
        printf("%s\n", "May");
        break;
    case 6:
        printf("%s\n", "June");
        break;
    case 7:printf("%s\n", "July");
        break;
    case 8:printf("%s\n", "August");
        break;
    case 9:
        printf("%s\n", "September");
        break;
    case 10:
        printf("%s\n", "October");
        break;
    case 11:
        printf("%s\n", "November");
        break;
    case 12:
        printf("%s\n", "December");
        break;
default :
        printf("%s\n", "Invalid Format");
}
```

# Looping Statement

 In order to repeat a statement multiple times, a control structure  known as loops are to be used. Loop allows a set of instructions to  repeat until a certain condition is reached. C supports the same type of loop as other modern structured languages.

 A ***for-loop*** executes a set statement s a fixed number of  times. It is used typically when you known in advanced how many times  you want to execute these statements.

​    C looping statements are written in the following format:

## for-loop

SYNTAX:

```c
for (initialization; condition; incrementation){
    <statements/s>;
}
```

where:

***Initialization\*** – an assignment statement that is used to set the loop control variable.

***Condition\*** – a relational expression that determines when the loop will exist by testing the loop-control variable against some values.

***Incrementation\*** – defines how the loop-control variable will change each time the loop is repeated.

EXAMPLE:

```c
//Create a program that will display integers 1 to 10 on the screen using for loops.
    
for (int i =1; i<=10; i++)
	printf("%d \n",ctr);
```



​    In an event-controlled loop, the number of times that the loop  is executed is not predetermined. Instead, termination of the loop is  triggered by the occurrence of some event. The ***while loop and do/while loop*** does this kind of operation.

## while-loop

SYNTAX:

```c
while (<condition>){
    <statement/s>;
}
```

where:

***statement\*** – can be an empty statement, a single statement or a block of statement that is to be repeated.       

***conditions\*** – may be any valid expression.  The loop iterates while the condition is true and program control passes to the next line following the loop if the condition is  false.                      

EXAMPLE:

 ```c
// Make a program that will display integers 25, 21, 17, 13, 9 using while loops.

while (ctr>=9){
    printf("%d \n",ctr);
    ctr -= 4;
}
 ```



Another way of creating a loop that is not counter controlled is to  use the do-while loop. It is convenient when at least one repetition of  loop body must be ensured.

## do/while-loop

SYNTAX:

```c
do{
    <statement/s>; 
} while (<condition>); 
```



EXAMPLE:

```c
// Design a C code that will display all numbers divisible by 11 from 1 to 100 using do-while loops.

int ctr=100;
do{
    if (ctr % 11 == 0)
        printf("%d \n",ctr);
    ctr -= 1;
}while(ctr>=1);
```



Unlike the for and while loop, the do/while lop checks the condition at  the bottom of the loop. This means that a do/while loop while always  execute at least once. Its common use is in a menu selection routine by  testing a valid response at the bottom of the loop, where can be  re-prompt the user until a valid response is entered.

## **Nested loop**

​    When one loop is inside of another, the loop is said to be  nested. It provides a means of solving some interesting programming  problems. It is sometimes important to note how much iteration a nested  loop executes. This number is determined by multiplying the number of  times the outer loop iterates by the number of times the inner loop  repeats each time it is executed.

EXAMPLE:

```c
//Display the following using nested loops:
// *
// *  *
// *  *  *
// *  *  *  *
// *  *  *  *  *

for (a = 1; a <= 5; a++){
    for (b = 1; b <=a; b++)
        printf(“ * ”);
    printf(“\n”);
}
```

# Array

It is a special type of variable, which can hold one or more values  of the same data type with reference to only one variable name. It is a  series or list of variables in computer memory, all of which have the  same name but the differentiated with special numbers called subscript,  index, or element.

SYNTAX:

```c
<dataType> arrayName[number of elements];
```

Note: In C language, elements starts with 0.

**SINGLE DIMENSIONAL ARRAY or ONE DIMENSIONAL ARRAY** –

an array that represents a single list of values.

EXAMPLES:

```c
int score[7];

score[1] = 5;
score[2] = 3;
score[3] = 4;
score[4] = 0;
score[5] = 6;
score[6] = 9;

score[1] + score[2] = 8
score[3]*score[5] = 24
score[3+2] = 6
score[3*2] = 9
score[1] < score [2] = False

```



```c
// Create a C program that will input 10 integers and display these integers form the last entered to the first entered integer using an array.

int a[10];
int ctr;

for(ctr=0;ctr<=9;ctr++){
    printf("Enter Number %d: ",ctr+1);
    scanf("%d",&a[ctr]);
}
for(ctr=9;ctr>=0;ctr--)
    printf("%d \n",a[ctr]);
```



## **TWO DIMENSIONAL ARRAY** 

- an array that represent values in a table or grid that contains rows and columns instead of a single list. 

SYNTAX:

```c
<dataType> arrayName[no. of rows][no. of cols];
```

EXAMPLE: 

```c
// Build a program that will input 5 integers and display them in ascending order.

int a[5];
int ctr1,ctr2,temp;

for(ctr1=0;ctr1<=4;ctr1++){
    printf("Enter Number %d: ",ctr1+1);
    scanf("%d",&a[ctr1]);
}
for(ctr1=0; ctr1<=3; ctr1++)
   for(ctr2=ctr1+1; ctr2<=4; ctr2++){
      if (a[ctr1]>a[ctr2])
      {
      temp=a[ctr1];
      a[ctr1]=a[ctr2];
      a[ctr2]=temp;
      }
   }
for(ctr1=0; ctr1<=4; ctr1++)
    printf("%d\n",a[ctr1]);
```

```c
// Using 15x15 array, create a multiplication table.

int mt[15][15];
int row, col;
    printf("\n\n\t\t\t\t\t MULTIPICATION TABLE\n\n\n");
    for (row=0; row<15; row++)
        for(col=0; col<15; col++)
            mt[row][col]=(row+1)*(col+1);
    for (row=0; row<15; row++){
        for(col=0; col<15; col++){    
            p(" %4d |",mt[row][col]);
        }
        p("\n");
    }
```



