import random

def my_rand1(n):
    rand_list=[]
    for i in range(n):
     rand_list.append(random.randint(3,9))
    return rand_list

n = 10
print(my_rand1(10))

#Метод 2
import random

res = random.sample(range(1, 50), 7)

print ("Random number list is : " + str(res))

#Метод 3

import random

res = [random.randrange(1, 50, 1) for i in range(7)]

print ("Random number list is : " + str(res))

#Метод 4

import random
lis = []
for _ in range(10):
 lis.append(random.randint(0, 51))
print(lis)

#Метод 5

import numpy as np

print(list(np.random.randint(low = 3,high=8,size=10)))

print(list(np.random.randint(low = 3,size=5)))

#Метод 6

import numpy as np

print(np.random.random_sample(size = 4))

print(np.random.random_sample(size = (4,4)))
