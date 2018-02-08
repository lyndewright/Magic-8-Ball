# Magic-8-Ball

import random
#list
prediction = ['Not gonna happen!', 'Absolutely!', 'Guess you will have to wait and see...']
#User prompt
user_input = input("Ask your question here:")
#Random response
print("Your answer is... " + random.choice(prediction))

user_input = input("Are you happy about that?")
if user_input == 'yes':
    print("Great!")
if user_input == 'no':
    print("Sorry!")

while True:
    user_input = input("Do you want to ask again?")
    if user_input == 'yes':
        import random
#list
        prediction = ['Not gonna happen!', 'Absolutely!', 'Guess you will have to wait and see...']
#User prompt
        user_input = input("Ask your question here:")
#Random response
        print("Your answer is... " + random.choice(prediction))

        user_happy = input("Are you happy about that?")
        if user_happy == 'yes':
            print("Great!")
        if user_happy == 'no':
            print("Sorry!")

    if user_input == 'no':
        break
