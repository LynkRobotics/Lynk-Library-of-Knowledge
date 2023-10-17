# Part Two

<br>

Welcome to the beginner Java tutorial, this is the landing page for part two. I ask if you are new to programming and/or Java for that matter, please go in order to reduce possible confusion. 

<br>

***

<br> 

## Preface

<br>
We will be learning about Boolean Logic, and Comparison Operators in this part.
We will be using this block of Java code for this part. 

````Java
public class JavaIntro2 {                        //This creates the "class", for now think of each class like a document or file
    public static void main(String args[]) {    //This line lets Java know what to run when you click execute below
      boolean b1 = true;                        //boolean variables can only hold true or false
      boolean b2 = false;

      System.out.println("AND: b1 && b2: " + (b1 && b2));     //&& is AND, only when both values are true is && true
      System.out.println("OR: b1 || b2: " + (b1 || b2));        //|| is OR, when either value is true || is true
      System.out.println("NOT: !b1: " + !b1);                   //! is NOT, ! changes true to false, or false to true
      
      int x = 10;
      int y = 20;
      
      System.out.println("x < y: " + (x < y));                  //<, >, and == are comparison operators, they result in booleans
      System.out.println("x > y: " + (x > y));                  //<=, >=, and != are also comparison operators, what do they do?
      System.out.println("x == y: " + (x == y));
      
    }                                           //End of main
}                                               //End of JavaIntro2
````

<br>

***

<br>

# [Previous Page](https://docs.lynkrobotics.org/java) / [Home](https://docs.lynkrobotics.org/) / [Next Page](./booleanLogic.md) 

<br>

***

<br> 

## Table Of Contents

<br>

- [Boolean Logic](./booleanLogic.md) 
- [Comparison Operators](./comparisonOperators.md) 
