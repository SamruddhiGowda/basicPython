even / odd 
n= int(input("Enter a number: "))
if (n % 2 == 0):
  print("even")
else:
  print("odd")

  swap 
  a= 5
b= 3
temp = a;
a = b;
b= temp;
print( "value of a after swapping :",a)
print( "value of b after swapping:",b)

a=5
b=3
a = a-b
b = a+b
a = b-a
print( "value of a after swapping :",a)
print( "value of b after swapping:",b)

palindrome 
def isPalindrome(s):
  return s == s[::-1]
s = '101'
ans = isPalindrome(s)
if ans:
  print ("yes")
else:
  print("no")

  n = 121
temp =n
rev=0
while (n>0):
  d= n%10
  rev = rev*10+d
  n=n//10
if (temp==rev):
  print("palindrome")
else:
  print("not a palindrome")

  prime no.s from 1 to n:
  def is_prime(num):
    if num <= 1:
        return False
    if num == 2:
        return True
    if num % 2 == 0:
        return False
    for i in range(3, int(num**0.5) + 1, 2):
        if num % i == 0:
            return False
    return True

def prime_numbers_up_to_n(n):
    primes = []
    for i in range(1, n + 1):
        if is_prime(i):
            primes.append(i)
    return primes

n = int(input("enter the value of n :"))
print(f"Prime numbers from 1 to {n}: {prime_numbers_up_to_n(n)}")

n = int(input("Enter the value of n: "))
for i in range(2, n + 1):
    flag = 0
    if i == 2:
        print(f'{i}', end=' ')
    else:
        for j in range(2, int(i ** 0.5) + 1):
            if i % j == 0:
                flag = 1
                break
        if flag == 0:
            print(f'{i}', end=' ')

pattern programming:
for i in range(5):
    for j in range(5):
        print('*', end=' ')
    print()

for i in range(5, 0, -1):
    for j in range(i, 0, -1):
        print(j, end=' ')
    print()

for i in range(5, 0, -1):
    print(" " * (5 - i), end='')
    for j in range(i, 0, -1):
        print(j, end=' ')
    print()

def print_x_pattern(n):
    for i in range(n):
        for j in range(n):
            if i == j or i + j == n - 1:
                print("*", end="")
            else:
                print(" ", end="")
        print()
print_x_pattern(5)

speedrun basics:
a='my name is sam'
print(a)

a = '''my name is
sam'''
print(a)

a="""my name is
 sam"""
print(a)

a = 'sam'
for i in a:
  print(i)

a='Thala for a reason'
print('Thala' in a)

a='thala for a reason'
if 'thala' in a:
  print("present")

slice method:
a= 'my name is sam'
print(a[0:2])

a= 'my name is sam'
print(a[-6:-1])

conversion:
a='sam'
b='SAM'
print('a = ',a.upper())
print('b = ',b.lower())

strip func:
a= 'my name is sam'
print(a.strip())

replace func:
a= 'my name is sam'
print(a.replace("i","e"))

split func:
a= 'my name is, sam'
print(a.split(','))

escape character:
a= "my name is \"sam\" gowda"
print(a)

bool values:
print(bool("hello"))

list:
