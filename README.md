# Calculator
#Intro
print('Welcome To One Time Use Calculator')
#Operators
print('Choose an operation to perform')
print('+ \n - \n * \n /')
operation = input()
#User Interaction
a=input('Enter Your First No.:')
b=input('Enter Your Second No.:')
#if elif and else statements
if operation =='+':
    print('The Answer Is', int(a)+int(b))
elif operation =='-':
    print('The Answer Is', int(a)-int(b))
elif operation =='*':
    print('The Answer Is', int(a)*int(b))
elif operation =='/':
    print('The Answer Is', int(a)/int(b))
else:
    pass
#Outro
print('Press enter to close....')
input()
