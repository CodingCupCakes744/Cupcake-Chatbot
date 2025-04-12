# Cupcake-Chatbot
"""A Python program that takes cupcake orders and gives bonus treats.My firstever project so nothing too cool I know lol."""

name = input("Welcome! May I have your name, please? ")
no = int(input("How many cupcakes would you like to order today? "))

if no < 10:
    print(f"Hi {name}, we really appreciate you dropping by! Just a heads-up: if you grab 10 or more cupcakes, we’ll throw in 5 extra—for free!")
else:
    print(f"Awesome choice, {name}! Since you ordered {no} cupcakes, you qualify for our sweet deal—5 bonus cupcakes! Your total: {no + 5} cupcakes. Enjoy!")
