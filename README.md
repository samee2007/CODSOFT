# calculator
# simple calculator with basic arithmetic operations
num1=eval(input("enter the First number :  "))
num2=eval(input("enter the Second number : "))
def add():
    return(num1+num2)
def subtraction():
    return(num1-num2)
def multiply():
    return(num1*num2)
def division():
    return(num1/num2)
def repeat():
        print("select a option\n" "1.addition\n" "2.subtraction\n" "3.multiplication\n" "4.division\n")
        n=int(input("enter a option from 1,2,3,4 = "))
        if (n==1):
            print("addition of two numbers = ",add())
        elif  (n==2):
            print("subtraction of two numbers =  ",subtraction())
        elif (n==3):
            print("multiplication of two numbers = ",multiply())
        elif (n==4):
            print("division of two numbers = ",division())
        else:
            print("error enter the option correctly")
            print("")
            repeat()
print()
repeat()
    
             
