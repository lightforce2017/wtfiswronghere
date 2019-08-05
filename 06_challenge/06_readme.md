Challenge 6 (2 min):

Error:
Traceback (most recent call last):
  File "06_challenge.py", line 34, in <module>
    fizzbuzz(100)
  File "06_challenge.py", line 21, in fizzbuzz
    num2 = conf.num
AttributeError: module 'conf' has no attribute 'num'

Should be:
conf has no num.
num2 = conf.num
See conf.py:
it has num2

So:
num1 = conf.num1
num2 = conf.num2