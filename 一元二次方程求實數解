a = float(input())
b = float(input())
c = float(input())
delta = b * b - 4 * a * c
if a == 0 and b != 0:
    #print( round(- c / b,2))
    print('{:.2f}'.format(- c / b))
elif a == 0 and b == 0:
    print('Data error!')
elif delta < 0:
    print("此方程式無實數解")
elif delta == 0:
    #print(round(-b  / (2 * a),2))
    print('{:.2f}'.format(-b  / (2 * a)))
else:
    x1 = (-b + delta ** 0.5) /( a * 2)
    x2 = (-b - delta ** 0.5) /(a * 2)
    if x1 < x2:
             x1,x2=x2,x1
    
    print('{:.2f} {:.2f}'.format(x1,x2)) 
