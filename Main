import random

# helper functions

def name_to_number(name):
    if name == "rock":
        number = 0
    elif name == "Spock":
        number = 1
    elif name == "paper":
        number = 2
    elif name == "lizard":
        number = 3
    elif name == "scissors":
        number = 4
    else:
        print "Sorry, you entered an invalid choice."
    return number

def number_to_name(number):
    if number == 0:
        name = "rock"
    elif number == 1:
        name = "Spock"
    elif number == 2:
        name = "paper"
    elif number == 3:
        name = "lizard"
    elif number == 4:
        name = "scissors"
    else:
        print "Sorry, something went wrong!"
    return name
    
def rpsls(player_choice): 
    print ""
    print "You chose " + player_choice
    
    player_number = name_to_number(player_choice)
    comp_number = random.randrange(0, 5)
    comp_choice = number_to_name(comp_number)
    
    print "Computer chooses " + comp_choice

    difference = (comp_number - player_number) % 5

    if difference == 0:
        print "Player and computer tie!"
    elif difference <= 2:
        print "Computer wins!"
    elif difference > 2:
        print "Player wins!"

    
# test your code - THESE CALLS MUST BE PRESENT IN YOUR SUBMITTED CODE
rpsls("rock")
rpsls("Spock")
rpsls("paper")
rpsls("lizard")
rpsls("scissors")
