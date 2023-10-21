# Part Three


<br>


<br>

***

<br> 

## Preface

<br>

In this part you will learn about todo
We will be using this block of Java code for this part. 

````Java
public class JavaIntro3 {                        //This creates the "class", for now think of each class like a document or file
    public static void main(String args[]) {    //This line lets Java know what to run when you click execute below
        boolean b1 = true;
        boolean b2 = false;
        int x = 10;
        int y = 20;
        
        if (b1){                                        //"if" statements decide to do something based on if something is true or false
            System.out.println("b1 is true");           //The statements inside the {} braces will run if the statement in () is true
        }
        
        if (b1 && b2){                                  //We can use logical operators in addition to booleans
            System.out.println("(b1 && b2) is true");
        } else {                                        //"else" lets us do things when the if statement is false
            System.out.println("(b1 && b2) is false"); 
        }
        
        if (x == y){                                    //We can use comparison operators as well
            System.out.println("x equals y");
        } else if (x > y){                              //"else if" allows us to check another statement if the first statement was false
            System.out.println("x greater than y");
        } else {
            System.out.println("x less than y");
        }
    }                                           //End of main
}                                               //End of JavaIntro3
````

<br>

***

<br>

# [Previous Page](https://docs.lynkrobotics.org/programming/java) / [Home](https://docs.lynkrobotics.org/) / [Next Page](./if.md) 

<br>

***

<br> 

## Table Of Contents

<br>

- [if, else if, else](./if.md)



<br>

***

<br>


