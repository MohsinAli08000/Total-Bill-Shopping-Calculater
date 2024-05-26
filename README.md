# Total-Bill-Shopping-Calculater
sum=0
while (True):
    userinput=input("Enter the item price\n")
    if (userinput!='q'):
        sum=sum+float(userinput)
        print(f"Order total so for:{sum}")
    else:
        print(f"your Total BIll is {sum} Thanks for shopping")
        break
