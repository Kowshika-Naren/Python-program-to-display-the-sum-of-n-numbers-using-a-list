# Python-program-to-display-the-sum-of-n-numbers-using-a-list
numbers = []
num = int(input('How many numbers: '))

for n in range(num):
    x = int(input('Enter number '))
    numbers.append(x)

print("Sum of numbers in the given list is:", sum(numbers))
How many numbers: 5
Enter number 10
Enter number 20
Enter number 30
Enter number 40
Enter number 50
Sum of numbers in the given list is: 150
