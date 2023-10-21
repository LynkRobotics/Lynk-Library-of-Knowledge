# Making our own class

<br>

***

<br>

- Each class gets a unique name.
- Classes can contain variables.
    - Classes can also contain objects of classes as well
- The constructor is a method with the same name as the class
    - The constructor doesn’t return any type and doesn’t declare `void` either
    - This is the method called when new is used to create an object

<br>

***

<br>

## Example

<br>

````java
//Simple motor class
class motor{
    //classes can have fields that store data
    int channel;                //which port is the motor connected too
    double speed = 0;           //how fast should the motor be going -1 to 1
````

<br>

***

<br>

- A class can also have it’s own methods
- Methods that return a single value are called getter methods
- Methods that send values to variables are called setter methods
- More complicated methods also exist in classes

<br>

## Examples

<br>

````Java
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
````
<br>

***

<br>

# [Previous Page](./objects.md) / [Home](./index.md) / [Next Page](https://docs.lynkrobotics.org/programming) 

