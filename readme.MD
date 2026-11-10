# Python Fundamentals

## Project Description

This project demonstrates basic Python programming concepts through five small programs. Each program focuses on user input, data validation, calculations, string manipulation, and exception handling.

## Programs Included

### 1. Circle Area Calculator
- File: `circle_area.py`
- Requests a circle's radius.
- Validates that the radius is a number and is not negative.
- Calculates area using the formula: π × radius².

### 2. Temperature Converter
- File: `temperature_converter.py`
- Accepts a temperature in Celsius.
- Converts Celsius to Fahrenheit using the formula: (Celsius × 9/5) + 32.
- Demonstrates uppercase formatting and word counting.

### 3. Simple Interest Calculator
- File: `simple_interest.py`
- Requests principal, interest rate, and time.
- Calculates simple interest using: (Principal × Rate × Time) / 100.
- Displays the interest and total amount.

### 4. First Ten U.S. Presidents
- File: `presidents_list.py`
- Stores the first ten U.S. presidents and their presidential terms.
- Uses both a for loop and a while loop to display the information.
- Adds an asterisk to names with a last name beginning with A.
- Demonstrates string searching and list processing.

### 5. String Analyzer
- File: `string_analyzer.py`
- Accepts a sentence from the user.
- Demonstrates uppercase, lowercase, reversing, slicing, and searching.
- Counts words and characters.
- Checks whether the sentence is a palindrome.

## How to Run the Programs

Requirements:
- Python 3.x
- No additional packages are required.

Open a terminal in the project folder and run each program separately:

```bash
python circle_area.py
python temperature_converter.py
python simple_interest.py
python presidents_list.py
python string_analyzer.py
```

On some Windows computers, you may need to use `py` instead of `python`.

## Input Validation and Exception Handling

The programs use `try/except` blocks to handle invalid numeric input. They also check for negative values, empty text, and other invalid entries where appropriate.

When the user enters invalid information, the program displays a helpful message and allows the user to try again.

## Testing Evidence

The following manual tests should be performed:

| Program | Test Input | Expected Result |
|---|---|---|
| Circle Area | Radius: 5 | Area approximately 78.54 |
| Circle Area | Radius: -3 | Displays an error and asks again |
| Circle Area | Radius: abc | Displays an invalid-input message |
| Temperature | Celsius: 0 | Fahrenheit: 32.00 |
| Temperature | Celsius: abc | Displays an invalid-input message |
| Simple Interest | Principal: 1000, Rate: 5, Time: 2 | Interest: $100.00 |
| Simple Interest | Principal: -100 | Displays an error and asks again |
| Presidents | Run program | Displays all ten presidents twice |
| String Analyzer | Enter an empty sentence | Requests a sentence again |
| String Analyzer | Enter "Racecar" | Identifies it as a palindrome |

## Assumptions

- Circle radius cannot be negative.
- Principal and time must be greater than zero.
- Interest rate may be zero or greater.
- Temperature values may be positive or negative.
- The presidents program uses the historical years each president served. William Henry Harrison's term is listed as 1841 because he died in office that year.
- The string analyzer accepts sentences between 1 and 200 characters.

## Conclusion

This project helped me practice Python input handling, calculations, string manipulation, loops, conditional statements, and exception handling. It also demonstrated why validating user input is important when building reliable programs.
