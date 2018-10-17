fib1 = 1

fib2 = 1

num = int(input())

print(fib1)

print(fib2)

new_fib = fib1 + fib2

while new_fib <= num:

    new_fib = fib1 + fib2

    print (new_fib)

    fib1, fib2 = fib2, new_fib
