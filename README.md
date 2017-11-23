# Python-codecademy.com
#my learning about python on www.codecademy.com
#This is my second try of using github, because I don't really get the way to use it, but I want to try and record my Python learning 
#exercises on web of www.codecademy.com
# ok the following are the assignment of the exercise:
# A prime number is a positive integer greater than 1 that has no positive divisors other than 1 and itself
# the instruction is :Define a function called is_prime that takes a number x as input.
#  For each number n from 2 to x - 1, test if x is evenly divisible by n.

#  If it is, return False.

#   If none of them are, then return True.
def is_prime(x):
  if x < 2:
    return False
  else:
    for n in range(2,x-1):
      if x % n == 0:
        return False
    return True
# this function may be easy for you, but I have thought for a long time, after I knew the answer, I think this is a better way 
# and a easier one than I have ever thought, so I want to make a record of this one, maybe it's helpful.
