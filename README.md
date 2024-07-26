# accecode3py-print-units-place-10-s-place-and-remaining-value-
''' write a program transferce through all digits and print units place , tens place and the remaining value of that number 
input num=4802
ouput= units place digit is: 2
      tens place digit is : 0
      remaining digits are:48'''

      num=int(input("enter the 4 digit number:"))
units=num%10
print("units place digitis:",units)
num//=10
tens=num%10
print("tens place digit is :",tens)
num//=10
print("remaining digits are:",num)
