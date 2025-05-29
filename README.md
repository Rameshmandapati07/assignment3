Task 1:
def factorial(n):
    if n < 0:
        return "Factorial is not defined for negative numbers."
    elif n == 0 or n == 1:
        return 1
    else:
        result = 1
        for i in range(2, n + 1):
            result *= i
        return result
sample_number = 5
print(f"The factorial of {sample_number} is: {factorial(sample_number)}")

Task 2:
import math
def perform_calculations():
    try:
        number = float(input("Enter a number: ")
        sqrt_value = math.sqrt(number)
        log_value = math.log(number)
        sine_value = math.sin(number)
        print(f"Square root: {sqrt_value}")
        print(f"Natural logarithm: {log_value}")
        print(f"Sine: {sine_value}")
    except ValueError:
        print("Please enter a valid number.")
    except Exception as e:
        print(f"An error occurred: {e}")
perform_calculations()


