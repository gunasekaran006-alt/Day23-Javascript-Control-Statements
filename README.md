# JavaScript Control Statements Practice

This repository contains fundamental concepts and practical examples of **JavaScript Control Flow**. It is designed to help beginners and interview aspirants understand how to manage logic and data iterations in JS.

## 🚀 Topics Covered

### 1. Conditional Statements
- **If...Else & Else If:** Basic decision-making based on age and marks.
- **Nested If:** Optimized grade checking logic (Interview-focused).
- **Switch Case:** Efficient multi-way branching (e.g., Day of the week).
- **Logical Operators:** Implementation of `&&` (AND) for user authentication scenarios.

### 2. Looping Statements
- **For Loop:** Standard iteration with initialization, condition, and increment.
- **While Loop:** Entry-controlled loops.
- **Do-While Loop:** Exit-controlled loops (ensures the code runs at least once).

## 💡 Industry Scenarios Included
- **Grading System:** Multi-level condition checking.
- **User Authentication:** Validating credentials using logical operators (Login simulation).

## 🛠️ How to Run
1. Clone this repository.
2. Open `index.html` in any modern web browser.
3. Open the **Browser Console** (Right-click > Inspect > Console) to see the output.

## 📝 Code Snippet Example
```javascript
// Example of a nested condition for grading
if(score >= 50) {
    if(score >= 90) console.log("Grade A");
    else if(score >= 75) console.log("Grade B");
    else console.log("Grade C");
} else {
    console.log("Fail");
}