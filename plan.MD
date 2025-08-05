---
# 💻 Java Programming Fundamentals: What to Learn & What to Build

*A step-by-step guide for beginners focused on building progressively more advanced terminal applications in Java.*

> 🚨 This guide does **not** teach you how to code — it shows you **what to learn** and **what to build** at each step of your journey.

---

## 🧱 Section 1: Setup & Your First Program

**🔍 Concepts Covered**: Tools, compiling & running Java, code structure

### ✅ What to Learn:

* What is Java? (JVM, JDK, JRE)
* How to install the JDK
* Using an IDE like **IntelliJ IDEA**
* Creating your first Java project
* Understanding `.java` files and the `main` method
* Running and debugging a simple Java program

### 💡 Projects:

1. **Hello World**

   * Print "Hello, World!" to the terminal.
   * Modify to include your name or a fun greeting.

2. **Personal Introduction Card**

   * Print your name, favorite hobby, favorite food, etc., using `System.out.println()`.

3. **ASCII Art Display**

   * Use characters like `*`, `@`, `#`, and `-` to draw a triangle, heart, or banner in the console.

---

## ✍️ Section 2: Printing & Output Formatting

**🔍 Concepts Covered**: Output, escaping characters, formatting text

### ✅ What to Learn:

* How `System.out.println()` works
* Newlines `\n`, tabs `\t`, quotes `\"`
* Writing multiple print statements for structured output

### 💡 Projects:

1. **ASCII Art Scenes**

   * Draw a house, robot, or cat using multiple print lines.

2. **Mini Resume**

   * Output a formatted resume with your name, skills, education, etc.

3. **Birthday Card Generator**

   * Print a fun birthday message with ASCII decorations and your name.

---

## 🧮 Section 3: Variables & Basic Data Types

**🔍 Concepts Covered**: `int`, `double`, `String`, `boolean`, variable declaration & use

### ✅ What to Learn:

* Storing values using variables
* Choosing the right data type
* Reassigning values
* Printing variables in sentences

### 💡 Projects:

1. **Mad Libs Game**

   * Create a fill-in-the-blank story using `String`, `int`, and `boolean` variables.

2. **Fun Fact Generator**

   * Combine facts and variables to generate fun output like “Did you know the Earth is round? true!”

3. **Height Converter**

   * Store a height in inches and convert to feet and inches using `int` and `double`.

4. **Name Card Generator**

   * Create a fake ID card or event badge using user-provided variables.

---

## ➕ Section 4: Operators

**🔍 Concepts Covered**: Arithmetic, comparison, and logical operators

### ✅ What to Learn:

* `+`, `-`, `*`, `/`, `%`
* `==`, `!=`, `>`, `<`, `>=`, `<=`
* `&&`, `||`, `!` (logic with booleans)
* Mixing `String` and numbers with `+`

### 💡 Projects:

1. **Tip Calculator**

   * Input bill total and tip %, calculate and print the final total.

2. **Tax Calculator**

   * Add tax to user-entered amounts and print the total.

3. **Basic Math Tool**

   * Ask for two numbers and show results for all 5 operations.

4. **Age in Days**

   * Convert user’s age into days, weeks, and months.

---

## 🧠 Section 5: Control Flow (if / else)

**🔍 Concepts Covered**: Making decisions with `if`, `else if`, `else`

### ✅ What to Learn:

* Write simple if/else statements
* Use conditions to control what prints
* Combine logic with `&&`, `||`
* Nest conditionals

### 💡 Projects:

1. **Pass/Fail Checker**

   * Input a test score and print "Pass" or "Fail".

2. **Movie Ticket Price Calculator**

   * Calculate price based on age (child, adult, senior).

3. **Simple Login System**

   * Hard-code a username and password; validate user input.

4. **Even or Odd Checker**

   * Input a number and print whether it’s even or odd.

5. **Weather Advice Bot**

   * Ask if it’s raining and cold, then suggest what to wear.

---

## 🔁 Section 6: Loops (for / while)

**🔍 Concepts Covered**: Repeating tasks using `for` and `while` loops

### ✅ What to Learn:

* Count up or down with `for` loops
* Run loops until a condition is false (`while`)
* Use loops for repetitive tasks
* Avoid infinite loops

### 💡 Projects:

1. **Multiplication Table Generator**

   * Ask for a number and print its table from 1 to 10.

2. **Countdown App**

   * Count down from any number to 0.

3. **Pattern Printer**

   * Use loops to print number or star patterns (e.g., triangle of `*`).

4. **Number Guessing Game (static)**

   * Hard-code a number and let the user guess until correct.

