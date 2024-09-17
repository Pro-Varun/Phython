# Phython

B,cong,Bh=0,0,0
v= int( input ( "enter a age"))
if (v>18):
     print("Press 1 for BJP")
     print("Press 2 for Congress")
     print("press 69 for Bhokaal")
     c=int(input("enter your choice")
     if (c==1):
         B=B+1
     if(c==2):
          cong=cong+1
     if(c==69):
           Bh=Bh+1
     else:
           print("invalid ")
else:
     print("u are not eligible")

print("Total Vote of BJP = ",B)
print("Total Vote of Congress = ",Cong)
print("Total Vote of Bhokaal  Party = ",Bh)

n1=int(input("Enter a Number"))
n2=int(input("Enter a Second Number"))

print("press (+) for sum of two no.")
print("press (-) for subtract of two no.")
print("press (/) for division of two no.")
print("press (*) for multiplication of two no.")

choice=input("Enter your Choice")

if (choice=="+"):
    print("Sum of two no.s = ",n1+n2)
elif (choice=="-"):
    print("Subtract of two no.s = ",n1-n2)
elif (choice=="/"):
    print("Division of two no.s = ",n1/n2)
elif (choice=="*"):
    print("Multiplication two no.s = ",n1*n2)
else:
    print("invalid choice")

    s=int(input("Enter starting ponit = "))
e=int(input("Enter ending ponit = "))
u=int(input("Enter updation choice = "))

print("Choice 'H' for horizantol")
print("Choise 'V' for vertical")

n=input("Enter your choice = ")

if (n=="H"):
    print("Choice 'F' for forward order")
    print("choice 'R' for reverse order")

    m=input("Enter your choice = ")

    if (m=="F"):
        for i in range(s,(e+1),u):
            print(i,end=' ')

    elif (m=="R"):
        for i in range(e,(s-1),-u):
            print(i,end=' ')

    else:
        print("Invalid Choice")

elif (n=="V"):
    print("Choice 'F' for forward order")
    print("choice 'R' for reverse order")

    m=input("Enter your choice = ")

    if (m=="F"):
        for i in range(s,(e+1),u):
            print(i)

    elif (m=="R"):
        for i in range(e,(s-1),-u):
            print(i)

    else:
        print("Invalid Choice")


else:
    print("Invalid choice")
