#The Python Bible course, Ziyad Yehia, project 4, Travis, the ridiculous security system
# student: Lukasz

know_users = ["Alice", "Bob", "Clarie", "Dan", "Emma", "George", "Harry"] #users name


while True: 
    print("Hi! My name is Travis")
    name =input("What is your name").strip().capitalize() # type your name

    if name in know_users: #checking is the inputed name is on list know_users
        print("Hello {}!".format(name))
        remove = input("Would you like to be removed from the system (y/n)?: ").lower()

        if remove == "y": #removing if y
            know_users.remove(name)
        elif remove == "n":
            print("no problem, I didn't want you to leave anyway")
            
            
    else:
        print ("Hmm I don't think I have met you yet {}".format(name)) # answer if the name is not on the list
        add_me = input("Would you like to be added to the system (y/n)?:").strip().lower()
        if add_me == "y":
            know_users.append(name)
            print("I put you on the list")
            print(know_users)
        elif add_me == "n":
            print("No worries. See you around!")

    
    escape = input("would you like to continue (y/n)?: ").strip().lower() # option to leave the program
    if escape == "y":
        continue
    else:
        break
