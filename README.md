# programs
print("enter two numbers")

a=int(input("number1:"))

b=int(input("number 2:"))

print("choose 2 for + \n choose 3 for - \n choose 4 for * \n choose 1 for / ")

c=int(input("choose what to do:"))

if(c==1):
     print(f"the division is:{a/b}")
    
if(c==2):
     print(f"the division is:{a+b}")
    
if(c==3):
    print(f"the division is:{a-b}")
    
if(c==4):
    print(f"the division is:{a*b}")   
    
else:
   print("invalid")
    
    
