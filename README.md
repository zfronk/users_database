# User Management System (C)

This is a simple C program that manages user details by storing usernames and passwords in a file (`user_details.txt`). It allows users to create an account and saves their credentials securely.

## Features
- ✅ Creates a `user_details.txt` file if it doesn’t exist.
- ✅ Prompts users to enter a username and password.
- ✅ Saves user credentials to a file in `username: password` format.

## How It Works
1. **File Handling:**  
   - Uses `fopen("user_details.txt", "a+")` to create or open the file in append mode.  
2. **Memory Management:**  
   - Dynamically allocates memory for user input.  
3. **Input Handling:**  
   - Ensures that empty input isn’t accepted.  
   - Removes newline characters from `fgets()`.  
4. **Storage:**  
   - Saves user data to `user_details.txt` in `username: password` format.  

## Installation & Usage
### 1. Compile the program
```sh
gcc user_file.c -o run.exe
