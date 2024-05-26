# Python-Some-Important-Coding-Question

# 1.Swape Two Number..

'''a = 10
b = 20
a,b = b,a
print("a:",a,"b:",b)'''


# 2.Prime or Not..?

'''n = int(input("Enter the no:"))
if n>1:
    for i in range(2,n):
        if n%i == 0:
            print(n,"is not prime")
            break
    else:
        print(n,"is prime")'''


# 3.How to find out the factorial of a number..?
'''n = int(input("Enter the number:"))
fact = 1
if n<0:
    print("Factorial of 0 does not exists")
if n == 0:
    print("Factorial of 0 is:",1)
if n>0:
    for i in range(1,n+1):
        fact = fact*i
    print("Factorial of given number is:",fact)'''


# 4 How to generate random number in python..?
# Any Number:

'''import random
num = random.random()
print(num)'''

# gives a random float number Specified range.

'''import random
num = random.uniform(1,100)
print(num)'''

# gives as a random integer Specified range.

'''import random
num = random.randint(1,100)
print(num)'''


# Random even Number....

'''import random
num = random.randrange(0,200,2)
print(num)'''

# Random Series.......?

'''import random
num = random.sample(range(0,100),8)
print(num)'''

# 5.Fibonacci series:?

'''n =10
n1,n2 = 0,1
print("Fibonacci Series:",n1,n2,end="")
for i in range (2,n):
    n3 = n1+n2
    n1 = n2
    n2 = n3
    print(n3,end="")'''

# IInd method:

'''a,b = 0,1
n = int(input("Enter the number:"))
if n == 1:
    print(a)
else:
    print(a)
    print(b)
    for i in range(2,n):
        c = a+b
        a = b
        b = c
        print(c)'''


# 6. Palindrome..?

'''value = input("Enter the Value:")
reversed_value = value[::-1]
if value == reversed_value:
    print("It's Palindrome")
else:
    print("It's not Palindrome")'''


# 7.Write a program to print the given number is odd or even.

'''n = int(input("Enter the no:"))
if n%2 == 0:
    print(n,"is even no")
else:
    print(n,"is odd no")'''


# 8.Write a program to find the given number is positive or negative.

'''n = int(input("Enter the no:"))
if n<0:
    print(n,"is Negative no")
else:
    print(n,"is positive no")'''

# Or

'''n1 = int(input("Enter 1st no:"))
n2 = int(input("Enter 2nd no:"))

if n1 == n2:
    print("both numbers are equal")
else:
    if n1<0:
        print(n1,"is negative number")
    else:
        print(n1,"is positive number")

    if n2<0:
        print(n2,"is negative number")
    else:
        print(n2,"is positive number")'''


# 9.Write a program to find the sum of two numbers.

'''n1 = int(input("Enter 1st no:"))
n2 = int(input("Enter 2nd no:"))

print("Sum of two number is:",n1+n2)'''

# 10.Write a program to find a maximum of two numbers.

'''n1 = int(input("Enter 1st no:"))
n2 = int(input("Enter 2nd no:"))
print("max of two no is:",max(n1,n2))'''

#or

'''n1 = int(input("Enter 1st no:"))
n2 = int(input("Enter 2nd no:"))

if n1>n2:
    print(n1,"is max number")
else:
    print(n2,"is max number")'''


# 11. Reverse String

'''my_str = "Kalidas"
print(my_str[::-1])'''



# Que.12 - Write a program to check if the given number is Armstrong or not.

'''n = int(input("Enter a number: "))
sum = 0
temp = n
while temp > 0:
   r = temp % 10
   sum = sum + r*r*r
   temp = temp//10
if n == sum:
   print(n,"is an Armstrong number")
else:
   print(n,"is not an Armstrong number")'''


# Que.13 -Write a program to find a minimum of two numbers.

'''n1 = float(input("Enter the 1st number:"))
n2 = float(input("Enter the 2nd number:"))
if n1 == n2:
    print("Both are equal")
if n1>n2:
    print(n2,"is minimum")
else:
    print(n1,"is minimum")'''



# Que.14 Write a program to find a maximum of three numbers.

'''n1 = float(input("Enter 1st Number:"))
n2 = float(input("Enter 2nd Number:"))
n3 = float(input("Enter 3rd Number:"))

if n1>n2 and n1>n3:
    print(n1,"is maximum")
if n2>n1 and n2>n3:
    print(n2,"is maximum")
if n3>n1 and n3>n2:
    print(n3,"is maximum")'''

# Or

'''n1 = float(input("Enter 1st Number:"))
n2 = float(input("Enter 2nd Number:"))
n3 = float(input("Enter 3rd Number:"))

if n1>n2 and n1>n3:
    print(n1,"is max.")
elif n2>n1 and n2>n3:
    print(n2,"is max")
else:
    print(n3,"is max.")'''


# Que.15 Write a program to find a minimum of three numbers.

'''n1 = float(input("Enter 1st Number:"))
n2 = float(input("Enter 2nd Number:"))
n3 = float(input("Enter 3rd Number:"))

if n1<n2 and n1<n3:
    print(n1,"is min.")
elif n2<n1 and n2<n3:
    print(n2,"is min.")
else:
    print(n3,"is min.")'''

# Or

'''n1 = float(input("Enter 1st Number:"))
n2 = float(input("Enter 2nd Number:"))
n3 = float(input("Enter 3rd Number:"))

if n1<n2 and n1<n3:
    print(n1,"is min.")
if n2<n1 and n2<n3:
    print(n2,"is min.")
if n3<n1 and n3<n2:
    print(n3,"is min.")'''


