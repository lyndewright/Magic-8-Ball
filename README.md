# Magic-8-Ball

import random
#list
prediction = ['Not gonna happen!', 'Absolutely!', 'Guess you will have to wait and see...']
#User prompt
user_input = input("Will I win the lottery tomorrow?")
#Random response
print("Your answer is... " + random.choice(prediction))

user_input = input("Are you happy about that?")
if user_input == 'yes':
    print("Great!")
if user_input == 'no':
    print("Sorry!")

while True:
