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
length = float(input("Enter the length "))
#Height of room
Height = float(input("Enter the height "))
#Find Area of room
Area = (length * Height)
#Area of room
print(f"The area is {Area} m^2 squared")

#Excersise 4,
#length of farm in feets
length = float(input("Enter the length "))
#Height of farm in feets
Height = float(input("Enter the height "))
#Find Area of farm in feets
Area = (length * Height)
#Area of farm in acre
print(f'The area is {Area / 43560} acre' )

#Excersise 5, 
#find amount of liters in container
bottles_le_1lt = int(input("Bottles not greater than 1 liter: "))
bottles_ge_1lt = int(input("Bottles greater than 1 liter:"))

refund = (bottles_le_1lt * 0.10) + (bottles_ge_1lt * 0.25)
final_refund = "{:.2f}".format(refund)
print(f'You get an amount of ${final_refund} for your containers')

