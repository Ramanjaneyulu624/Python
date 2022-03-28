# Python
number1=float(input('Enter a number'))
number2=float(input('Enter a number'))
sym=input('select operation')
if sym== '+':
    print(number1,'+',number2, '=',number1 + number2)
elif sym=='-':
    print(number1,'-',number2,'=',number1-number2)
elif sym=='*':
    print(number1,'*',number2,'=',number1*number2)
elif sym=='/':
    print(number1,'/',number2,'=',number1/number2)
else:
    print('Invalid operation')
