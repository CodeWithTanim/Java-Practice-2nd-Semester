# ☕ Java Practice - 2nd Semester

[![Java Version](https://img.shields.io/badge/Java-8%20%7C%2011%20%7C%2017%20%7C%2021-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Repository](https://img.shields.io/badge/GitHub-Java--Practice--2nd--Semester-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CodeWithTanim/Java-Practice-2nd-Semester)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-brightgreen.svg?style=for-the-badge)](https://github.com/CodeWithTanim/Java-Practice-2nd-Semester)

A comprehensive, structured collection of core **Java Laboratory Exercises and Practical Programming Solutions** developed for the **2nd Semester Computer Science / Engineering** curriculum.

> 📌 **Repository Organization Note:**  
> Each directory in this repository is explicitly named after the **Question / Assignment Problem Statement**. This provides immediate clarity on the problem being solved, its algorithmic constraints, and the corresponding implementation.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Repository Structure](#-repository-structure)
- [Curriculum & Concepts Matrix](#-curriculum--concepts-matrix)
- [Questions & Features Index](#-questions--features-index)
- [Detailed Feature Breakdown](#-detailed-feature-breakdown)
  - [P2 - Hello World Program](#p2---write-save-compile-and-execute-a-helloworld-program-in-java)
  - [P3 - Addition of Two Integers](#p3---write-a-java-program-to-add-two-integers)
  - [P4 - Floating-Point Multiplication](#p4---write-a-java-program-to-multiply-two-floating-point-numbers)
  - [P5 - ASCII Value Extraction](#p5---write-a-java-program-to-find-ascii-value-of-a-character)
  - [P6 - Quotient and Remainder Computation](#p6---write-a-java-program-to-compute-quotient-and-remainder)
  - [P7 - Vowel or Consonant via `if..else`](#p7---write-a-java-program-to-check-whether-an-alphabet-is-vowel-or-consonant-using-ifelse-statement)
  - [P8 - Vowel or Consonant via `switch`](#p8---write-a-java-program-to-check-whether-an-alphabet-is-vowel-or-consonant-using-switch-statement)
  - [P9 - Largest of Three Numbers via `if..else`](#p9---write-a-java-program-to-find-largest-among-three-numbers-using-ifelse-statement)
  - [P10 - Largest of Three Numbers via Nested `if..else`](#p10--write-a-java-program-to-find-the-largest-number-among-three-using-nested-ifelse-statement)
  - [P11 - Leap Year Checker](#p11---write-a-java-program-to-check-whether-a-year-is-a-leap-year)
  - [P12 - Swap Two Numbers with Temporary Variable](#p12---write-a-java-program-to-swap-two-numbers-using-temporary-variable)
  - [Q13 - Class and Object Fundamentals](#q13---write-a-program-in-java-to-show-the-working-of-a-class-and-an-object)
  - [Q14 - Student Class Design (Variables & Methods)](#q14---write-a-program-in-java-to-create-a-student-class-with-3-variables-and-2-methods)
- [How to Set Up & Run](#-how-to-set-up--run)
- [Author & Connect](#-author--connect)

---

## 📖 Overview

This repository is designed as an educational reference covering foundational to intermediate Java concepts. It takes learners systematically through:
1. **Basic Syntax & Execution**: Standard console I/O, compilation workflow, and main execution entry points.
2. **Data Types & Arithmetic**: Primitive types (`int`, `float`, `char`, `double`), mathematical operators, quotient/remainder calculation, and explicit type casting.
3. **Control Flow & Decision Logic**: Sequential statements, conditional branching (`if..else`), nested conditional trees, and multi-branch `switch` selections with fall-through logic.
4. **Algorithmic Exercises**: Gregorian calendar leap-year verification and in-memory variable swapping using auxiliary storage.
5. **Object-Oriented Programming (OOP)**: Custom class definitions, state attributes (instance variables), behavior encapsulation (instance methods), object instantiation via `new`, and multi-instance independence.

---

## 📂 Repository Structure

```plaintext
Java-Practice-2nd-Semester/
│
├── P2 - Write, save, compile, and execute a Helloworld program in Java/
│   └── HelloWorld.java
│
├── P3 - Write a Java program to add two integers/
│   └── AddTwoIntegers.java
│
├── P4 - Write a Java program to multiply Two Floating-Point Numbers/
│   └── MultiplyTwoFloats.java
│
├── P5 - Write a Java program to find ASCII value of a character/
│   └── AsciiValueOfChar.java
│
├── P6 - Write a Java program to compute Quotient and Remainder/
│   └── QuotientAndRemainder.java
│
├── P7 - Write a Java program to check whether an alphabet is vowel or consonant using if..else statement/
│   └── VowelOrConsonant.java
│
├── P8 - Write a Java program to check whether an alphabet is vowel or consonant using switch statement/
│   └── VowelOrConsonantSwitch.java
│
├── P9 - Write a Java program to find Largest Among three numbers using if..else statement/
│   └── LargestAmongThree.java
│
├── P10- Write a Java program to find the largest number among three using nested if..else statement/
│   └── LargestAmongThreeNested.java
│
├── P11 - Write a Java program to check whether a Year is a Leap Year/
│   └── LeapYearChecker.java
│
├── P12 - Write a Java program to Swap two numbers using temporary variable/
│   └── SwapNumbers.java
│
├── Q13 - Write a program in Java to show the working of a class and an object/
│   └── ClassAndObjectExample.java
│
├── Q14 - Write a program in Java to create a student class with 3 variables and 2 methods/
│   └── StudentClassExample.java
│
└── README.md
```

---

## 🎯 Curriculum & Concepts Matrix

| Category | Key Concepts Covered | Relevant Programs / Questions |
| :--- | :--- | :--- |
| **Java Fundamentals** | Program structure, `main()` method, standard output stream | `P2` |
| **Input & Arithmetic** | `java.util.Scanner`, interactive user input, binary operators (`+`, `*`) | `P3`, `P4` |
| **Data Types & Casting** | Primitive conversion, character-to-integer ASCII mapping | `P5` |
| **Division Mathematics** | Truncated integer division (`/`), modulo remainder (`%`) | `P6` |
| **Conditional Branching** | `if..else`, logical OR (`||`), input character validation | `P7` |
| **Selection Control** | Multi-case `switch`, case fall-through, `default` handling | `P8` |
| **Relational Logic** | Comparative analysis, compound conditions (`&&`, `>=`) | `P9` |
| **Decision Trees** | Nested conditional statements without logical compound operators | `P10` |
| **Algorithms** | Gregorian calendar leap year math, 3-step variable value swapping | `P11`, `P12` |
| **Object-Oriented Programming** | Class definition, objects, attributes, member methods, grading logic | `Q13`, `Q14` |

---

## 📋 Questions & Features Index

Every folder name corresponds directly to the official Question statement:

| # | Question Name (Folder Name) | Source File | Core Focus |
| :---: | :--- | :--- | :--- |
| **P2** | [P2 - Write, save, compile, and execute a Helloworld program in Java](./P2%20-%20Write,%20save,%20compile,%20and%20execute%20a%20Helloworld%20program%20in%20Java) | [`HelloWorld.java`](./P2%20-%20Write,%20save,%20compile,%20and%20execute%20a%20Helloworld%20program%20in%20Java/HelloWorld.java) | Environment test & standard output |
| **P3** | [P3 - Write a Java program to add two integers](./P3%20-%20Write%20a%20Java%20program%20to%20add%20two%20integers) | [`AddTwoIntegers.java`](./P3%20-%20Write%20a%20Java%20program%20to%20add%20two%20integers/AddTwoIntegers.java) | Integer I/O & addition operator |
| **P4** | [P4 - Write a Java program to multiply Two Floating-Point Numbers](./P4%20-%20Write%20a%20Java%20program%20to%20multiply%20Two%20Floating-Point%20Numbers) | [`MultiplyTwoFloats.java`](./P4%20-%20Write%20a%20Java%20program%20to%20multiply%20Two%20Floating-Point%20Numbers/MultiplyTwoFloats.java) | Floating-point precision arithmetic |
| **P5** | [P5 - Write a Java program to find ASCII value of a character](./P5%20-%20Write%20a%20Java%20program%20to%20find%20ASCII%20value%20of%20a%20character) | [`AsciiValueOfChar.java`](./P5%20-%20Write%20a%20Java%20program%20to%20find%20ASCII%20value%20of%20a%20character/AsciiValueOfChar.java) | Explicit casting (`char` $\to$ `int`) |
| **P6** | [P6 - Write a Java program to compute Quotient and Remainder](./P6%20-%20Write%20a%20Java%20program%20to%20compute%20Quotient%20and%20Remainder) | [`QuotientAndRemainder.java`](./P6%20-%20Write%20a%20Java%20program%20to%20compute%20Quotient%20and%20Remainder/QuotientAndRemainder.java) | Division operator (`/`) & Modulo (`%`) |
| **P7** | [P7 - Write a Java program to check whether an alphabet is vowel or consonant using if..else statement](./P7%20-%20Write%20a%20Java%20program%20to%20check%20whether%20an%20alphabet%20is%20vowel%20or%20consonant%20using%20if..else%20statement) | [`VowelOrConsonant.java`](./P7%20-%20Write%20a%20Java%20program%20to%20check%20whether%20an%20alphabet%20is%20vowel%20or%20consonant%20using%20if..else%20statement/VowelOrConsonant.java) | Conditional branching & alphabet check |
| **P8** | [P8 - Write a Java program to check whether an alphabet is vowel or consonant using switch statement](./P8%20-%20Write%20a%20Java%20program%20to%20check%20whether%20an%20alphabet%20is%20vowel%20or%20consonant%20using%20switch%20statement) | [`VowelOrConsonantSwitch.java`](./P8%20-%20Write%20a%20Java%20program%20to%20check%20whether%20an%20alphabet%20is%20vowel%20or%20consonant%20using%20switch%20statement/VowelOrConsonantSwitch.java) | `switch` construct with case fall-through |
| **P9** | [P9 - Write a Java program to find Largest Among three numbers using if..else statement](./P9%20-%20Write%20a%20Java%20program%20to%20find%20Largest%20Among%20three%20numbers%20using%20if..else%20statement) | [`LargestAmongThree.java`](./P9%20-%20Write%20a%20Java%20program%20to%20find%20Largest%20Among%20three%20numbers%20using%20if..else%20statement/LargestAmongThree.java) | Compound logical comparison (`&&`) |
| **P10** | [P10- Write a Java program to find the largest number among three using nested if..else statement](./P10-%20Write%20a%20Java%20program%20to%20find%20the%20largest%20number%20among%20three%20using%20nested%20if..else%20statement) | [`LargestAmongThreeNested.java`](./P10-%20Write%20a%20Java%20program%20to%20find%20the%20largest%20number%20among%20three%20using%20nested%20if..else%20statement/LargestAmongThreeNested.java) | Nested hierarchical decisions |
| **P11** | [P11 - Write a Java program to check whether a Year is a Leap Year](./P11%20-%20Write%20a%20Java%20program%20to%20check%20whether%20a%20Year%20is%20a%20Leap%20Year) | [`LeapYearChecker.java`](./P11%20-%20Write%20a%20Java%20program%20to%20check%20whether%20a%20Year%20is%20a%20Leap%20Year/LeapYearChecker.java) | Gregorian calendar leap year formula |
| **P12** | [P12 - Write a Java program to Swap two numbers using temporary variable](./P12%20-%20Write%20a%20Java%20program%20to%20Swap%20two%20numbers%20using%20temporary%20variable) | [`SwapNumbers.java`](./P12%20-%20Write%20a%20Java%20program%20to%20Swap%20two%20numbers%20using%20temporary%20variable/SwapNumbers.java) | Variable swapping via buffer storage |
| **Q13** | [Q13 - Write a program in Java to show the working of a class and an object](./Q13%20-%20Write%20a%20program%20in%20Java%20to%20show%20the%20working%20of%20a%20class%C2%A0and%C2%A0an%C2%A0object) | [`ClassAndObjectExample.java`](./Q13%20-%20Write%20a%20program%20in%20Java%20to%20show%20the%20working%20of%20a%20class%C2%A0and%C2%A0an%C2%A0object/ClassAndObjectExample.java) | OOP blueprint class & object instantiation |
| **Q14** | [Q14 - Write a program in Java to create a student class with 3 variables and 2 methods](./Q14%20-%20Write%20a%20program%20in%20Java%20to%20create%20a%20student%20class%20with%203%20variables%C2%A0and%C2%A02%C2%A0methods) | [`StudentClassExample.java`](./Q14%20-%20Write%20a%20program%20in%20Java%20to%20create%20a%20student%20class%20with%203%20variables%C2%A0and%C2%A02%C2%A0methods/StudentClassExample.java) | State (3 vars) & behavior (2 methods) design |

---

## 🔍 Detailed Feature Breakdown

### P2 - Write, save, compile, and execute a Helloworld program in Java

- **Folder / Question Name:** `P2 - Write, save, compile, and execute a Helloworld program in Java`
- **Class Name:** `HelloWorld`
- **Source File:** [`HelloWorld.java`](./P2%20-%20Write,%20save,%20compile,%20and%20execute%20a%20Helloworld%20program%20in%20Java/HelloWorld.java)

#### 🌟 Key Features:
- **Canonical Entry Point:** Demonstrates the standard Java signature `public static void main(String[] args)` required by the Java Virtual Machine (JVM).
- **Console Stream Interaction:** Uses `System.out.println()` to emit characters to standard output terminated by a newline.
- **Workflow Demonstration:** Serves as the introductory template for the compile (`javac`) and execution (`java`) life cycle.

#### 🖥️ Output:
```text
Hello, World!
```

---

### P3 - Write a Java program to add two integers

- **Folder / Question Name:** `P3 - Write a Java program to add two integers`
- **Class Name:** `AddTwoIntegers`
- **Source File:** [`AddTwoIntegers.java`](./P3%20-%20Write%20a%20Java%20program%20to%20add%20two%20integers/AddTwoIntegers.java)

#### 🌟 Key Features:
- **Dynamic User Input:** Initializes `java.util.Scanner` hooked to `System.in` to parse user keystrokes in real time.
- **Integer Parsing:** Uses `scanner.nextInt()` to collect two integer values from standard input.
- **Binary Arithmetic Addition:** Implements addition using the `+` operator (`sum = num1 + num2`).
- **Resource Management:** Explicitly calls `scanner.close()` to release the input stream handle and prevent resource leaks.

#### 🖥️ Sample Run:
```text
Enter the first integer: 15
Enter the second integer: 25
The sum of 15 and 25 is: 40
```

---

### P4 - Write a Java program to multiply Two Floating-Point Numbers

- **Folder / Question Name:** `P4 - Write a Java program to multiply Two Floating-Point Numbers`
- **Class Name:** `MultiplyTwoFloats`
- **Source File:** [`MultiplyTwoFloats.java`](./P4%20-%20Write%20a%20Java%20program%20to%20multiply%20Two%20Floating-Point%20Numbers/MultiplyTwoFloats.java)

#### 🌟 Key Features:
- **Single-Precision Representation:** Utilizes the primitive `float` data type for fractional and decimal numbers.
- **Stream Tokenization:** Collects fractional user inputs via `scanner.nextFloat()`.
- **Arithmetic Product Calculation:** Performs multiplication via `product = num1 * num2`.
- **String Concatenation Display:** Presents the factors and resulting product with formatted console output.

#### 🖥️ Sample Run:
```text
Enter the first floating-point number: 4.5
Enter the second floating-point number: 2.0
The product of 4.5 and 2.0 is: 9.0
```

---

### P5 - Write a Java program to find ASCII value of a character

- **Folder / Question Name:** `P5 - Write a Java program to find ASCII value of a character`
- **Class Name:** `AsciiValueOfChar`
- **Source File:** [`AsciiValueOfChar.java`](./P5%20-%20Write%20a%20Java%20program%20to%20find%20ASCII%20value%20of%20a%20character/AsciiValueOfChar.java)

#### 🌟 Key Features:
- **Character Extraction:** Demonstrates reading a single character by reading the next token and extracting index 0 via `scanner.next().charAt(0)`.
- **Explicit Type Widening/Casting:** Casts a `char` primitive to an `int` primitive using `(int) character`.
- **Encoding Demonstration:** Illustrates how Java stores character literals as numeric Unicode/ASCII code points in memory.

#### 🖥️ Sample Run:
```text
Enter a character: A
The ASCII value of 'A' is: 65
```

---

### P6 - Write a Java program to compute Quotient and Remainder

- **Folder / Question Name:** `P6 - Write a Java program to compute Quotient and Remainder`
- **Class Name:** `QuotientAndRemainder`
- **Source File:** [`QuotientAndRemainder.java`](./P6%20-%20Write%20a%20Java%20program%20to%20compute%20Quotient%20and%20Remainder/QuotientAndRemainder.java)

#### 🌟 Key Features:
- **Division Duality:** Illustrates the dual aspects of division arithmetic on integers.
- **Quotient Calculation:** Evaluates integer division via the `/` operator, truncating fractional values.
- **Modulo Remainder Calculation:** Employs the `%` (modulus) operator to determine the remainder left after integer division.
- **Multi-Value Reporting:** Displays both metrics side-by-side for clear mathematical comparison.

#### 🖥️ Sample Run:
```text
Enter the dividend: 29
Enter the divisor: 4
Quotient: 7
Remainder: 1
```

---

### P7 - Write a Java program to check whether an alphabet is vowel or consonant using if..else statement

- **Folder / Question Name:** `P7 - Write a Java program to check whether an alphabet is vowel or consonant using if..else statement`
- **Class Name:** `VowelOrConsonant`
- **Source File:** [`VowelOrConsonant.java`](./P7%20-%20Write%20a%20Java%20program%20to%20check%20whether%20an%20alphabet%20is%20vowel%20or%20consonant%20using%20if..else%20statement/VowelOrConsonant.java)

#### 🌟 Key Features:
- **Input Sanitization & Normalization:** Converts input character to lowercase using `Character.toLowerCase(ch)` to enable case-insensitive evaluation.
- **Range-Based Input Validation:** Validates that the input character falls within the English alphabet boundaries (`ch >= 'a' && ch <= 'z'`), rejecting symbols, numbers, and whitespace.
- **Compound Logical Disjunction:** Checks against all English vowels using chained logical OR operators:
  ```java
  if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u')
  ```
- **Error Feedback:** Provides clear diagnostic output (`"Invalid input. Please enter a valid alphabet character."`) when non-alphabetic inputs are entered.

#### 🖥️ Sample Run:
```text
Enter a single alphabet character: E
e is a vowel.
```

---

### P8 - Write a Java program to check whether an alphabet is vowel or consonant using switch statement

- **Folder / Question Name:** `P8 - Write a Java program to check whether an alphabet is vowel or consonant using switch statement`
- **Class Name:** `VowelOrConsonantSwitch`
- **Source File:** [`VowelOrConsonantSwitch.java`](./P8%20-%20Write%20a%20Java%20program%20to%20check%20whether%20an%20alphabet%20is%20vowel%20or%20consonant%20using%20switch%20statement/VowelOrConsonantSwitch.java)

#### 🌟 Key Features:
- **Dual-Range Character Validation:** Verifies that the input belongs to upper or lower ASCII alphabetic characters: `(ch >= 'a' && ch <= 'z') || (ch >= 'A' && ch <= 'Z')`.
- **Case Fall-Through Technique:** Leverages deliberate switch fall-through across `'a'`, `'e'`, `'i'`, `'o'`, `'u'` without intermediate `break` statements to execute a unified vowel block.
- **Default Consonant Catch:** Employs the `default` label within the switch statement to automatically classify any other valid alphabet letter as a consonant.

#### 🖥️ Sample Run:
```text
Enter a single alphabet character: k
k is a consonant.
```

---

### P9 - Write a Java program to find Largest Among three numbers using if..else statement

- **Folder / Question Name:** `P9 - Write a Java program to find Largest Among three numbers using if..else statement`
- **Class Name:** `LargestAmongThree`
- **Source File:** [`LargestAmongThree.java`](./P9%20-%20Write%20a%20Java%20program%20to%20find%20Largest%20Among%20three%20numbers%20using%20if..else%20statement/LargestAmongThree.java)

#### 🌟 Key Features:
- **Double Precision Inputs:** Uses `scanner.nextDouble()` to accommodate integer, negative, and high-precision fractional inputs.
- **Compound Boolean Logic:** Evaluates conditions using logical AND (`&&`) combined with greater-than-or-equal (`>=`):
  ```java
  if (num1 >= num2 && num1 >= num3) { ... }
  else if (num2 >= num1 && num2 >= num3) { ... }
  else { ... }
  ```
- **Equivalence Handling:** Reliably resolves cases where two or three numbers are equal through inclusive `>=` comparison.

#### 🖥️ Sample Run:
```text
Enter the first number: 45.8
Enter the second number: 99.2
Enter the third number: 12.4
99.2 is the largest number.
```

---

### P10- Write a Java program to find the largest number among three using nested if..else statement

- **Folder / Question Name:** `P10- Write a Java program to find the largest number among three using nested if..else statement`
- **Class Name:** `LargestAmongThreeNested`
- **Source File:** [`LargestAmongThreeNested.java`](./P10-%20Write%20a%20Java%20program%20to%20find%20the%20largest%20number%20among%20three%20using%20nested%20if..else%20statement/LargestAmongThreeNested.java)

#### 🌟 Key Features:
- **Hierarchical Decision Tree:** Demonstrates nested control flow without using compound boolean operators (`&&`), mirroring formal binary decision trees.
- **Two-Tier Evaluation Logic:**
  - **Outer Tier:** Determines whether `num1 >= num2`.
  - **Inner Tier A (when num1 >= num2):** Compares `num1` against `num3` to select the largest.
  - **Inner Tier B (when num2 > num1):** Compares `num2` against `num3` to select the largest.
- **Algorithmic Efficiency:** Requires at most two comparison steps to determine the maximum value among three candidates.

#### 🖥️ Sample Run:
```text
Enter the first number: 73
Enter the second number: 18
Enter the third number: 89
89.0 is the largest number.
```

---

### P11 - Write a Java program to check whether a Year is a Leap Year

- **Folder / Question Name:** `P11 - Write a Java program to check whether a Year is a Leap Year`
- **Class Name:** `LeapYearChecker`
- **Source File:** [`LeapYearChecker.java`](./P11%20-%20Write%20a%20Java%20program%20to%20check%20whether%20a%20Year%20is%20a%20Leap%20Year/LeapYearChecker.java)

#### 🌟 Key Features:
- **Accurate Gregorian Calendar Implementation:** Applies the full international standard for leap year calculation:
  $$\text{Leap Year} \iff (\text{year} \pmod 4 = 0 \land \text{year} \pmod{100} \neq 0) \lor (\text{year} \pmod{400} = 0)$$
- **Century Year Handling:** Accurately distinguishes non-leap centuries (e.g., 1700, 1800, 1900, 2100) from quad-century leap years (e.g., 1600, 2000, 2400).
- **Concise Conditional Expression:**
  ```java
  if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0))
  ```

#### 🖥️ Sample Run:
```text
Enter a year: 2024
2024 is a leap year.
```

---

### P12 - Write a Java program to Swap two numbers using temporary variable

- **Folder / Question Name:** `P12 - Write a Java program to Swap two numbers using temporary variable`
- **Class Name:** `SwapNumbers`
- **Source File:** [`SwapNumbers.java`](./P12%20-%20Write%20a%20Java%20program%20to%20Swap%20two%20numbers%20using%20temporary%20variable/SwapNumbers.java)

#### 🌟 Key Features:
- **Classic 3-Step Swapping Algorithm:**
  1. Store the first value in an auxiliary variable: `int temp = num1;`
  2. Overwrite the first variable with the second: `num1 = num2;`
  3. Assign the buffered value to the second variable: `num2 = temp;`
- **State Transition Logging:** Displays the values of `num1` and `num2` both before and after the swap to clearly prove the exchange of data.
- **Memory Buffer Concept:** Reinforces fundamental principles of variable reassignment and transient memory buffers.

#### 🖥️ Sample Run:
```text
Enter the first number: 10
Enter the second number: 20
Before swapping: num1 = 10, num2 = 20
After swapping: num1 = 20, num2 = 10
```

---

### Q13 - Write a program in Java to show the working of a class and an object

- **Folder / Question Name:** `Q13 - Write a program in Java to show the working of a class and an object`
- **Class Names:** `Person` (Blueprint Class), `ClassAndObjectExample` (Driver Class)
- **Source File:** [`ClassAndObjectExample.java`](./Q13%20-%20Write%20a%20program%20in%20Java%20to%20show%20the%20working%20of%20a%20class%C2%A0and%C2%A0an%C2%A0object/ClassAndObjectExample.java)

#### 🌟 Key Features:
- **OOP Foundation:** Demonstrates the relationship between a class (blueprint/schema) and an object (concrete instance allocated in memory).
- **Attribute Definition:** Class `Person` defines state variables: `String name` and `int age`.
- **Instance Method Behavior:** Encapsulates behavior inside the `displayDetails()` method.
- **Dynamic Heap Instantiation:** Creates separate instances using the `new` keyword:
  ```java
  Person person1 = new Person();
  Person person2 = new Person();
  ```
- **State Isolation:** Shows that mutating attributes on `person1` (`name = "John"`, `age = 30`) remains completely independent of `person2` (`name = "Alice"`, `age = 25`).

#### 🖥️ Output:
```text
Details of Person 1:
Name: John
Age: 30

Details of Person 2:
Name: Alice
Age: 25
```

---

### Q14 - Write a program in Java to create a student class with 3 variables and 2 methods

- **Folder / Question Name:** `Q14 - Write a program in Java to create a student class with 3 variables and 2 methods`
- **Class Names:** `Student` (Entity Class), `StudentClassExample` (Driver Class)
- **Source File:** [`StudentClassExample.java`](./Q14%20-%20Write%20a%20program%20in%20Java%20to%20create%20a%20student%20class%20with%203%20variables%C2%A0and%C2%A02%C2%A0methods/StudentClassExample.java)

#### 🌟 Key Features:
- **Strict Specification Compliance:** Class `Student` is structured with **exactly 3 variables** and **exactly 2 methods**:
  - **Variables (3 Attributes):**
    1. `String name` — Student's full name.
    2. `int rollNumber` — Institutional roll / identification number.
    3. `double marks` — Academic examination score.
  - **Methods (2 Behaviors):**
    1. `void displayDetails()` — Formats and prints the student profile to the console.
    2. `void calculateGrade()` — Computes and prints the academic grade based on performance benchmarks:
       - $\ge 90 \implies \text{Grade A}$
       - $\ge 80 \implies \text{Grade B}$
       - $\ge 70 \implies \text{Grade C}$
       - $< 70 \implies \text{Grade D}$
- **Interactive Scanner Ingestion:** Demonstrates reading multi-word strings (`nextLine()`), integer primitives (`nextInt()`), and floating-point marks (`nextDouble()`).
- **Encapsulated Business Logic:** Moves grade evaluation logic into a dedicated member method of the object.

#### 🖥️ Sample Run:
```text
Enter student name: Tanim
Enter student roll number: 101
Enter student marks: 92.5
Student Details:
Name: Tanim
Roll Number: 101
Marks: 92.5
Grade: A
```

---

## 🛠️ How to Set Up & Run

### Prerequisites

Ensure you have the Java Development Kit (JDK) installed on your system:
- **JDK 8 or higher** (JDK 11, 17, or 21 LTS recommended).
- Verify your installation by running:
  ```bash
  java -version
  javac -version
  ```

### Clone the Repository

```bash
git clone https://github.com/CodeWithTanim/Java-Practice-2nd-Semester.git
cd Java-Practice-2nd-Semester
```

### Compiling and Running Individual Programs

Because folder names contain spaces, wrap paths in double quotes in your shell or navigate directly into the folder:

#### Method 1: Running from the Repository Root

```bash
# Example: P2 - Hello World
javac "P2 - Write, save, compile, and execute a Helloworld program in Java/HelloWorld.java"
java -cp "P2 - Write, save, compile, and execute a Helloworld program in Java" HelloWorld

# Example: P11 - Leap Year Checker
javac "P11 - Write a Java program to check whether a Year is a Leap Year/LeapYearChecker.java"
java -cp "P11 - Write a Java program to check whether a Year is a Leap Year" LeapYearChecker

# Example: Q14 - Student Class Example
javac "Q14 - Write a program in Java to create a student class with 3 variables and 2 methods/StudentClassExample.java"
java -cp "Q14 - Write a program in Java to create a student class with 3 variables and 2 methods" StudentClassExample
```

#### Method 2: Navigating into the Target Directory

```bash
cd "P3 - Write a Java program to add two integers"
javac AddTwoIntegers.java
java AddTwoIntegers
```

#### Method 3: Using an IDE
You can open this repository directly in any modern Java IDE:
- **Visual Studio Code** (with the *Extension Pack for Java*)
- **IntelliJ IDEA**
- **Eclipse IDE**
- **Apache NetBeans**

---

## 👨‍💻 Author & Connect

**MSR Tanim**  
*Computer Science & Engineering Student | Developer*

Connect and follow along with future projects:

[![GitHub](https://img.shields.io/badge/GitHub-CodeWithTanim-181717?style=flat-square&logo=github)](https://github.com/CodeWithTanim)
[![YouTube](https://img.shields.io/badge/YouTube-CodeWithTanim-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@CodeWithTanim)
[![Facebook](https://img.shields.io/badge/Facebook-msrtanim.py-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://fb.com/msrtanim.py)
[![Instagram](https://img.shields.io/badge/Instagram-msrtanim.py-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/msrtanim.py)
[![X / Twitter](https://img.shields.io/badge/X-@msrtanim__-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/msrtanim_)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/4Y4KUUADMC)
[![CodePen](https://img.shields.io/badge/CodePen-msrtanim-000000?style=flat-square&logo=codepen&logoColor=white)](https://codepen.io/msrtanim)

---

## 📄 License & Academic Disclaimer

This project is created for educational and practice purposes as part of 2nd Semester Java coursework. Feel free to use the code as a study reference, laboratory guide, or template for learning core Java and Object-Oriented Programming concepts.
