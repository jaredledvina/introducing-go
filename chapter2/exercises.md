# Exercises:
1. How are integers stored on a computer?
    Integers are stored in the binary format. Starting at 000, 001, 010, 011, 100, etc. 

2. We know that (in base 10) the largest one-digit number is 9 and the largest two-digit number is 99. Given that in binary the largest two-digit number is 11 (3), the largest three-digit number is 111 (7) and the largest four-digit number is 1111 (15), what’s the largest eight-digit number? (Hint: 101−1 = 9 and 102−1 = 99)
    The largest base 10 8 digit number is 99999999. The 8 digit binary number, 11111111 = 255.

3. Although overpowered for the task, you can use Go as a calculator. Write a program that computes 32,132 × 42,452 and prints it to the terminal (use the * operator for multiplication).
    See exercise_3.go

4. What is a string? How do you find its length?
    A string is a type that has a definite length, represents text, and is made up of individual bytes for each character.
    Use `len("String goes here")`

5. What’s the value of the expression (true && false) || (false && true) || !(false && false)?
   true
