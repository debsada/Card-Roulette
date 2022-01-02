# Card-Roulette
A game that chooses a random name from user input to pay for the group meal

import random

# Split string method
names_string = input("Give me everybody's names, separated by a comma. ")
names = names_string.split(", ")


max_range = len(names)


unlucky_fella = random.randint(0,max_range - 1)

print(f"{names[unlucky_fella]} is going to buy the meal today!")
