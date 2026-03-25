# Quiz-game-python-
A simple interactive quiz game build using python that asks questions and calculates the user's score 

Quiz Game using Python

 Project Description
This is a simple interactive Quiz Game developed using Python.  
The program asks multiple questions and checks the user's answers, then displays the final score.

Features
- Multiple choice questions
- Score calculation
- Instant feedback (correct/wrong)
- Final result display

Technology Used
- Python

 How to Run
1. Download the file
2. Open terminal / command prompt
3. Run the program:
   python quiz_game.py

Sample Output
Welcome to the Quiz Game!
Question 1: ...
Your Answer: ...
Correct!

yogamaya
CCE department 




print("🎮 Welcome to the Quiz Game!")

score = 0

# Question 1
print("\n1. What is the capital of India?")
print("a) Mumbai")
print("b) Delhi")
print("c) Chennai")

ans = input("Enter your answer: ")

if ans.lower() == "b":
    print("✅ Correct!")
    score += 1
else:
    print("❌ Wrong! Correct answer is Delhi")

# Question 2
print("\n2. Which language is used for programming?")
print("a) Python")
print("b) HTML")
print("c) Both")

ans = input("Enter your answer: ")

if ans.lower() == "c":
    print("✅ Correct!")
    score += 1
else:
    print("❌ Wrong! Correct answer is Both")

# Question 3
print("\n3. What is 5 + 3?")
print("a) 5")
print("b) 8")
print("c) 10")

ans = input("Enter your answer: ")

if ans.lower() == "b":
    print("✅ Correct!")
    score += 1
else:
    print("❌ Wrong! Correct answer is 8")

# Final Score
print("\n🎯 Your Final Score:", score, "/ 3")

if score == 3:
    print("🔥 Excellent!")
elif score == 2:
    print("👍 Good job!")
else:
    print("📚 Keep practicing!")

