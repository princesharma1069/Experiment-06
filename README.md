# Experiment-06
## Title: 
Study of conditional statements in python
## Theory:
Conditional statements in Python are used to make decisions based on certain conditions.
These statements evaluate Boolean expressions (True or False) and execute specific blocks of code accordingly.    
The primary decision-making constructs used in Python are if, if-else, and if-elif-else.  
The modulus operator (%) checks the divisibility of a element.  
Logical operators (and, or, not) to combine multiple conditions.    
Relational operators (>, <, >=, <=, ==, !=) to compare values.  
The if-elif-else ladder is used when multiple conditions need to be checked.  
## Algorithm:
    A)
    1)Start
    2)Input a using a = int(input("Enter a number:"))
    3)If a > 0, print "Number is positive"
    4)Else if a < 0, print "Number is negative"
    5)Else, print "Number is zero"
    6)Stop
    B)
    1)Start
    2)Input a using a = int(input("Enter a number:"))
    3)If a % 2 == 0, print "Number is Even"
    4)Else, print "Number is Odd"
    5)Stop
    C)
    Start
    1)Input a using a = int(input("Enter a number a:"))
    2)Input b using b = int(input("Enter a number b:"))
    3)Input c using c = int(input("Enter a number c:"))
    4)If a > b and a > c, print "a is the greatest number"
    5)Else if b > a and b > c, print "b is the greatest number"
    6)Else, print "c is the greatest number"
    7)Stop
    D)
    1)Start
    2)Input subject using subject = int(input("Enter a subject:"))
    3)If subject >= 90, print "Grade A"
    4)Else if subject >= 75, print "Grade B"
    5)Else if subject >= 60, print "Grade C"
    6)Else if subject >= 40, print "Grade D"
    7)Else, print "Fail"
    8)Stop
    E)
    1)Start
    2)Input year using year = int(input("Enter a year:"))
    3)If (year % 4 == 0 and year % 100 != 0) or year % 400 == 0, print "Leap year"
    4)Else, print "Not a leap year"
    5)Stop
    F)
    Start
    1)Input Date using Date = int(input("Enter a date:"))
    2)Input Month using Month = int(input("Enter a month:"))
    3)Input Year using Year = int(input("Enter a year:"))
    4)If Month in (1,3,5,7,8,10,12)
    5)If Date == 31 and Month == 12
         Year += 1
         Date = 1
         Month = 1
    6)Else if Date < 31
         Date += 1
    7)Else
         Date = 1
         Month += 1
    8)Else if Month in (4,6,9,11)
    9)If Date == 30
         Date = 1
         Month += 1
    10)Else if Date < 30
         Date += 1
    11)Else if Month == 2
    12)If (year % 4 == 0 and year % 100 != 0) or year % 400 == 0
      If Date == 29
         Date = 1
         Month += 1
      Else if Date < 29
         Date += 1
      Else
         If Date == 28
         Date = 1
         Month += 1
    13)Print Date,"/",Month,"/",Year
    14)Stop

