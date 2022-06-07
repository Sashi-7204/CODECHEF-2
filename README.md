# Activity-2 
* **This Activity is used to Check passwords, Phone Numbers and URL's.**
* *To Check the validity Password*
1. The first line of the code checks if the length of the password is less than 8. If it is, the program prints an error message and continues to the next iteration of the loop.
2. If the length is not less than 8, the program checks if the password contains at least one lowercase letter. If it does not, it prints an error message and continues to the next iteration of the loop.
3. If the password does not contain at least one lowercase letter, the program checks if it contains at least one uppercase letter. If it does not, it prints an error message and continues to the next iteration of the loop.
4. If the password does not contain at least one uppercase letter, the program checks if it contains at least one number. If it does not, it prints an error message and continues to the next iteration of the loop.
5. If the password does not contain at least one number, the program checks if it contains at least one of the symbols _, @, or $. If it does not, it prints an error message and continues to the next iteration of the loop.
6. If the password contains any of the symbols _, @, or $, the program checks if it contains any spaces. If it does, the program prints an error message and continues to the next iteration of the loop.
7. If the password does not contain any spaces, the program prints a success message and breaks out of the loop.
* *To Check the validity Phone Number*
1. We first ask the user to enter a country code.
2. We then check if the country code is valid or not.
3. If the country code is not valid, we ask the user to enter a valid country code.
4. If the country code is valid, we ask the user to enter a mobile number.
5. If the mobile number is valid, we print the mobile number as valid.
6. If the mobile number is not valid, we print the mobile number as invalid.
* *To Check the validity of an URL*
1. The re_exp variable holds the regular expression for URL.
2. The exp variable holds the compiled regular expression.
3. The input string is stored in the ip_url variable.
4. The re.search() method returns a match object if the expression is found in the string.
5. If the match object is not empty, the URL is valid.
6. If the match object is empty, the URL is invalid.
