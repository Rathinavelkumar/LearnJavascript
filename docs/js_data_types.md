Data types specify the different sizes and values that can be stored in the variable. Javascript have various data types that we can use in our javascript programs.

## **Built-In Data Types**

    Numeric Types           # Number, BigInt
    Text Type               # String
    Empty Type              # undefined, null
    Mapping Type            # Object
    Symbol Types            # Symbol
    Boolean Type            # Boolean

** `Note` - you can use any online javascript interpreter to run and test the below js program examples

## **Number Type**
Integers and floating number can be represented using number datatype in javascript. Below is the sample example program.

    // Number Data Types
    let num1 = 100;
    console.log(typeof(num1), num1);

    let num2 = 3.14;
    console.log(typeof(num2), num2)

    let num3 = 10*20
    console.log(typeof(num3), num3)

 Output

    number 100
    number 3.14
    number 200

## **BigInt Type**
Number data types allows the numbers only between the range of -9007199254740991 to +9007199254740992. BigInt helps to store the values more than 9007199254740991 by simply appending n to the end of that integer

    // BigInt Data Type
    let num1 = 9007199254740993n;
    console.log(typeof(num1), num1);

 Output

    bigint 9007199254740993

## **String Type**
Text can be store with the help of string data type. single quotes, double quotes or backticks are used to represent string in Javascript

    // String Data Type
    //single quote
    let name1 = 'Python'
    console.log(typeof(name1), name1)

    //double quote
    let name2 = "Javascript"
    console.log(typeof(name2), name2)

    //backticks - to include expressions
    let output = `Learn ${name1} and ${name2}`
    console.log(output)

 Output

    string Python
    string Javascript
    Learn Python and Javascript

## **Boolean Type**
Boolean data types are used to store true or false in the variable for logical operations

    //Boolean data type
    is_validated = true
    console.log(typeof(is_validated), is_validated)

    is_checked = false
    console.log(typeof(is_checked), is_checked)

 Output

    boolean true
    boolean false

## **Undefined Type**
Unassigned values are considers as undefined data type in javascript

    //Undefined data type
    let amount;
    console.log(typeof(amount), amount)

 Output

    undefined undefined

## **Null Type**
Empty values are considers as null Object in javascript

    //Null data type
    let amount=null;
    console.log(typeof(amount), amount)

 Output

    object null

## **Symbol Type**
To achieve immutability, symbol has been introduced from ES6.

    //Symbol data type
    let name1=Symbol("Js");
    let name2=Symbol("Js")

    //Even though both have same value, its considered as different objects
    console.log(name1===name2)
    console.log(typeof(name1))

 Output

    false
    symbol

## **Object Type**
Object type is one of major data type which is like dictionary in python. With the help of key and value pair combination, data can be store and retrieve in javascript

    //Object data type
    let data = {
        name : "Javascript",
        version : "ES6",
        year : "2016"
    }

    //Access elements using dot walk
    console.log(data.name)

    //Access elements using key with square brackets
    console.log(data["year"])

 Output

    Javascript
    2016