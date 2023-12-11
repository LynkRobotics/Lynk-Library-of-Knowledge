# Lynk Java Style Guide <br>

## Overview <br>
Coding style is an important part of good software engineering practice. The goal is to write code that is clear and easy to understand, reducing the effort required to make future extensions or modifications. <br>

### Why we use a style guide XKCD <br>
![image](http://imgs.xkcd.com/comics/code_quality.png)

## Comments <br>
Comments should be used to give overviews of code and provide additional information that is not readily available in the code itself. Comments should contain only information that is relevant to reading and understanding the program. Avoid duplicating information that is clearly evident in the code. <br>

````java
/*
Initalizes all 4 Swerve modules with their constants and positions
0 1
2 3
*/
mSwerveMods = new SwerveModule[] {
  new SwerveModule(0, Constants.Swerve.Mod0.constants),
  new SwerveModule(1, Constants.Swerve.Mod1.constants),
  new SwerveModule(2, Constants.Swerve.Mod2.constants),
  new SwerveModule(3, Constants.Swerve.Mod3.constants)
};
````

## Naming Conventions <br>

### Variables and Methods <br>
As a rule, Java uses camel case (eg. camelCase) for most names, including variables and methods. <br> 

````java
// Variable Example
public Pose2d currentPose = getPose(); 

// Method Example
public Pose2d getPose() { 
  return swerveOdometry.getPoseMeters();
}
````

### Classes <br>
However, there are some variations depending on what you are naming. <br>
Class and Interface names use pascal case (eg. PascalCase), which is like camel case, except they start with a capital letter. For example, the drive subsystem class is named DriveSubsystem, not driveSubsystem. <br>

````java
// Class Example
public class DriveSubsystem {

}
````
### Constants <br>
Constants should be held in the `Constants.java` class, and they should be easily readible and organized into smaller subclasses.
All constants should be `public static final` because constants do not change
````java
public final class Constants { // Constants Class

  public static final class Swerve { // Swerve Class

    public static final int pigeonID = 1; //some swerve constants
    public static final boolean invertGyro = false; 

    public static final class Mod0 { // Module 0 Class
      public static final int driveMotorID = 1; // Camel Case styling
      public static final int angleMotorID = 2;
      public static final int canCoderID = 1;
      public static final String canBus = "rio";
      public static final Rotation2d angleOffset = Rotation2d.fromDegrees(0.0);
      public static final SwerveModuleConstants constants = new SwerveModuleConstants(driveMotorID, angleMotorID,
        canCoderID, canBus, angleOffset);
    }
  }
}
````

## Class Headers <br>
All source files should begin with a class header that lists the class name, year: game, and team (9496 Lynk) <br>

````java
// Code for: Drive Subsystem | 2023: Charged Up! | 9496 Lynk

package frc.robot.subsystems;

import frc.robot.Constants;

public class DriveSubsystem extends SubsystemBase {
  
}
````

## Brackets and Parentheses <br>
Brackets ({ and }) must be used for all method and class declarations, as well as conditionals and loops that contain multiple lines of code. <br>
While you can omit brackets for single line conditionals and loops, it’s best practice to use them for readability. For example, <br>
````java
if (true) {
  return false;
}
````
is more readable than:
````java
if true
  return false;
````
Along the same lines, parentheses (( and )) should be used for the arguments of the conditional or loop, as seen in the example above. <br>

## Indentations and Spacing <br>
While the amount of whitespace doesn’t affect the compilation and running of code in Java, there are standards that help with readability.

All indentations should be two spaces, and there should be an indentation each time a new block (eg. loop, method, etc) is opened, as seen in the examples above.

There should be spaces before and after keywords and operators. For example, while
````java
x=3;
````
is valid syntax, placing a space between each side of the operator keeps the code clear and readable:
````java
x = 3;
````







