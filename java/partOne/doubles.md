# Doubles

<br>

***

<br> 

- A `double` is another variable type, that allows numbers with decimal points to be stored in them.
  - If we change all the `int` variables to `double` variables in our program the division will be more accurate.
  - `Answer` is now `0.5` instead of `0`

<br>

***

<br>

## Example

<br>

````Java
//Anything typed after a "//" is comment, the complier ignores comments
//Comments are used to provide more information about what a program is doing.

public class JavaIntro {                        //This creates the "class", for now think of each class like a document or file
    public static void main(String args[]) {    //This line lets Java know what to run when you click execute below
      double x = 10;
      double y = 20;
      double answer = x / y;

      System.out.println("Answer: " + answer);
    }                                           //End of main
}                                               //End of JavaIntro
````

<br>

`Output: 0.5`

<br>

***

<br>

# [Previous Page](./division.md) / [Home](./index.md) / [Next Page](./strings.md)
