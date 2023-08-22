# Flow Control Java Project

This Java project, named "Flow Control," is a simple program that takes two integer parameters and calculates the count of numbers between them, displaying the range and the total count of iterations.

## Introduction
The "Flow Control" program reads two integer parameters and calculates the count of numbers that lie between them. It showcases fundamental input reading, exception handling, and basic loop concepts in Java.

## Usage
1. The program prompts the user to input two integer parameters.
2. It validates that the inputs are valid integer numbers. If not, the program will display an error message and prompt again for valid inputs.
3. It calculates and displays the count of numbers between the provided parameters.
4. The program also indicates the range of numbers that were considered for counting.

## Exception Handling
The program employs custom exception handling. If the second parameter provided is smaller than the first parameter, an "InvalidParametersException" is thrown, signifying that the second parameter must be greater than the first.

## How to Run
1. Compile the Java program using the following command:
   ```
   javac Counter.java
   ```

2. Execute the compiled program using:
   ```
   java Counter
   ```

3. Follow the prompts to enter two integer parameters. The program will then validate the inputs, calculate and display the count of numbers between these parameters, and provide the range of numbers considered.

Please note that this program assumes valid integer inputs. If an invalid input (non-integer) is provided, the program will display an error message and prompt for a valid input. Additionally, ensure that Java is installed on your system before running the program.

Feel free to modify the parameter values and observe the program's output to explore different ranges and counts.

## License
This project is licensed under the MIT License.
