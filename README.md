# 2.leap-year-or-not
n=int(input('Enter any year:'))
if n%4==0 and n%100!=0:
    print('Leap year')
elif n%400==0:
    print('Leap year')
else:
    print('Not a Leap year')
