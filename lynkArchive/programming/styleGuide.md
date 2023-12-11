# Lynk Java Style Guide <br>

## Overview <br>
Coding style is an important part of good software engineering practice. The goal is to write code that is clear and easy to understand, reducing the effort required to make future extensions or modifications. <br>

### Why we use a style guide XKCD <br>
![image](http://imgs.xkcd.com/comics/code_quality.png)

***

## Naming Conventions <br>
### Variable and Methods <br>
As a rule, Java uses camel case (eg. camelCase) for most names, including variables and methods. However, there are some variations depending on what you are naming.
````java
public int userAge; // variable

public int getUserAge(){ // method
  return userAge;
}
````
Class and Interface names use pascal case (eg. PascalCase), which is like camel case, except they start with a capital letter. For example, the linked list class is named LinkedList, not linkedList.
````java
public class LinkedList { // Class
}
````
Constants do not use camel case, and instead use snake case (eg. snake_case) with all uppercase letters. For example, if you wanted to store the constant pi, you could name it VALUE_OF_PI.
````java
public class Constants {
  public static final double VALUE_OF_PI = 3.14159; // constant
}
````

|                       Type                       |                      Naming Convention                      | Example |
| :----------------------------------------------: | :--------------------------------------------: | :-------: |
| Class | PascalCase | LinkedList |
| Constant | snake_case | VALUE_OF_PI |
| Method | cammelCase | myMethod |
| Variable | cammelCase | numLetters |

***

## Brackets and Parentheses <br> 
Brackets ({ and }) must be used for all method and class declarations, as well as conditionals and loops that contain multiple lines of code.

While you can omit brackets for single line conditionals and loops, it’s best practice to use them for readability. For example,
````java
if (true) {
  return false;
}
````
is much more readable than
````java
if true
  return false;
````
Along the same lines, parentheses (( and )) should be used for the arguments of the conditional or loop, as seen in the example above.

***

## Indentations and Spacing <br>
While the amount of whitespace doesn’t affect the compilation and running of code in Java, there are standards that help with readability.

All indentations should be two spaces (or tab), and there should be an indentation each time a new block (eg. loop, method, etc) is opened, as seen in the examples above and below.

````java
public class JavaExample {
  public class Constants {
    public static final double VALUE_OF_PI = 3.14;
  }
  public static void Main(String[] args){
    if (VALUE_OF_PIE == 3.14){
      return true;
    } else {
      return false;
    }
  }
}
````

There should be spaces before and after keywords and operators. For example, while

````java
x=3;
````
is valid syntax, placing a space between each side of the operator keeps the code clear and readable:
````java
x = 3;
````

*** 

## Class Headers <br>
All source files should begin with a class header that lists the team name and number (Lynk 9496), the current season, and if it is Off-Season or In-Season
````java
// Lynk 9496
// Season: 2024 Crescendo
// Status: In-Season

public class JavaExample {
  
}
````

*** 


