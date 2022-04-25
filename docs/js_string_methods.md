Below are the must known javascript string methods

## **Length method**
Length method helps to get the length of the given string

    //Length Method
    input_name = "RATHNASCHOOLS"
    console.log(input_name.length)

 Output

    13

## **Replace method**
Replace method helps to replace the given specified value with another given value as parameter

    //Replace Method
    input_name = "RATHNA SCHOOLS - LEARN PYTHON"
    console.log(input_name)
    new_name = input_name.replace("PYTHON", "JAVASCRIPT")
    console.log(new_name)

 Output

    RATHNA SCHOOLS - LEARN PYTHON
    RATHNA SCHOOLS - LEARN JAVASCRIPT

## **toUpperCase method**
Uppercase method helps to return all the characters in the given string with uppercase letter

    //toUpperCase Method
    input_name = "Rathna Schools"
    console.log(input_name.toUpperCase())

 Output

    RATHNA SCHOOLS

## **toLowerCase method**
toUpperCase method helps to return all the characters in the given string with lowercase letter

    //toLowerCase Method
    input_name = "Rathna Schools"
    console.log(input_name.toLowerCase())

 Output

    rathna schools

## **concat method**
concat method helps to concat the two or more than two string and return the single string value

    //concat Method
    let name1 = "RATHNA "
    let name2 = "SCHOOLS"
    let result = name1 + name2
    console.log(result)

 Output

    RATHNA SCHOOLS

## **trim method**
concat method helps to remove the empty spaces from the beginning and ending of the given string value

    //trim Method
    let name = "      RATHNA SCHOOLS  "
    let result = name.trim()
    console.log(result)

 Output

    RATHNA SCHOOLS

## **padStart method**
padStart method helps to pad the given string with start of another string

    //padStart Method
    let input = "SCHOOLS";
    let result = input.padStart(14,"RATHNA ");
    console.log(result)

 Output

    RATHNA SCHOOLS

## **padEnd method**
padEnd method helps to pad the given string with end of another string

    //padEnd Method
    let input = "SCHOOLS";
    let result = input.padEnd(14," RATHNA");
    console.log(result)

 Output

    SCHOOLS RATHNA

## **charAt method**
charAt method helps to return the specified index's characters from the given input string

    //charAt Method
    let input = "RATHNA SCHOOLS";
    let result = input.charAt(3)
    console.log(result)

 Output

    H

## **charCodeAt method**
charCodeAt method helps to return the unicode of the specified index's characters from the given input string

    //charCodeAt Method
    let input = "RATHNA SCHOOLS";
    let result = input.charCodeAt(3)
    console.log(result)

 Output

    72