5. **Simple Menu System**

   * Let the user choose options from a menu until they quit.

---

## 🎤 Section 7: User Input with `Scanner`

**🔍 Concepts Covered**: Interacting with the user through typed input

### ✅ What to Learn:

* Import and use `Scanner`
* `nextLine()`, `nextInt()`, `nextDouble()`
* Reading multiple values
* Handling string/number mixing

### 💡 Projects:

1. **Interactive Quiz Game**

   * Ask multiple questions and track the user’s score.

2. **Custom Story Generator**

   * Ask user for name, age, animal, etc., and generate a silly story.

3. **ATM Simulator (Basic)**

   * Let the user “deposit” and “withdraw” from a fake account.

4. **Unit Converter**

   * Convert inches to centimeters, or Fahrenheit to Celsius.

5. **Restaurant Order Flow**

   * Show a menu, take order input, calculate total with tax.

---

## 🧠 Optional: Combine Concepts for Mini Games & Advanced Projects

Once you’ve covered Sections 1–7, you’re ready for some **bigger projects** that bring everything together:

### 🎮 Mini Games:

* **Rock Paper Scissors**
  Use random number generation and conditionals to play against the computer.

* **Dice Rolling Game**
  Roll a virtual die and let the user guess the result.

* **Quiz Game with Scoring**
  Add points, track score, give feedback.

* **Number Guessing Game with Random Number**
  Use `Random` to generate a secret number.

### 🍔 Real-World Simulations:

* **Restaurant Order System**
  Display menu, take multiple item orders, calculate subtotal and tax.

* **Basic Banking App**
  Track a balance, allow deposit/withdrawal, show balance.

* **Simple Calendar Tool**
  Let users input tasks or events and display them.

---

## ✅ Summary Table

| Section         | Focus            | Example Projects                  |
| --------------- | ---------------- | --------------------------------- |
| 1. Setup        | Java + IDE       | Hello World, ASCII name card      |
| 2. Output       | Print statements | Resume, ASCII art                 |
| 3. Variables    | Data types       | Mad Libs, Fun Facts               |
| 4. Operators    | Math & logic     | Tip calculator, age in days       |
| 5. Control Flow | `if / else`      | Pass/fail checker, login system   |
| 6. Loops        | Repetition       | Multiplication table, menu system |
| 7. Input        | `Scanner`        | Quiz game, unit converter         |

---

## 🌱 Intermediate Fundamentals

This section introduces essential concepts that take you beyond the basics — reusable **methods**, powerful **data structures** like **lists** and **maps**, and how to combine them to build more interesting and modular terminal applications.

---

### 🔧 1. Methods – Reusability and Clean Code

**Goal:** Learn to create and use your own methods to avoid repetition, organize code, and build more readable programs.

#### 🧠 Key Concepts:

* Defining a method: `public static void greet() { ... }`
* Parameters and arguments
* Return values: `public static int add(int a, int b)`
* Method overloading (optional for later)
* Method calling: `greet();`

#### 💡 Projects:

* **Greeting Generator**: Create a method `greet(name)` that prints a personalized greeting.
* **Simple Calculator**: Create `add()`, `subtract()`, `multiply()`, `divide()` methods and call them based on user input.
* **Tip Calculator Refactor**: Take your previous tip calculator and break it into input, calculation, and output methods.
* **Even/Odd Checker**: Method that takes an integer and prints if it's even or odd.
* **Basic Unit Converter**: Write methods for `cmToInches`, `fahrenheitToCelsius`, `poundsToKg`, etc.

---

### 📋 2. Lists – Managing Collections of Data

**Goal:** Learn how to store, loop through, and manage collections of items using Lists (specifically `ArrayList`).

#### 🧠 Key Concepts:

* Importing and declaring: `ArrayList<String> items = new ArrayList<>();`
* Adding/removing items: `add()`, `remove()`
* Accessing items: `get(index)`, `set(index, value)`
* Looping through lists
* `.size()` method
* Searching within a list

#### 💡 Projects:

* **To-Do List App**: Let the user add, view, and remove tasks from a list.
* **Grocery List Tracker**: Similar to To-Do but with quantities and prices. You could add total cost later.
* **Simple Quiz App**: Store questions and check answers using lists.
* **Movie Watchlist**: Add/remove/display movies, maybe with a `markAsWatched()` function.
* **Vocab Builder**: Store new vocabulary words and quiz the user.

---

### 🗺️ 3. Maps – Associating Keys with Values

**Goal:** Learn how to associate keys with values (like a dictionary) using `HashMap`.

#### 🧠 Key Concepts:

