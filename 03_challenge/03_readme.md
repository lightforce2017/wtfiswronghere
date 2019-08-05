Challenge 3 (1.5 min):

Error:
Traceback (most recent call last):
  File "03_challenge.py", line 26, in <module>
    fizzbuzz('16')
  File "03_challenge.py", line 15, in fizzbuzz
    for i in range(1,max_num):
TypeError: 'str' object cannot be interpreted as an integer

Should be:
Change fizzbuzz('16') into fizzbuzz(16) because function gets an integer as argument

Right:
fizzbuzz(16)