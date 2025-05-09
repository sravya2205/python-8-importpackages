from math import pow,sqrt
n=16
print(sqrt(n))
print(pow(2,3))

#trignometric functions
from math import sin,cos,tan,radians
angle=30
print("sin:",sin(radians(angle)))
print("cos:",cos(radians(angle)))
print("tan:",tan(radians(angle)))

#floor ,ceil
from math import floor,ceil
num=7.9
print("floor:",floor(num))
print("ceil:",ceil(num))

#log log10 exp,e
from math import log,log10,exp,e
print("natural log:",log(e))
print("log base 10:",log10(100))
print("e to power 2:",exp(2))

#pi
from math import pi
print(pi)

#finding the area of circle and circumference of circle
r=float(input("enter the radius"))
a=pi*(r**2)
d=r*2
c=pi*d
print("area:",a)
print("circumference:",c)

#date and time and calender epoch time
from datetime import datetime
now=datetime.now()
print("current time:",now)
print("Date:",now.date())
print("Time:",now.time())
