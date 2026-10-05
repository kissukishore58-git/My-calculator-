# My-calculator-
# It is my first GitHub project and I am a python learner


num1 = int(input("give a value:"))
num2 = int(input("give a value: "))
operator = input()

if operator == "+":
  print(f"Addition of two numbers : {num1 + num2}")
elif operator == "-":
  print(f"subtraction of two numbers : {num1 - num2}")
elif operator == "*":
  print(f"Multiplication of two numbers : {num1 * num2} ")
elif operator == "/":
  print(f"division of two numbers : {num1 / num2}")
else:
  print("invaild operator")         
  
  