* Importing and declaring: `HashMap<String, Integer> scores = new HashMap<>();`
* Putting values: `put(key, value)`
* Getting values: `get(key)`
* Checking keys/values: `containsKey()`, `containsValue()`
* Removing entries: `remove(key)`
* Iterating through entries

#### 💡 Projects:

* **Phone Book App**: Store names as keys and phone numbers as values.
* **Word Counter**: Count occurrences of each word in a sentence.
* **Student Gradebook**: Map student names to letter grades or GPA.
* **Currency Converter**: Map currency codes to conversion rates.
* **Restaurant Menu App**: Map item names to prices; let the user place orders and calculate total.

---

### 🧩 Project Ideas That Combine All of the Above

These ideas require methods, lists, and maps working together:

* **Rock, Paper, Scissors (vs Computer)**: Use methods for logic, and lists/maps to manage choices.
* **Dice Guessing Game**: Use random numbers and user input, refactor with methods.
* **Text-Based RPG Inventory System**: Use a map for item names and quantities, and a list to store equipped items.
* **Restaurant Ordering System**: Show a menu (map), let user pick items (list), and print receipt with totals (method).
* **Flashcard App**: Map questions to answers, use methods to quiz, use lists to track incorrect ones for review.

---

## 🔷 Section: Advanced Fundamentals – Mastering Object-Oriented Programming

### 🎯 Learning Goals:

* Understand and use **Classes**, **Objects**, and **Constructors**
* Learn and apply **Encapsulation**, **Abstraction**, **Inheritance**, and **Polymorphism**
* Design small systems with interacting objects
* Refactor procedural code into object-oriented structures

---

### 🧱 Topics & Concepts:

1. **Classes and Objects**

   * What is a class?
   * Instantiating objects
   * Fields and methods in classes
   * Constructors (default and parameterized)

2. **Encapsulation**

   * Access modifiers: `private`, `public`, `protected`
   * Getters and setters

3. **`this` keyword**

   * Referencing the current instance
   * Constructor chaining using `this(...)`

4. **Static vs Instance Members**

   * Static fields and methods
   * Class-level vs instance-level logic

5. **Composition**

   * Objects within objects (has-a relationships)
   * Building complex structures with simpler classes

6. **Inheritance**

   * `extends` keyword
   * Superclasses and subclasses
   * The `super` keyword
   * Method overriding

7. **Polymorphism**

   * Method overloading
   * Method overriding
   * Upcasting and dynamic method dispatch

8. **Abstract Classes & Interfaces**

   * `abstract` keyword
   * Interface vs abstract class
   * Implementing multiple interfaces
   * Java's approach to multiple inheritance

9. **Access Control and Packages**

   * Package-private visibility
   * Organizing files into packages
   * `import` statements

10. **Best Practices**

    * Clean code in OOP
    * SRP (Single Responsibility Principle)
    * Cohesion and coupling
    * DRY principle

---

### 🧪 Hands-On Projects:

#### 🔹 1. **`Book` & `Library` System**

* Create a `Book` class with fields like `title`, `author`, and `ISBN`.
* Build a `Library` class that contains a list of `Book`s and methods to:

  * Add a book
  * Remove a book
  * Search by title or author
* Practice encapsulation and composition.

#### 🔹 2. **`Student` and `Course` Enrollment System**

* Model a `Student` class and a `Course` class.
* Each course keeps a list of enrolled students.
* Each student keeps a list of enrolled courses.
* Demonstrates many-to-many relationships.

#### 🔹 3. **`Shape` Drawing App (Inheritance & Polymorphism)**

* Create an abstract class `Shape` with method `draw()`.
* Create subclasses `Circle`, `Rectangle`, `Triangle`.
* Have a method that takes a list of shapes and calls `draw()` on each.
* Learn dynamic dispatch and polymorphism.

#### 🔹 4. **`Zoo` Management Simulator**

* Classes: `Animal` (base), `Bird`, `Mammal`, `Reptile` (inherited)
* Interface: `Flyable`, `Swimmable`
* Encapsulation: each animal has a diet, cage number, etc.
* Add features like feeding animals or tracking their behavior.

#### 🔹 5. **Restaurant Menu Ordering System (OOP version)**

* Build on the earlier procedural menu project.
* Use classes: `MenuItem`, `Order`, `Restaurant`
* Add pricing, ordering multiple items, calculating totals.

---

### 💡 Suggested Practice Challenges:

* Create a `BankAccount` class with deposit, withdraw, and balance methods.
* Build a `Deck` and `Card` class and simulate shuffling and drawing cards.
* Create a `TaskManager` app with `Task` and `Project` classes.
* Model a `ChatApp` with `User`, `Message`, and `Group` classes.

