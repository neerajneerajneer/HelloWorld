# HelloWorld Java Project

## Project Overview
The **HelloWorld** project is a simple Java application that prints "Hello, World!" to the console. This project serves as an introductory exercise for understanding the basic syntax and structure of Java programming.

## Purpose
The purpose of this project is to familiarize myself with Java programming by creating a foundational application that demonstrates how to write, compile, and execute Java code.

## Learning Objectives
- Understand basic Java syntax.
- Learn about class and method structures.
- Familiarize myself with the Eclipse IDE for development.
- Practice outputting text to the console.

## Project Structure
The project contains the following files:
- `HelloWorld.java`: The main Java class containing the code to print "Hello, World!" to the console.

## Steps to Create the Project

### Step 1: Setting Up the Development Environment
1. **Download and Install Eclipse IDE**:
   - Go to the [Eclipse website](https://www.eclipse.org/downloads/).
   - Download the installer for your operating system.
   - Follow the installation instructions to set up Eclipse on your computer.

2. **Install Java Development Kit (JDK)**:
   - Download the latest JDK from [Oracle's website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
   - Follow the instructions to install JDK on your machine.

### Step 2: Create a New Java Project in Eclipse
1. **Open Eclipse IDE**.
2. **Create a New Java Project**:
   - Click on `File` > `New` > `Java Project`.
   - Enter the project name as `HelloWorld`.
   - Click `Finish`.

### Step 3: Create a New Java Class
1. **Right-click on the `src` folder** in your project.
2. Select `New` > `Class`.
3. **Enter the Class Name**:
   - Type `HelloWorld` in the class name field.
   - Check the box for `public static void main(String[] args)`.
   - Click `Finish`.

### Step 4: Write the Code
1. **Open the `HelloWorld.java` file**.
2. **Add the following code**:
   ```java
   public class HelloWorld {
       public static void main(String[] args) {
           System.out.println("Hello, World!");
       }
   }
