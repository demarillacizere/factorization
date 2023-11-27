import time
def tabulation_factorial(n):
    fact = [1] * (n + 1)
    start_time = time.time()
    for i in range(2, n + 1):
        fact[i] = i * fact[i - 1]
    end_time = time.time()
    running_time = (end_time - start_time) * 1000
    print("Factorial of", n, "is", fact[n])
    print("Running time:", running_time, "milliseconds")

n = 50
tabulation_factorial(n)


