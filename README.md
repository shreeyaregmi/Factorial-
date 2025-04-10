# Factorial-
To find the factorial of a number.
# using if else 
def fact_norm(n):
    if n == 1:
        return 1
    else:
        return n * fact_norm(n - 1)
    
print("Factorial:", fact_norm(5))
