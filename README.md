# bonus-project-

📌 Description

A simple C++ console application that generates random math quiz questions.
The player answers arithmetic problems, and the program checks if the answers are correct or wrong, then displays the final score and pass/fail result.

🚀 Features

Supports 4 difficulty levels: Easy, Medium, Hard, Mixed.

Supports 5 operation types: Addition (+), Subtraction (-), Multiplication (×), Division (÷), Mixed.

Generates random questions using rand().

Provides instant feedback (Correct/Wrong).

Shows final results (number of correct and wrong answers, pass/fail).


🛠️ How It Works

The program generates a list of math questions.

The user answers each question through the console.

After answering all questions, the program displays:

✅ Number of correct answers

❌ Number of wrong answers

🎯 Whether the user passed or failed

📂 Project Structure
MathQuizGame/
│-- main.cpp       # Main source code
│-- README.md      # Documentation

🖥️ Example Run
Question [1/5]
8 + 7 = 15
Correct!

Question [2/5]
12 x 3 = 36
Correct!

Question [3/5]
20 / 5 = 6
Wrong! Correct Answer: 4

Quiz Completed! Right Answers: 2, Wrong Answers: 1
You Passed the Quiz!

🔧 How to Compile & Run
On Linux / macOS:
g++ main.cpp -o MathQuizGame
./MathQuizGame

On Windows (MinGW):
g++ main.cpp -o MathQuizGame.exe
MathQuizGame.exe

🎯 Future Improvements

Allow user to choose difficulty level.

Allow user to set number of questions.

Add score percentage and grading system.

Store results in a file (e.g., results.txt).

👨‍💻 Author

Created by Beltagy 