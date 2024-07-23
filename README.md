print("welcome to the tip calculator!")
b=float(input("what was the total bill? $"))
tip=input("how much tip would you like to give? 10%,20%,30% ")
p=int(input("how many people to split the bill with ? "))
payable=(b*(int(tip)/100)+b)/p
print("each person has to pay $",round(payable,2))
