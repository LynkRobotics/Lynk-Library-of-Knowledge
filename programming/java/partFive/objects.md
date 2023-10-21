# Creating and using objects

<br>

***

<br>

- An instance of a class is called an **object**
- To create an object we use the `new` keyword
    - You can see the pattern is similar to making a new variable
- Each object is a new instance of the class
    - They keep their own values
- We use the object.method() pattern to use methods inside an object

<br>

***

<br>

## Example 

<br>

````Java
motor m1 = new motor(0);              //new is used to create an instance of the class called an object
      motor m2 = new motor(1);
      
      System.out.println("m1 channel: " + m1.getChannel());
      System.out.println("m2 channel: " + m2.getChannel());
      
      m1.setSpeed(1);
      m2.setSpeed(-1);

      System.out.println("m1 speed: " + m1.getSpeed());
      System.out.println("m2 speed: " + m2.getSpeed());
````

<br>

# [Previous Page](./index.md) / [Home](./index.md) / [Next Page](./classes.md) 