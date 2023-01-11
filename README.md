# projecteuler

#1 multiples of 3 or 5 below 1000
#run the number from 1 to 1000 in steps of 1
#identify if number is a multiple of 3 or 5 using remainder
#integer division, to retain quotient, use "//"
#exponent, raising power, use "**"
#add number to sum if the number is a multiple of 3 or 5
#keep looping until number reach 999

#import math
i = 0
sum = 0

while i < 999:
  i += 1

  if i%3 == 0 or i%5 == 0:
    sum = sum + i

print(sum)
