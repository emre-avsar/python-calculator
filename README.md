# python-calculator
Simple calculator application built with Python.
num1 = float(input("Birinci sayi: "))
op = input("Islem (+ - * /): ")
num2 = float(input("Ikinci sayi: "))

if op == "+":
    print(num1 + num2)
elif op == "-":
    print(num1 - num2)
elif op == "*":
    print(num1 * num2)
elif op == "/":
    print(num1 / num2)
