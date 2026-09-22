print("Using Temp")
a,b=10,5
temp=a
a=b
b=temp
print(a,b)
print("Using ,")
a,b=10,5
a,b=b,a
print(a,b)
print("Using + and -")
a,b=10,5
a=a+b
b=a-b
a=a-b
print(a,b)
print("Using ^")
a,b=10,5
a=a^b
b=a^b
a=a^b
print(a,b)
