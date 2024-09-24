'''1'''
import math
x = float(input('Введите x '))
y = float(input('Введите y '))
f = math.log(abs(math.sin((x + y))))
print("f = ", f)

'''2'''

x = float(input('Введите x '))
y = float(input('Введите y '))
if math.sin(x+y)<= -0.5:
 f = (math.arctg(1./3.*(abs(x+y)))) * (exp(y)*x)
elif (math.sin(x+y) < 0,5) and (math.sin(x+y) >-0,5):
 f = 3*math.log(abs(x*y))
elif (math.sin(x+y) >= 0,5) :
 f = (x**3)+(y**1,5)
print('f = ', f)


'''3'''
import math
a = float(input('Введите a '))
b = float(input('Введите b '))
hx = float(input('Введите hx '))
x = a 
while x<= b: 
    f = (math.cos((math.e)*x))**3 +math.sin(abs(x))
    print('x = ', x, ' f = ', f)
    x = x + hx 
    
    
'''4'''   
import math
ax, bx, hx = 1.0, 2.5, 0.5
ay, by, hy = 1.0,4.0, 1.0
x = ax 
while x<= bx: 
    y = ay 
    while y<= by: 
        if x + y <= 2:
            f = math.pow(math.sin(x*math.pow(math.e,0.1*y)),1/3)
        else:
            f = math.fabs(math.log(x+y,2))
        print('x: = ', x, 'y = ', y, 'f = ', f) 
        y = y + hy 
        x = x + hx 
    
