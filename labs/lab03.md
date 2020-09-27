---
layout: default
title: "Lab 3: Arrays"
---

## Getting Started

Download [CS201\_Lab03\_Gradle.zip](CS201_Lab03_Gradle.zip). Extract the zip file and import it into Eclipse

> **File&rarr;Import...&rarr;Gradle&rarr;Existing Gradle Project**

You should see a project called **CS201\_Lab03\_Gradle** in the Package Explorer window.

## Your task

Implement the following static methods in the **Arrays** class:

-   **readArray**: Takes two parameters, **keyboard** and **numElements**. **keyboard** is a **Scanner** object you can use to read input from the user. **numElements** is the number of integer values to read. The method should return a reference to an array containing the requested number of integer values.

-   **printArray**: Takes a parameter **arr**, an array of integer values. The method should print out the element values in the array.

-   **reverseArray**: Takes a parameter **arr**, an array of integer values. The method should reverse the values in the elements of the array. For example, if passed an array containing the values **1 2 3**, the method should re-arrange the contents of the array so that it contains the values **3 2 1**.

As you implement each method, be sure to comment out

> **throw new UnsupportedOperationException("TODO - implement");**

A **main** method is provided for testing - you won't need to change it. 

Run the program by right-clicking on the file **Arrays.java** in the **src/main/java/(default package)** package, and then choosing

> **Run As&rarr;Java Application**

When you run the **main** method, you should see output looking something like this (user input in **bold**):

<pre>
How many values? 
<b>5</b>
Please enter 5 values:
<b>9 0 1 2 5</b>
You entered the following values:
9 0 1 2 5 
Now I am going to reverse the array for you...
Here are the reversed array values:
5 2 1 0 9 
</pre>

## Submitting

When you are done, submit the lab to the Marmoset server using either of the methods below.

### From Eclipse

If you have the [Simple Marmoset Uploader Plugin](../resources/index.html) installed, then right click on the project (**CS201\_Lab03\_Gradle**) and choose **Submit project...**. Enter your Marmoset username and password when prompted.

### From a web browser

Save the project (**CS201\_Lab03\_Gradle**) to a zip file by right-clicking it and choosing

> **Export...&rarr;Archive File**

Upload the saved zip file to the Marmoset server as **lab03**. The server URL is

> [https://cs.ycp.edu/marmoset/](https://cs.ycp.edu/marmoset/)
