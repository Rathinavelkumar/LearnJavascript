Number is the primitive data type in javascript. It can take both non-decimal and decimal numbers

## **Numbers declaration**
Unlike in other programming language, javascript always use 64 bit floating point to save the number in memory

    //Number without decimal
    num1 = 10
    console.log(num1)

    //Number with decimal
    num2 = 2.5
    console.log(num2)

    //Number with scientific notation
    num3 = 25e10
    console.log(num3)

    num4 = 25e-5
    console.log(num4)

 Output

    10
    2.5
    250000000000
    0.00025

## **Numbers precision**
Javascript maintain precision up to 15 digits, after that it gives non-accurate results. Also floating result are not 100% accurate, since they are stored as a binary internally

    //Integer precision - Up to 15 digit
    num1 = 999999999999999
    console.log(num1)

    //More than 15 digit makes not accurate result
    num2 = 9999999999999999
    console.log(num2)

    //Floating point precision - not accurate usually
    num3 = 0.1 + 0.2
    console.log(num3)

    //To solve floating accuracy issue
    num4 = 0.1 + 0.2
    console.log(num4.toFixed(2))

 Output

    999999999999999
    10000000000000000
    0.30000000000000004
    0.30

## **Adding number and string**
Plus operator is used for addition of numbers. If both are numbers, it will sum the value else it will concat the values in case of string

    //Adding two numbers
    result1 = 10 + 20
    console.log(result1)

    //Adding number and string
    result2 = 10 + "20"
    console.log(result2)

    //Adding string and number
    result3 = "10" + 20
    console.log(result3)

    //Adding two strings
    result4 = "10" + "20"
    console.log(result4)

 Output

    30
    1020
    1020
    1020

## **NaN and Infinity**
NaN (Not A Number) - illegal arithmetic operation with not a number values result in NaN result in javascript. Similarly, when calculation exceeds the limit, it will result in infinity result

    //NaN example
    result1 = 10 - "Rathnaschoools"
    console.log(typeof(result1), result1)

    //Infinity example
    result2 = 10 / 0
    console.log(typeof(result2), result2)

 Output

    number NaN
    number Infinity