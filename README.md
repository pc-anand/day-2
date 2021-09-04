# day-2
##name:Palak Chilbule
```python
#program for pattern below using zip()
'''
1   5
2   4
3   3
4   2
5   1
'''
num = ["1", "2", "3", "4", "5"]
reverse_num = ["5", "4", "3", "2", "1"]
for n, r_n in zip(num, reverse_num):
    print("%s   %s" % (n, r_n))
# program for the sum of 10 natural numbers
sum = 0
i = 1
while i<=10:
    sum = sum + i
    i = i+ 1
print(sum)
# factorial of 5
num=5
fact=1
for i in range(1,num+1):
    fact = fact*i
print('factorial of 5 is',fact)
#  fibonacci series 0 1 1 2 3 5 8 13
num = int(input('Enter a number'))
num0 = 0
num1 = 1
i = 0
fn = 0
if num < 0:
    print('Negative numbers are not allowed')
elif num == 0:
    print('Fibonacci series of 0 is 0')
else:
    for i in range(1, n):
        fn = num0 + num1
        num0 = num1
        num1 = fn
        print(num1)
    print('Fibonacci series of', num, 'is', num1)

# program for calculation of LCM, HCF, GCD
n1 = float(input('Enter first number'))
n2 = float(input('Enter second number'))
gcd = 0
if (n2 == 0):
    print(n1)
print(gcd(n2, n1 % n2))

# program for checking leap year
y = int(input('Enter year'))
if y % 400 == 0:
    print('It is a leap year')
elif y % 4 == 0:
    print('It is a leap year')
elif y % 100 == 0:
    print('Is a not a leap year')
else:
    print('Not a leap year')

# WAP to check armstrong number
n = int(input("Enter a number: "))
sum = 0
temp_num = n
while temp_num > 0:
    digit = temp_num % 10
    sum += digit ** 3
    temp_num //= 10
if n == sum:
    print(n, "is an Armstrong number")
else:
    print(n, "is not an Armstrong number")

# palindrome number
n = int(input("Enter number:"))  # 2002
temp_num = n
rev = 0
while (temp_num > 0):  # temp_num = 0
    dig = temp_num % 10  # dig = 2
    rev = rev * 10 + dig  # rev = 200*10+2= 2002
    temp_num //= 10  # temp_num  = 0
if (n == rev):
    print("The number is a palindrome")
else:
    print("The number is not a palindrome")

#Enter five integer number and find max number (using simple if)
num = int(input("Enter a Number :"))
largest = 0
while (num > 0):
    remainder = num % 10
    if largest < remainder:
        largest = remainder
    num //= 10
print("the largest digit is :", largest)

# Enter five integer number and find smallest number (using simple if)
num = int(input("Enter a Number :"))
smallest = num
while (num > 0):
    remainder = num % 10
    if smallest > remainder:
        smallest = remainder
    num //= 10
print("The Smallest Digit is :", smallest)
#  ASCII equivalent
char = (input("Enter a character: "))
print("The ASCII value of", char, "is", ord(char))```
