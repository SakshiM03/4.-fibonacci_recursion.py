# 4.-fibonacci_recursion.py
def fibonacci(n):
    # Base cases
    if n == 0:
        return 0

    if n == 1:
        return 1

    # Recursive case
    return fibonacci(n - 1) + fibonacci(n - 2)


n = 7

print("Fibonacci series:")

for i in range(n):
    print(fibonacci(i), end=" ")

Output:

Fibonacci series:
0 1 1 2 3 5 8
