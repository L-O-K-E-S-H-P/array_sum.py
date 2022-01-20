# array_sum.py
Write a program to print the sum of all the elements of an array of size N where N can be any integer between 1 and 100.

N = input()

# Get the input
numArray = map(int, input().split())

sum_integer = 0
# Write the logic to add these numbers here

for i in numArray:
    sum_integer +=i


# Print the sum
print(sum_integer)
