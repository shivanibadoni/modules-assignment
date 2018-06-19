# modules-assignment
#q1
A tuple is a sequence of immutable Python objects. Tuples are sequences, just like lists.
The differences between tuples and lists are, the tuples cannot be changed unlike lists and tuples use parentheses,
whereas lists use square brackets.
#q2
import time
print (time.strftime("%H:%M:%S"))
 print (time.strftime("%I:%M:%S"))
#q3
>>> import datetime
>>> date = datetime.datetime.fromtimestamp(19800801)
>>> print date.month
8
#q4
>>> import datetime
>>> date = datetime.datetime.fromtimestamp(19800801)
>>> print date.day
17
#q6
>>> from time import gmtime, strftime
>>> strftime("%Y-%m-%d %H:%M:%S", gmtime())
#q7
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
n=4
factorial(n)
#q8
