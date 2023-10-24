# Making a Method

<br>

- For now just know public static help the program work.
    - A lot of times you can copy patterns from parts of the program without always knowing what they do
- The next value is the return type
    - In the first method its `double`, in the second its `void`
    - `void` is used is when the method won’t send any data back
    - A method could return any type (boolean, string, etc)

<br>

## Example

<br>

````java
 /*add 4 to the paramter sent to the method and return the result*/
    public static double addFour(double num){   // the varible type before the method name is what type will be returned
        return num + 4;                         //return is the keyword that tells java to end the method and send the value
    }
    
    /*if the boolean named bol is true than print out the double named num*/
    public static void ifTruePrint(boolean bol, double num){    //void means the method won't return any value
        if (bol){
            System.out.println(num);
        }
    }                                                           //this method doesn't return a value
````

<br>

***

<br>

- Methods can have parameters these are places where you can send it information.
- `addFour` has one parameter num 
    - these are like variables that are required to be given a value for the method to work.

<br>

***

<br>

- `Return` is a java keyword that tells the program what data the method should send back
- If the method returns `void` you don’t have return in the method at all.

<br>

***

<br>

# [Previous Page](./index.md) / [Home](./index.md) / [Next Page](https://docs.lynkrobotics.org/programming/java/partFive) 



