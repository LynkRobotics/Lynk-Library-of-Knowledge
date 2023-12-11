# Lynk Java Style Guide <br>

## Overview <br>
Coding style is an important part of good software engineering practice. The goal is to write code that is clear and easy to understand, reducing the effort required to make future extensions or modifications. <br>

### Why we use a style guide XKCD <br>
![image](http://imgs.xkcd.com/comics/code_quality.png)

## Comments <br>
Comments should be used to give overviews of code and provide additional information that is not readily available in the code itself. Comments should contain only information that is relevant to reading and understanding the program. Avoid duplicating information that is clearly evident in the code. <br>


## Naming Conventions <br>
As a rule, Java uses camel case (eg. camelCase) for most names, including variables and methods. However, there are some variations depending on what you are naming. <br>

Class and Interface names use pascal case (eg. PascalCase), which is like camel case, except they start with a capital letter. For example, the drive subsystem class is named DriveSubsystem, not driveSubsystem. <br>

````java
public class DriveSubsystem {

}
````
#### tbd <br>
Constants do not use camel case, and instead use snake case (eg. snake_case) with all uppercase letters. For example, if you wanted to store a CAN constant of a drive motor, you could name it DRIVE_M.





