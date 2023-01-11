# projecteuler
#1 multiples of 3 or 5 below 1000
import math
i = 0
sum = 0

#run the number from 1 to 1000 in steps of 1
while i < 999:
  i += 1
#identify if number is a multiple of 3 or 5 using remainder
  if i%3 == 0 or i%5 == 0:

#add number to sum if the number is a multiple of 3 or 5
    sum = sum + i
#keep looping until number reach 999
print(sum)
