Variables are used to store value and call them wherever required in our code

Example:

    let roll_number = 12345

    # roll_number is a variable
    # = is an assignment operator
    # 12345 is the value stored in roll_number variable

## **Important point on Js variables**

* **`Var, let, Const and None`** 4 ways are available to declare variables in javascript
* **`When to use var`** Var keywords are used from 1995 to 2015. After that let and const keywords are introduced to eliminate some bugs in var. But, still old browser only recognize var keyword during code execution
* **`When to use let and const`** Const usually used to declare the constant value which cannot change once declared. Let is used to declare dynamic variables in the program

## **Rules for Variable Creation**

* **`Lowercase or uppercase or digits or underscore or dollar signs`** A Variable name can only contain lowercase (a to z) or uppercase (A to Z) or digits (0 to 9) or an underscore (_) or dollar signs($)
* **`Letter First`** A variable name must start with a letter. $ and _ also allowed but its not a good practice
* **`Case-Sensitive`** Variable name is case-sensitive (a = 5, A=6 -> a and A are two different variables in Javascript)
* **`No Special Characters or keywords`** The variable name cannot have reserved keywords and special characters such as !, @, #, % etc..

## **Multiple Assignment**
We can assign values to multiple variables in a single line like this  let a = 10, b = 20, c=30;

    //Multiple Assignment with multiple value
    let a = 10, b = 20, c = 30;
    console.log(a, b, c)

 Output

    10 20 30