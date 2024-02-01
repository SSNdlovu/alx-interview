UTF-8 Validation Project
This project, part of the ALX curriculum, focuses on implementing a Python algorithm to determine the validity of a given data set representing a UTF-8 encoding. The task involves writing a method, validUTF8(data), which returns True if the data is a valid UTF-8 encoding and False otherwise.

Project Details
Algorithm: Python
Author: Carrie Ybay, Software Engineer at Holberton School
Weight: 1
Project Start: Jan 29, 2024, 6:00 AM
Project End: Feb 2, 2024, 6:00 AM
Checker Release: Jan 30, 2024, 6:00 AM
Auto Review Launch: At the deadline
Task Overview
A character in UTF-8 can be 1 to 4 bytes long.
The data set can contain multiple characters.
The data is represented by a list of integers.
Each integer represents 1 byte of data, and only the 8 least significant bits need handling.
Example Usage
python
Copy code
data = [65]
print(validUTF8(data))  # Output: True

data = [80, 121, 116, 104, 111, 110, 32, 105, 115, 32, 99, 111, 111, 108, 33]
print(validUTF8(data))  # Output: True

data = [229, 65, 127, 256]
print(validUTF8(data))  # Output: False
Repository Information
GitHub Repository: alx-interview
Directory: 0x04-utf8_validation
File: 0-validate_utf8.py
Copyright Information
Copyright © 2024 ALX, All rights reserved.
