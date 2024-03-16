# bigger-3-number



number1 = int(input("please enter your number: "))
number2 = int(input("please enter your number: "))
number3 = int(input("please enter your number: "))

max_number = number1

if number2> max_number:
    max_number = number2
elif number3> max_number:
    max_number = number3
print(max_number)
