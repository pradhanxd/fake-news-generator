import random
subjects = [
    "Shahrukh Khan",
    "Virat Kohli",
    "Nirmala Sitharaman",
    "A Mumbai Cat",
    "A Group Of Monkeys",
    "Prime Minister Modi",
    "Auto Rickshaw Driver From Delhi"
]

actions = [
    "Launches",
    "Cancels",
    "Dances With",
    "Eats",
    "Declares Wars On",
    "Orders",
    "Celebrates"
]

places_or_things = [
    "At Red Fort",
    "In Mumbai Local Train",
    "A Plate Of Samosa",
    "Inside Parliament",
    "At Ganga Ghat",
    "During IPL Match",
    "At India Gate"
]

while True:
    subject = random.choice(subjects)
    action = random.choice(actions)
    place_or_thing = random.choice(places_or_things)

    headline = f" BREAKING NEWS: {subject} {action} {place_or_thing}"
    print("\n" + headline)

    user_input = input("\nDo you want another headline?(yes/no)").strip().lower()
    if user_input == "no":
        break

print("\n Thanks for using the fake news generator.Have a fun day")

