import random

def love_calculator(name1, name2):
    score = random.randint(1, 100)
    print(f"The love score between {name1} and {name2} is {score}%")

name1 = input("Enter the first name: ")
name2 = input("Enter the second name: ")
love_calculator(name1, name2)
