# hw5
```html
<from numpy import * 
import matplotlib.pyplot as plt 

def f(x): 
return x**2*exp(-x*2)*cos(3*x) 

x = linspace(-10,10 , 51) # 51 точка между 0 и 3 
y = f(x) 

plt.plot(x, y) 
plt.show()>
```
![screenshot of sample](https://pp.userapi.com/c831308/v831308795/890c8/JUQ5sxB_DDE.jpg)

```html
<from numpy import * 
import matplotlib.pyplot as plt 
def func(x): 
    return x**2*exp(-x*2)*cos(3*x) 
def trapezoid (a,b,n): 
    h=(b-a)/(n-1) 
    sum=(func(a)+func(b))/2 
    for i in range (1,n-1): 
        sum +=func(a+i*h) 
    return h*sum 
a=0 
b=1
n=1000 
print (trapezoid (a,b,n-1))>
>Ответ:-0.027525155343462213


```html
<from numpy import *
import matplotlib.pyplot as plt 
def func(x): 
    return x**2*exp(-x*2)*cos(3*x) 
a=0 
B=1
n=1000 
def trapezoid (a,b,n):
    h=(B-a)/(n-1) 
    for i in range (1,n-1):
           b=a+i*h<B
    sum=(func(a)+func(b))/2 
    for i in range (1,n-1): 
        sum +=func(a+i*h) 
    return h*sum   
print (trapezoid (a,b,n-1))
)>
>Ответ:-0.027525155343462213
Ответ, посчитанный с помощью встроенной функции: -0.027525155343462213
Все шикарно!
