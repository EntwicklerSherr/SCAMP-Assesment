# SCAMP-Assesment
Python Technical Assessment for the She Code Africa Mentorship Program

#Using Python, write out a function to output the fibbonacci sequence of a given number.In this case 10

x = int(input("Enter Number? "))

y1, y2 = 0, 1
count = 0

if x < 0:
   print("Please enter a positive integer")
elif x == 1:
   print("Fibonacci sequence upto",x,":")
   print(y1)
else:
   print("Fibonacci sequence:")
   while count < x:
       print(y1)
       nth = y1 + y2
      
       y1 = y2
       y2 = nth
       count += 1

#Output of given number:

Enter Number? 10
Fibonacci sequence:
0
1
1
2
3
5
8
13
21
34