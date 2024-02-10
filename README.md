# BMI Calculator

This is a simple C program that calculates the Body Mass Index (BMI) based on the user's weight and height input.

# Prerequisite
  - **C Compiler**: You need a C compiler installed on your system to compile and execute the program. One commonly used compiler is GCC (GNU Compiler Collection), which is available for various operating systems. If you don't have GCC installed, you can download it       from [gcc.gnu.org](https://gcc.gnu.org/).
  - **Development Environment**: You can write and edit the program code using any text editor or integrated development environment (IDE) that supports C programming. Some popular options include Visual Studio Code, Atom, Sublime Text, and Eclipse CDT.
  - **Basic Understanding of C Programming**: This program assumes basic knowledge of the C programming language. You should be familiar with concepts such as variables, data types, input/output, arithmetic operations, and conditional statements.
  -  **Terminal or Command Prompt**: You'll need access to a terminal or command prompt to compile and execute the program. This is where you'll run commands to compile the source code and execute the compiled program.

# Getting Stared
  - **Compile the Program**: Compile the program using a C compiler.
  - **Run the Program**: Execute the compiled program.
  - **Enter Your Information**: Follow the prompts to enter your weight in kilograms and your height in meters.
  - **View the Result**: The program will calculate your BMI and display the result along with a message indicating your weight status (underweight, normal weight, overweight, or obese).

# Program Logic

1. **Initialization**:
   - The program initializes variables `weight`, `height`, and `bmi` of type float to store user input and calculated BMI.

2. **Input**:
   - The program prompts the user to enter their weight in kilograms and their height in meters using `printf()` statements.
   - User inputs for weight and height are read using `scanf()` and stored in the variables `weight` and `height`, respectively.

3. **BMI Calculation**:
   - The program calculates the BMI using the formula: BMI = weight / (height * height).
   - The calculated BMI is stored in the variable `bmi`.

4. **Output**:
   - The program displays the calculated BMI using `printf()` with formatting to show two decimal places.
   - Conditional statements (`if-else`) determine the weight status based on the BMI:
     - If BMI is less than 18.5, it indicates the user is underweight.
     - If BMI is between 18.5 and 24.9 (inclusive), it indicates the user is in the normal weight range.
     - If BMI is between 25 and 29.9 (inclusive), it indicates the user is overweight.
     - If BMI is 30 or greater, it indicates the user is obese.

5. **Return**:
   - The program exits with a return value of 0, indicating successful execution.

# Reference

This program was developed based on the concepts learned in college. It applies fundamental principles of programming, including:

- Input/output handling using `printf()` and `scanf()` functions for user interaction.
- Variable declaration and initialization to store data.
- Arithmetic operations for calculations, such as BMI calculation using the formula: BMI = weight / (height * height).
- Conditional statements (`if-else`) to make decisions based on calculated values.
- Compilation and execution of C programs using a C compiler, such as GCC.

The development of this program was guided by the knowledge and skills acquired during the study of course(Logic building with c) in college.

     

# License

This project is licensed under the MIT License. 

