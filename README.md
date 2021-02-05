# tpw_solutions_1_5.py
HW exercise 1-5

#Excersise 1, 
print("Kevin Wang\n"
"8101 Leslie St, Thornhill\n"
"Ontario, L3T 7P4\n"
"Canada")

#Excersise 2,
Name = str(input("Enter your name "))
print("Hello " + Name)

#Excersise 3,
#length of room
length = int(input("Enter the length "))
#Height of room
Height = int(input("Enter the height "))
#Find Area of room
Area = (length * Height)
#Area of room
print(Area)

#Excersise 4,
#length of farm in feets
length = int(input("Enter the length "))
#Height of farm in feets
Height = int(input("Enter the height "))
#Find Area of farm in feets
Area = (length * Height)
#Area of farm in acre
print(Area / 43560 )

Excersise 5, 
#find amount of liters in container
container = float(input("enter the amount "))

#deposit when container < 1 liter  
if container < 1:
        print("0.10$ deposit")
#deposit when container > 1 liter
elif container > 1:
        print("0.25$ deposit")

