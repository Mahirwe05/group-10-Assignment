
# 🐍 Python Assignment Report
## ✍️ Collaborators
Name:
MUGIRANEZA Eugene  27580

INEZA Tania Horline 25797

MUCYO Kevin 22609

MUTSINZI Brian Heritier 26522

AKIMANA Janviere 26769

MAHIRWE Yvette 26510

## 📄 Overview

This assignment involves two simple but important Python programs that demonstrate core programming concepts:

* **Question 2**: Checks whether a user-entered string is a palindrome.
* **Question 3**: Combines two user-entered strings, breaks the combined result into characters, and displays them clearly.

---

## ✅ Question 2: Palindrome Checker

### 🔍 Description

A **palindrome** is a word or phrase that reads the same forward and backward (e.g., "madam", "racecar"). This program allows the user to input a string and checks whether it is a palindrome using Python string slicing.

### 💡 Features

* Takes user input using `input()`
* Uses slicing `text[::-1]` to reverse the string
* Compares original and reversed strings
* Prints a clear result
```python
def check_palindrome():
    text = input("Enter a string to check if it's a palindrome: ")
    if text == text[::-1]:
        print("Yes, it is a palindrome.")
    else:
        print("No, it is not a palindrome.")

check_palindrome()
```

### 🧾 Sample Output
![Pal](https://github.com/user-attachments/assets/feeb9042-9efc-4020-9558-5968e5c3ec49)


## ✅ Question 3: String Combiner and Character Lister

### 🔍 Description

This program asks the user for **two input strings**, combines them into one, and then:

* Displays the combined result
* Breaks it into individual characters
* Displays the list of characters

### 💡 Features

* User input for two strings
* String concatenation
* Character iteration using a list comprehension
* Organized output showing both the full string and character list

  ```python
  def combine_and_iterate(text1, text2):
    combined = text1 + text2
    char_list = [char for char in combined]
    return combined, char_list  
text1 = input("Enter the first text: ")
text2 = input("Enter the second text: ")

combined, result = combine_and_iterate(text1, text2)
print("Combined text:", combined)
print("List of characters from combined text:", result)
print("Thank you for using my application \nAfter processing the input.")
 ```

### 🧾 Sample Output

![CON](https://github.com/user-attachments/assets/82699b4c-9461-416d-a8b2-186cf6a69e6d)


## 🧠 Concepts Covered

* String input and manipulation
* Conditional statements (`if-else`)
* String slicing (`[::-1]`)
* Functions and return values
* List comprehensions
* Clean console output formatting

---






---


