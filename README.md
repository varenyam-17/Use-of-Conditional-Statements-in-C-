# IF-ELSE-in-c-
Varenyam Singh 24070123126
Aim: To study and implement C++ decision making statements
Theory:Decision-making statements allow a program to take different actions based on different conditions. They’re essential for adding logic and control to the program flow. In C++, the main decision-making statements are:
🔹 if Statement
- Executes a block of code only if a specified condition is true.
if (x > 0) {
    cout << "Positive number";
}
🔹 if-else Statement
- Executes one block if the condition is true, and another if false.
if (x > 0) {
    cout << "Positive";
} else {
    cout << "Non-positive";
}
🔹 else if Ladder
- Checks multiple conditions in sequence.
if (x > 0) {
    cout << "Positive";
} else if (x < 0) {
    cout << "Negative";
} else {
    cout << "Zero";
}
🔹 switch Statement
- Used for checking a variable against multiple constant values. Best for menu-driven programs.
switch (choice) {
    case 1: cout << "Option 1"; break;
    case 2: cout << "Option 2"; break;
    default: cout << "Invalid";
}
🔹 Conditional/Ternary Operator ? :
- Shorthand for simple if-else operations.
string result = (x > 0) ? "Positive" : "Non-positive";
These constructs form the backbone of decision-making in programming and are key to implementing control structures in practical applications.
  ALGORITHMS:
 1. Even or Odd~>
  - Start
- Input a number n
- Check condition:
- If n % 2 == 0, then
→ Display “Even number”
- Else
→ Display “Odd number”
- End
2.Vowel or Consonant~>
  - Start
- Input a character ch
- Convert ch to lowercase (if needed)
- Check condition:
- If ch is 'a', 'e', 'i', 'o', or 'u' →
→ Display “Vowel”
- Else if ch is an alphabet character →
→ Display “Consonant”
- Else →
→ Display “Not an alphabet character”
- End
3.To find the Greatest Number among Three Numbers~>
  - Start
- Input three numbers: a, b, and c
- Check conditions:
- If a ≥ b and a ≥ c →
→ Display “a is the greatest”
- Else if b ≥ a and b ≥ c →
→ Display “b is the greatest”
- Else →
→ Display “c is the greatest”
- End
 Conclusion
Understanding and implementing decision-making statements in C++ is fundamental for writing logical and interactive programs. By mastering structures like if, else if, and switch, programmers can guide program execution based on dynamic input and real-world conditions. This leads to more efficient, user-friendly, and adaptable software solutions. Practical application of these statements enhances problem-solving skills and deepens your grasp of algorithmic thinking.



