Javascript strings are used to create, store and manipulate the text characters

## **String declaration**
Single or Double quotes are used to declare the strings in javascript like the below example

    //String with single quotes
    str1 = 'string with single quotes'
    console.log(typeof(str1), str1)

    //String with double quotes
    str2 = "string with double quotes"
    console.log(typeof(str2), str2)

    //String with single and double quotes
    str3 = 'string with "single" quotes'
    console.log(typeof(str3), str3)

    //String with double and single quotes
    str4 = "string with 'double' quotes"
    console.log(typeof(str4), str4)

 Output

    string string with single quotes
    string string with double quotes
    string string with "single" quotes
    string string with 'double' quotes

## **String reading**
Strings can be read with the help of positive index value

| R  | A  | T  | H  | N  | A  | S  | C  | H  | O  | O  | L  | S  |
| :--|:--:| --:| --:| --:| --:| --:| --:| --:| --:| --:| --:| --:|
| 0  | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10  | 11  | 12  |

    //String Reading
    school_name = "RATHNASCHOOLS"

    //Reading the first character of the string
    console.log(school_name[0])

    //Reading the second character of the string
    console.log(school_name[1])

    //Reading the last character of the string
    console.log(school_name[12])

 Output

    R
    A
    S

## **String update**
In Javascript, strings are immutable which means it cannot be changed once declared

    //String Update
    school_name = "RATHNASCHOOLS"

    //Item assignment ignored for immutable objects
    school_name[1] = "E"
    console.log(school_name)

 Output

    RATHNASCHOOLS

Needs to redeclare the variable once again with new value is the only option to update the string javascript

    //String Update
    school_name = "RATHNASCHOOLS"

    //Object Recreation
    school_name = "RETHNASCHOOLS"
    console.log(school_name)

 Output

    RETHNASCHOOLS

## **String deletion**
In Javascript, strings are immutable which means it cannot be specific character deletion is impossible

    //String Deletion
    school_name = "RATHNASCHOOLS"

    //Item deletion impossible for immutable objects
    delete school_name[0]
    console.log(school_name)

 Output

    RATHNASCHOOLS

Entire variable deletion can be possible like the below example

    //String Deletion
    school_name = "RATHNASCHOOLS"

    //Entire object deletion is possible
    delete school_name
    console.log(school_name)

 Output

    console.log(school_name)
                ^
    ReferenceError: school_name is not defined

## **String slicing**
With the help of slice methods, string can be sliced with start and end index as parameters

    //String Slicing
    school_name = "RATHNASCHOOLS"

    //Print the first three characters
    console.log(school_name.slice(0,3))

    //Print the middle three characters
    console.log(school_name.slice(6,9))

    //Print the last two characters
    console.log(school_name.slice(11,13))

 Output

    RAT
    SCH
    LS