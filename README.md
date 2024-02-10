# BMI Calculator

This is a simple C program that calculates the Body Mass Index (BMI) based on the user's weight and height input.

# How to Use
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
     

# License

This project is licensed under the MIT License. 

