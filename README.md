# My-codes
These are some of the codes I have done while I learn pyhton.
import random

secret = random.randint(1, 10)
guess = int(input("Guess the number: "))

if guess == secret:
    print("Correct!")
else:
    print("Wrong!")
