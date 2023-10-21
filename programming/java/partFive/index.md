# Part Five


<br>

<br>

***

<br> 

## Preface

<br>

In this part you will learn about making a objects and methods.
We will be using this block of Java code for this part. 

````Java
public class JavaIntro5 {                       
    public static void main(String args[]) {    
      motor m1 = new motor(0);              //new is used to create an instance of the class called an object
      motor m2 = new motor(1);
      
      System.out.println("m1 channel: " + m1.getChannel());
      System.out.println("m2 channel: " + m2.getChannel());
      
      m1.setSpeed(1);
      m2.setSpeed(-1);

      System.out.println("m1 speed: " + m1.getSpeed());
      System.out.println("m2 speed: " + m2.getSpeed());
    }                                          
}   

//Simple motor class
class motor{
    //classes can have fields that store data
    int channel;                //which port is the motor connected too
    double speed = 0;           //how fast should the motor be going -1 to 1
    
    motor(int c){               //This is the constructor, it doesn't have a return type or void
        channel = c;            //channel doesn't get a value set until the consttuctor is run
    }
    
    int getChannel(){          //this is a "getter" method it returns a value
        return channel;
    }
    
    double getSpeed(){          
        return speed;
    }
    
    void setSpeed(double s){    //this is a "setter" method it sets a value
        speed = s;
    }
    //a complete motor class would have methods that actually control the motor
    //most of those methods are already created for us in FRC
}
````

<br>

***

<br>

# [Previous Page](https://docs.lynkrobotics.org/programming/java) / [Home](https://docs.lynkrobotics.org/) / [Next Page](./objects.md) 

<br>

***

<br> 

## Table Of Contents

<br>

- [Creating and using objects](./objects.md)
- [Making our own class](./classes.md)



<br>

***

<br>

