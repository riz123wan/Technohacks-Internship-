# Technohacks-Internship-
Task 4. To - Do -list
import random

def roll_dice():
    return random.randint(1, 6)

def main():
    print("Rolling the dice...")
    dice1 = roll_dice()
    dice2 = roll_dice()
    print("Result:")
    print("Dice 1:", dice1)
    print("Dice 2:", dice2)
    print("Total:", dice1 + dice2)

if __name__ == "__main__":
    main()

