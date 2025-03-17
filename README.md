result=0
def add():
    x= int(input("enter the first number:"))
    y= int(input ("enter the second number: "))
    result= x+y
    return result 
   
def sub():
    x= int(input(" enter the first number :"))
    y=int(input(" enter the second number : "))
    result=x-y
    return result 
    
def mul():
    x= int(input(" enter the first number : "))
    y= int(input("enter the second number :"))
    result= x*y
    return result 
def div():
    x= int(input ( " enter the first number : "))
    y= int(input ("enter the second number :"))
    result=x/y
    return result 
    
while (1):
    print(f"welcome to your personal calculator")
    print("1.Addition \n 2.Subtraction \n 3.Multiplication \n 4.division \n 5. Exit ")
    x= int (input("enter your choice :"))
    if (x==1):
        result= add()
        print(result)
    elif(x==2):
        result=sub()
        print(result)
    elif (x==3):
        result=mul()
        print(result)
    elif (x==4):
        result =div()
        print(result)
    elif (x==5):
        exit()
    else:
        print("Enter a valid Option ")
