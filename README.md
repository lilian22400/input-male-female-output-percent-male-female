# input-male-female-output-percent-male-female
# Write a program that asks the user for the number of males and the number of females registered in a class using two separate inputs ("Enter number of males:", "Enter number of females:").

astr = input('input the number of males:')
a = int(astr)
bstr = input('input the number of females:')
b = int(bstr)
c = a+b
males = (a /c)*100
females = (b /c)*100
print('percent males:', males, '%')
print('percent females:', females, '%')
