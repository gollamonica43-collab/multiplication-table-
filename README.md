# Multiplication Table in Java

## 📌 Project Name

**Multiplication Table**

## 📖 Project Description

This is a simple Java program that generates the **multiplication table of a number** entered by the user.

The program uses a `for` loop to calculate and display the multiplication table from **1 to 10**.

## 🎯 Objective

The objective of this project is to learn:

* Java variables
* User input using `Scanner`
* `for` loops
* Arithmetic operators
* Multiplication
* Basic Java programming

## 🛠️ Technologies Used

* Java
* Scanner
* For Loop
* Arithmetic Operators

## 📂 Project Structure

```text
multiplication-table-java/
│
├── MultiplicationTable.java
└── README.md
```

## 💻 Java Code

```java
import java.util.Scanner;

public class MultiplicationTable {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int number = scanner.nextInt();

        System.out.println("\nMultiplication Table of " + number);

        for (int i = 1; i <= 10; i++) {
            System.out.println(number + " x " + i + " = " + (number * i));
        }

        scanner.close();
    }
}
```

## ▶️ How to Run

### Step 1: Check Java Installation

Open the terminal and run:

```bash
java -version
```

### Step 2: Compile the Program

```bash
javac MultiplicationTable.java
```

### Step 3: Run the Program

```bash
java MultiplicationTable
```

## ⌨️ Example 1

### Input

```text
Enter a number: 5
```

### Output

```text
Multiplication Table of 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

## ⌨️ Example 2

### Input

```text
Enter a number: 7
```

### Output

```text
Multiplication Table of 7
7 x 1 = 7
7 x 2 = 14
7 x 3 = 21
7 x 4 = 28
7 x 5 = 35
7 x 6 = 42
7 x 7 = 49
7 x 8 = 56
7 x 9 = 63
7 x 10 = 70
```

## 🔍 How It Works

First, the program asks the user to enter a number:

```java
int number = scanner.nextInt();
```

A `for` loop then runs from `1` to `10`:

```java
for (int i = 1; i <= 10; i++) {
    System.out.println(number + " x " + i + " = " + (number * i));
}
```

For every loop iteration, the entered number is multiplied by the current value of `i`.

For example, if the user enters `5`:

```text
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
...
5 x 10 = 50
```

## ⏱️ Complexity

* **Time Complexity:** O(1)
* **Space Complexity:** O(1)

The loop always runs exactly 10 times.

## 📚 What I Learned

Through this project, I learned:

* How to take input using `Scanner`
* How to use variables
* How to use a `for` loop
* How to perform multiplication in Java
* How to format program output
* Basic Java programming logic

## 🚀 Future Improvements

This project can be improved by:

* Allowing the user to choose the ending number
* Printing tables from 1 to 10
* Printing multiple multiplication tables
* Creating a multiplication-table menu
* Adding input validation

## 👨‍💻 Author

**Java Beginner Project**

Created to practice Java loops, user input, and arithmetic operations.
