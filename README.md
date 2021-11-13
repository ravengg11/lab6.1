import math
n = int(input("N-?"))
x = int(input("X-?"))
fact = 1 
sum_fact = 1 
z = 1 
for i in range(1,(2*n) + 1):
    fact = fact * i
    t = i % 2
    if t == 0:
        z = -z
        x = x*x
        sum_fact += z*(x/fact)
print (sum_fact)
print (math.cos(x))
