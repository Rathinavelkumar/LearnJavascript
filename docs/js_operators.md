Operators are used to perform various mathematical operations on the data value. Operators are used to perform various mathematical operations on the data value

## **Types of Operators**

    1. Arithmetic operators 

    2. Comparison operators

    3. Logical operators

    4. Bitwise operators

    5. Assignment operators 
    

## **Arithmetic operators**
Arithmetic operators are used to perform simple arithmetic operations over the operands

    //Addition Operation
    let add_result = 10 + 20
    console.log(`Addition Result : ${add_result}`)

    //Subtraction Operation
    sub_result = 100 - 50
    console.log(`Subtraction Result : ${sub_result}`)

    //Multiplication Operation
    multi_result = 10 * 20
    console.log(`Multiplication Result : ${multi_result}`)

    //Division Operation (Decimal Value)
    div_result = 25 / 10
    console.log(`Division Result : ${div_result}`)

    //Modulus Operation
    mod_result = 25%10
    console.log(`Modulus Result : ${mod_result}`)

    //Exponential Operation (2*2*2*2*2)
    exp_result = 2 ** 5
    console.log(`Exponential Result : ${exp_result}`)

    //Increment Operation
    inc_result = 10
    inc_result++
    console.log(`Increment Result : ${inc_result}`)

    //Decrement Operation
    dec_result = 10
    dec_result--
    console.log(`Decrement Result : ${dec_result}`)

 Output

    Addition Result : 30
    Subtraction Result : 50
    Multiplication Result : 200
    Division Result : 2.5
    Modulus Result : 5
    Exponential Result : 32
    Increment Result : 11
    Decrement Result : 9

## **Comparison operators**
Comparison operators are used to check for relations between the operands

    //Equal Operator (Type Ignored)
    num1=50, num2 = "50"
    if (num1==num2) {
        console.log("Equal")
    }

    //Identical Operator (Should be same type )
    num1=50, num2 = 50
    if (num1===num2) {
        console.log("Equal")
    }

    //Not Equal Operator
    num1=50, num2 = "100"
    if (num1!=num2) {
        console.log("Not Equal")
    }

    //Not Identical Operator
    num1=50, num2 = 100
    if (num1!==num2) {
        console.log("Not Equal")
    }

    //Greater than Operator
    num1=100, num2 = 50
    if (num1>num2) {
        console.log("num1 is greater than num2")
    }

    //Lesser than Operator
    num1=50, num2 = 100
    if (num1<num2) {
        console.log("num1 is lesser than num2")
    }

    //Greater than or Equal to Operator
    num1=50, num2 = 50
    if (num1>=num2) {
        console.log("Greater than or Equal to")
    }

    //Lesser than or Equal to Operator
    num1=50, num2 = 50
    if (num1<=num2) {
        console.log("Lesser than or Equal to")
    }

 Output

    Equal
    Equal
    Not Equal
    Not Equal
    num1 is greater than num2
    num1 is lesser than num2
    Greater than or Equal to
    Lesser than or Equal to

## **Logical operators**
Logical Operators are used to check conditional expression. We can use these operators in conditional and looping statement for evaluation

    //AND - Returns True If both conditions are True
    num = 50
    if (num>10 && num<100) {
    console.log(true) 
    }

    //OR - Returns True If any one of the conditions is True
    num = 50
    if (num>10 || num<30) {
        console.log(true)
    }

    //NOT - Returns opposite of the result
    num = 50
    if (!(num>100)) {
        console.log(true)
    }

 Output

    true
    true
    true

## **Bitwise operators**
Bitwise operators are used to perform operations bit by bit

**Bitwise AND operator**

    num1 = 3
    num2 = 5

    //BITWISE AND Operator returns 1 if both the bits are 1
    console.log( num1&num2 )

 Output

    1

The result is 1, because 3 is equal to 0011 in binary and 5 is equal to 0101 in binary

Now compare each bit between 3 and 5, only last bit are 1 for both, so that alone returns 1 in final result. Hence, 0001 decimal value is 1, that is get printed in final output

    0011 = 3
    0101 = 5
    ----------
    0001 = 1

**Bitwise OR operator**

    num1 = 3
    num2 = 5

    //BITWISE OR Operator returns 1 if anyone of two bits are 1
    console.log( num1 | num2 )

 Output

    7

The result is 7, because 3 is equal to 0011 in binary and 5 is equal to 0101 in binary

Now compare each bit between 3 and 5, the last three having latest one of two bits is 1, so that three bits returns 1. Hence, 0111 decimal value is 7, that is get printed in final output

    0011 = 3
    0101 = 5
    ----------
    0111 = 7

**Bitwise XOR operator**

    num1 = 3
    num2 = 5

    //BITWISE XOR Operator returns 1 if both bit are not equal
    console.log( num1 ^ num2 )

 Output

    6

The result is 6, because 3 is equal to 0011 in binary and 5 is equal to 0101 in binary 

Now compare each bit between 3 and 5, only 2nd and 3rd third sets having one of the bit is 1 and other is 0, so that two bits returns 1. Hence, 0111 decimal value is 6, that is get printed in final output

    0011 = 3
    0101 = 5
    ----------
    0110 = 6


**Bitwise NOT operator**

    num = 3

    //BITWISE NOT Operator returns 1's compliment of the number
    console.log( ~num )

 Output

    -4

The result is -4, because 3 is equal to 0011 in binary First it add last bit 1+1 = 10 in binary (0 is result and 1 is carry)

Second it add second bit 1 with carry 1 which means 1+1 = 10 in binary (0 is result and 1 is carry) 

Third it add third bit 0 with carry 1 which means 1+0=0 in binary (no carry) Fourth it only have one bit 0 and no carry, so result in 0

Since its a 1's compliment we should have - value for the output decimal, so it gives -0100 as -4 in decimal output.

    0011 = 3
    -      1
    --------------
    - 0100 = -4


**Left shift operator**

    num = 3

    //LEFT SHIFT - Shifting Bit to Leftmost
    console.log( num<<2 )

 Output

    12

The result is 12, since the bits are pushing from left to right (2 places movement since we gave <<2 )

    0011 = 3
    <<2
    ------------
    1100 = 12

**Right shift operator**

    num = 8

    //RIGHT SHIFT - Shifting Bit to Rightmost
    console.log( num>>3 )

 Output

    1

The result is 1, since the bits are pushing from right to left (3 places movement since we gave <<3)

    1000 = 8
    >>3
    -------------
    0001 = 1

## **Assignment operators**
Arithmetic operators are used to perform assignment operations over the operands

    //Assign Operation (=)
    let assign_result = 10 + 20
    console.log(`Assigned Result : ${assign_result}`)

    //Add and assign (+=)
    let add_assign = 10
    add_assign+=20
    console.log(`Add assign Result : ${add_assign}`)

    //Subtract and assign (-=)
    let sub_assign = 20
    sub_assign-=10
    console.log(`Sub assign Result : ${sub_assign}`)

    //Multiply and assign (*=)
    let mul_assign = 20
    mul_assign*=10
    console.log(`Mul assign Result : ${mul_assign}`)

    //Divide and assign(/=)
    let div_assign = 20
    div_assign/=10
    console.log(`Div assign Result : ${div_assign}`)

    //Modulus and assign(%=)
    let mod_assign = 22
    mod_assign%=10
    console.log(`Mod assign Result : ${mod_assign}`)

 Output

    Assigned Result : 30
    Add assign Result : 30
    Sub assign Result : 10
    Mul assign Result : 200
    Div assign Result : 2
    Mod assign Result : 2