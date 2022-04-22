Javascript provides lot of inbuilt methods which helps to perform various operations on numbers

## **toString method**
This method helps to convert any number to string data type like the below example program

    //toString Method
    num1 = 100;
    console.log(typeof(num1), num1)
    result = num1.toString()
    console.log(typeof(result), result);

 Output

    number 100
    string 100

## **toExponential method**
This method helps to round a number based on the number given in parameter and returns as a string in output with exponential notation

    //toExponential Method
    let x = 5.125;

    result1 = x.toExponential(2);
    console.log(result1)

    result2 = x.toExponential(4);
    console.log(result2)

    result3 = x.toExponential(6);
    console.log(result3)

 Output

    5.13e+0
    5.1250e+0
    5.125000e+0

## **toFixed method**
This method helps to round a number with specified number of decimal and returns as a string in output

    //toFixed Method
    let x = 5.125;

    result1 = x.toFixed(2);
    console.log(result1)

    result2 = x.toFixed(4);
    console.log(result2)

    result3 = x.toFixed(6);
    console.log(result3)

 Output

    5.13
    5.1250
    5.125000

## **toPrecision method**
This method helps to round a number with specified length and returns as a string in output

    //toPrecision Method
    let x = 5.125;

    result1 = x.toPrecision(2);
    console.log(result1)

    result2 = x.toPrecision(4);
    console.log(result2)

    result3 = x.toPrecision(6);
    console.log(result3)

 Output

    5.1
    5.125
    5.12500

## **valueOf method**
Two methods are used to create number in javascript which are primitive or object method. The valueof method helps to convert number objects to primitive numbers

   //valueOf method
   let num1=123
   console.log(num1)

   let num2=new String("123")
   console.log(num2)
   console.log(num2.valueOf())

 Output

   123
   [String: '123']
   123