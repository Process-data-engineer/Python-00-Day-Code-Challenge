# Python-100-Day-Code-Challenge
print("Welcome to the tip calculator!")
print("Welcome to the Tip Calculator")
Bill = float(input("What is your total bill? " + "$"))
Tip = int(input("what percentage of tip would you like to give ? 10 13 15.."))
People = int(input("how many people should pay? "))
tip_per = Bill*(Tip/100)
bill_tot = Bill+tip_per
ind_bill = round(bill_tot/People, 2)
print(f"Every Person Should Pay {ind_bill}")

