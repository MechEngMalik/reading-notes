# **Expressions and operators**

## **operators**

**javaScript has the following types of operators. This section describes the operators and contains information about operator precedence.**

* ### **Assignment operators**

**An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.**

![operaters](https://static.packt-cdn.com/products/9781789805864/graphics/image/Chapter_2_Table_17.jpg)
_______________________________________________________

* ###  **Comparison operators**

**A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values.**

![como](https://www.lifewire.com/thmb/AoGXXTZUbptWcxW2YqqDdLb9Un8=/1201x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/excel-google-spreadsheets-comparison-operators-583c9dae5f9b58d5b189efb0.jpg)

__________________________________________________________________


* ### **Logical operators**

**Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the && and || operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. The logical operators are described in the following table.**
![log](https://www.devopsschool.com/blog/wp-content/uploads/2020/07/JavaScript-Logical-Operator.png)

## **Expressions**

**_An expression is any valid unit of code that resolves to a value._**

**Every syntactically valid expression resolves to some value but conceptually, there are two types of expressions: with side effects (for example: those that assign value to a variable) and those that in some sense evaluate and therefore resolve to a value.**

**The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to seven.**

***The code 3 + 4 is an example of the second expression type. This expression uses the + operator to add three and four together without assigning the result, seven, to a variable**.

**JavaScript has the following expression categories:**

* **Arithmetic: evaluates to a number, for example 3.14159. (Generally uses arithmetic operators.)**

* **String: evaluates to a character string, for example, "Fred" or "234". (Generally uses string operators.)**
* **Logical: evaluates to true or false. (Often involves logical operators.)**
* **Primary expressions: Basic keywords and general expressions in JavaScript.**
* **Left-hand-side expressions: Left values are the destination of an assignment.**

__________________________________________________________________

## **_Loops and iteration_**

**Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another.**
The statements for loops provided in JavaScript are:

* **for statement**
* **do...while statement**
* **while statement**
* **labeled statement**
* **break statement**
* **continue statement**
* **for...in statement**
* **for...of statement**

___________________________________________________________________

## **for statement**

![if](https://media.geeksforgeeks.org/wp-content/uploads/20191118171408/If-statement-GeeksforGeeks1.jpg)
**A for loop repeats until a specified condition evaluates to false.**

**A for statement looks as follows:**

_for ([initialExpression]; [conditionExpression]; [incrementExpression]_)
 **statement**_

**_When a for loop executes, the following occurs:_**

* **_The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables._**

* **_The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)_**

* **_The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements._**

* **_If present, the update expression incrementExpression is executed.
Control returns to Step 2._**

![if loop](https://cis.bentley.edu/sandbox/wp-content/uploads/2014/02/ifthenelse_011.png)

## **while statement**

![im while](https://beginnersbook.com/wp-content/uploads/2015/03/do-while_java.jpg)
**_A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:_**

## _while (condition)_

  **_statement_**

* **_If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop._**

* **_The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while._**

* **_To execute multiple statements, use a block statement ({ ... }) to group those statements._**

![while](https://eecs.oregonstate.edu/ecampus-video/CS161/template/chapter_5/chapter5_images/5_24.png)
