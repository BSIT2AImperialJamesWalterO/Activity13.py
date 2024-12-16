# Activity13.py
print("Welcome to Factorial Program")
num = int(input("Enter any number: "))
fact = 1
for i in range(1, num + 1):
  fact *= i
print(f"The factorial of {num} is {fact}")
