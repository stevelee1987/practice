# practice
print('hello professor kurisima')
print('i want to be a good programmer just like white hat')
print('i look forward to kind coopertion')
import random
import time
w = ['cat', 'dog', 'fox', 'monkey', 'mouse', 'panda', 'frog', 'snake', 'wolf']
n = 1
print('you ready for play game. please push your enter button')
input()
start = time.time()
q = random.choice(w)
while n < = 5
    print('*subject', n)
    
    print(q)
    x = input()
    if q == x:
       print('pass')
       n = n + 1
       q = random.choice(w)
    else:
        print('be wrong! try again')
end = time.time()
et = end - start
et = format(et, '2f')
print('typing time : ', et, 'second')
    
    
    
