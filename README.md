# task-3
SWAP TWO VARIABLE  Swap two numbers without using a third variable.  # Example Input: a = 5, b = 10  # Example Output: a = 10, b = 5
a = 5
b = 10

# Swapping without a third variable
a = a + b
b = a - b
a = a - b

# Output the results
print(f"a = {a}, b = {b}")

