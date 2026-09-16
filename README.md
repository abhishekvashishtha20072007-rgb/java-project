Online Quiz Application – Java

A desktop-based Online Quiz Application developed using Core Java and Java Swing.
The application allows a student to enter their name, answer Java multiple-choice questions, complete each question within a fixed time, and view the final score and grade.

Project Features

Student name/login screen

Simple and user-friendly Swing GUI

20 Java MCQ questions in the question bank

15 questions are randomly selected for each quiz

4 options for every question

30-second timer for each question

Automatic answer checking

Automatic score calculation

Percentage calculation

Grade calculation

Quiz restart option

Exit option

Randomized questions for every new quiz

Technologies Used

Programming Language: Java

GUI: Java Swing

JDK: Java 8 or newer

IDE: VS Code / IntelliJ IDEA / Eclipse / NetBeans

Project Structure

OnlineQuizApplication/
│
├── Main.java
├── Question.java
├── QuizManager.java
├── LoginFrame.java
├── QuizFrame.java
├── ResultFrame.java
└── README.md

Description of Files

1. Main.java

The starting point of the application. It launches the login window using Swing.

2. Question.java

Represents a quiz question. It stores:

Question text

Four answer options

Correct answer

3. QuizManager.java

Stores the Java MCQ question bank and randomly shuffles the questions before each quiz.

4. LoginFrame.java

Creates the initial GUI where the student enters their name and starts the quiz.

5. QuizFrame.java

Displays:

Current question

Four answer options

Question number

30-second countdown timer

Next/Submit button

It also checks answers and maintains the score.

6. ResultFrame.java

Displays the final:

Student name

Score

Percentage

Grade

Restart Quiz button

Exit button

How the Application Works

Start Application
       ↓
Enter Student Name
       ↓
Start Quiz
       ↓
Random Questions Selected
       ↓
Display Question + 4 Options
       ↓
30-Second Timer
       ↓
Check Answer
       ↓
Next Question
       ↓
All Questions Completed
       ↓
Calculate Score & Percentage
       ↓
Display Result & Grade

Grading System

Percentage

Grade

90% – 100%

A+

80% – 89%

A

70% – 79%

B

60% – 69%

C

50% – 59%

D

Below 50%

F

Requirements

Before running the project, make sure Java is installed.

Check Java version:

java -version

Check Java compiler:

javac -version

Java 8 or newer is recommended.

How to Run in VS Code

Extract the project ZIP.

Open VS Code.

Select File → Open Folder.

Open the OnlineQuizApplication folder.

Install Extension Pack for Java if Java support is not already installed.

Open Main.java.

Click the Run ▶ button.

Run Using Terminal

Open the VS Code terminal inside the project folder and execute:

javac *.java
java Main

The Online Quiz Application GUI will open automatically.

OOP Concepts Used

This project demonstrates important Java concepts:

Classes and Objects

Encapsulation

Constructors

Methods

ArrayList

Inheritance

Event Handling

GUI Programming

Exception-safe input validation

Quiz Rules

Enter your name before starting.

Each quiz contains 15 questions.

Each question has 4 options.

You get 30 seconds for each question.

A correct answer increases the score by 1.

An unanswered question receives 0 marks.

After the last question, the final result is displayed.

You can restart the quiz or exit the application.

Future Enhancements

The project can be extended with:

Login using username and password

Multiple categories such as Python, C++, and General Knowledge

Database connectivity using MySQL

High-score/leaderboard system

Admin panel for adding questions

Sound effects

Difficulty levels

Negative marking

Certificate generation

Detailed answer review

Author

Student Project – Java

License

This project is created for educational and academic purposes.
