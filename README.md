# Python-64
 Python program to find the sum of the digits of an integer using while loop
total = 0
number = int(input("Enter an integer: "))

while number != 0:
    digit = number % 10
    total = total + digit
    number = number // 10

print("Sum of digits is:", total)

Output:
Enter an integer: 458
Sum of digits is: 17

