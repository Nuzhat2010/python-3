a=10
b=-10
c=0
if a > 0  or b >0:
    print("either of the number is greater than 0 ")
else:
    print("no number is greater than 0")
if b > 0 or c > 0:
    print("either of the number is greater than 0")
else:
    print("no number is greater than 0")
h=float(input('height:'))
w=float(input('weight:'))
bmi=w/(h*h)

if bmi<18.5:
    print(f"your bmi is {bmi}.you are underweight")
elif bmi>=18.5 and bmi<25:
    print(f"your bmi is {bmi}.you are healthy")
elif bmi>=25 and bmi<30:
    print(f"your bmi is {bmi}.you are overweight")
elif bmi>=30 and bmi<35:
    print(f"your bmi is {bmi}.you are obese")
else:
    print(f"your bmi is {bmi}.you are extremely obese")                 
