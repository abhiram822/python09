# python09
#ATM
print("Choose Language:")
print("1. English")
print("2. Hindi")
print("3. Telugu")
language = int(input("Enter the number for your language: "))
pin=int(input("Enter your 4-digit pin:"))
spin=1234
balance=5000
if pin==spin:
    print(" Access granted")
    withdraw=int(input("Enter amount:"))
    if withdraw > balance:
        print("Insufficent fund!!!")
    else:
        print("Amount withdraw:",withdraw)
        print("Remaining balance:",balance-withdraw)
        ptint("Thanks for withdrawing")
else:
    print("Access denied please try ")
ATM
