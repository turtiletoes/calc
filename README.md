# calc
fun thing
###############python
x1 = 0 #Num Input
x2 = 0 #num X2
x3 = 0 #Conclusion
rou = 0 #Rounds
action = 0 #Input what you do
repeat = 1 #repeats script
while repeat == 1:
    print("----")
    preX = x1 # previous X
    print("prv X1 = " + str(x1))
    print("----")
    #^^^^^^^^ setup and declares prev X
    x1 = input("What does your X1 equal?")
    print("____________________________")
    action = input("add? mul? div? sub?")
    print("____________________________")

    if action == "add": #Addition script
        x2 = input("what does x2 equal?")
        x1 = int(x1) + int(x2)
        print("your final answer is " + str(x1))
        rou = input("round number?")  # Round Script
        if rou == "yes":
            x1 = round(x1)
        print("your final answer is " + str(x1)) #Round script end
        repeat = input("continue y/n?")
        if repeat == "y":
            repeat = 1
        else:
            repeat = 0 #ends script

    if action == "sub": #Subtraction script
        x2 = input("what does x2 equal?")
        x1 = int(x1) - int(x2)
        print("your final answer is " + str(x1))
        rou = input("round number?")  # Round Script
        if rou == "yes":
            x1 = round(x1)
            print("your final answer is " + str(x1)) #Round script end
        repeat = input("continue y/n?")
        if repeat == "y":
            repeat = 1
        else:
            repeat = 0 #ends script

    if action == "mul": #Multiply
        x2 = input("what does x2 equal?")
        x1 = int(x1) * int(x2)
        print("your final answer is " + str(x1))
        rou = input("round number?")  # Round Script
        if rou == "yes":
            x1 = round(x1)
            print("your final answer is " + str(x1)) #Round script end
        repeat = input("continue y/n?")
        if repeat == "y":
            repeat = 1
        else:
            repeat = 0 #ends script

    if action == "div": #Divison
        x2 = input("what does x2 equal?")
        x1 = int(x1) / int(x2)
        print("your final answer is " + str(x1))
        rou = input("round number?") #Round Script
        if rou == "yes":
            x1 = round(x1)
            print("your final answer is " + str(x1)) #Round script end
        repeat = input("continue y/n?")
        if repeat == "y":
            repeat = 1
        else:
            repeat = 0 #ends script