# Question 16: Write a Python program to find the largest element in a list.

'''l = [12,34,56,78,90,123,567,34,67,98,89,704,208,183]
l.sort()
print("largest element is:",max(l))'''


# Question 17: Write a Python program to find the Smallest element in a list.

'''l1 = [11,22,33,44,55,66,77,88,99,31,34,12,65,3,44,6,8,900]
l1.sort()
print("Smallest element is:",min(l1))'''

# Question 18: Write a Python program to sort the given list.

'''l2 = [11,22,33,44,55,66,77,88,99,31,34,12,65,3,44,6,8,900]
l2.sort()
print(l2)'''



# Question 19: Write a Python program to find the common elements between two lists.

'''list1 = [1,3,5,7,8]
list2 = [9,7,4,5,1]

print(set(list1) & set(list2))'''



# Qu.20 Merge two list:

'''l1 = [13,56,89,45]
l2 = [23,44,67,99]
merge_list = l1+l2
print(merge_list)'''


# Or
'''l1 = [13,56,89,45]
l2 = [23,44,67,99]
l1.extend(l2)
print("Merge two list:",l1)'''


# Qu.21 Reverse Counting:-

'''for rc in range(100,0,-1):
    print(rc)'''

'''for rc in range(1,101):
    print(rc)'''

'''n = int(input("Enter the number:"))
for rc in range(n,0,-1):
    print(rc)'''

# Qu.22 Generate custom font:

'''import pyfiglet
text = pyfiglet.figlet_format("JAY SHREE RAM",font="puffy")
print(text)'''


# Qu.- 23 Calender with Python:

#month

'''import calendar
month = calendar.month(2024,5)
print(month)'''

#Year

'''import calendar
year = calendar.calendar(2024)
print(year)'''

# Qu.24 Year is leap year or not?

'''import calendar
year = calendar.isleap(2024)
print(year)'''


# Qu.25 Get Current Time and Date:

# Time:
'''from datetime import datetime
time_now = datetime.now().strftime("%H:%M:%S")
print("The time is now:",time_now)'''

# Date:

'''from datetime import date
today_date = date.today()
print("To day",today_date)'''






# Qu.12-->
# *
# **
# ***
# ****
# *****


'''n = int(input("Enter the no:"))
for i in range (1,n+1):
    for j in range(1,i+1):
        print("*",end="")
    print()'''

#or

'''n = 5
for i in range(1,n+1):
    for j in range(1,i+1):
        print("$",end="")
    print()'''



# Qu.13-->
# * * * * *
# * * * * *
# * * * * *
# * * * * *
# * * * * *

'''n = 5
for i in range(5):
    print("* "*5)
print()'''

# Or

'''n = int(input("Enter the no:"))
for i in range(n):
    print("* "*n)
print()'''



# Qu.14-->

# *
# *

# *
# *

'''n = int(input("Enter the no:"))
for i in range(n):
    for j in range(n):
        print("*")
    print()'''

#or

'''n = 2
for i in range(2):
    for j in range(2):
        print("*")
    print()'''











# Write a program to find a substring in a given string
# Like:- string is Hsjshgramhfudndjjbdbjdk
# And
# Substring is ram
# Then program will check that ram is available in given string or not


'''def find_substring(main_string,substring):
    if substring in main_string:
        print(f"The substring {substring} is available in the given string")
    else:
        print(f"The substring {substring} is not available in the given string")


main_string = "Hsjshgramhfudndjjbdbjdk"
substring ="ram"
find_substring(main_string,substring)'''



# OR


'''def find_substring():
    main_string = input("Enter main_string:")
    substring = input("Enter substring:")

    if substring in main_string:
        print(f"The substring {substring} is available in the given string")
    else:
        print(f"The substring {substring} is not available in the given string")

find_substring()'''




# Write a program to find repeated substring in given string

#def find_repeated_substring():

'''string = "Hsjshgramhfudndjjbdbjdk"
print("All the duplicate characters in the string are: ")
for i in range(0, len(string)):
   count = 1
   for j in range(i+1, len(string)):
      if(string[i] == string[j] and string[i] != ' '):
         count = count + 1
# setting the string j to 0 to avoid printing the characters already taken
   string = string[:j] + '0' + string[j+1:]
# If the count is greater than 1, the character is considered as duplicate
   if(count > 1 and string[i] != '0'):
      print(string[i]," - ",count)'''






#Qu.31 Checking internet speed:

#[Pending?]


# Qu.32 Open a website using python:

'''import webbrowser
url = "https://google.com/"
open_web = webbrowser.open(url)
print(open_web)'''

'''import webbrowser
url = "https://instagram.com/"
open_web = webbrowser.open(url)
print(open_web)'''

'''import webbrowser
url = "https://youtube.com/"
open_web = webbrowser.open(url)
print(open_web)'''


# Qu.33 Grammer Errors:
#pending?


# Qu. count frequency of each element

 import collections
 def CountFrequency(arr):
     return collections.Counter(arr)

 # Driver function
 if __name__ == "__main__":

 	arr = [1, 1, 1, 1, 2, 2, 2, 2, 3, 3, 4, 5, 5]
 	freq = CountFrequency(arr)

 	# iterate dictionary named as freq to print
 	# count of each element
 	for (key, value) in freq.items():
		print (key, " -> ", value)









