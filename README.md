# set-of-integer
count = int(input("Enter the count of numbers: "))
i = 0
sum = 0
for i in range(count):
    x = int(input("Enter an integer: "))
    sum = sum + x
avg = sum/count
print(" The average is: ", avg)
output
Enter the count of numbers: 3
Enter an integer: 14
Enter an integer: 15
Enter an integer: 16
 The average is:  15.0
