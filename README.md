# Some Python exercises solved by me
## From CodeWars
***
exercise: https://www.codewars.com/kata/54edbc7200b811e956000556/python
```
def count_sheeps(sheep):
    res = [x for x in sheep if x == True]
    return len(res)
```
***
exercise: https://www.codewars.com/kata/55d24f55d7dd296eb9000030
```
def summation(num):
    return sum(range(1, num+1))
```
***
exercise: https://www.codewars.com/kata/523b4ff7adca849afe000035
```
def greet():
    return "hello world!"
```
***
exercise: https://www.codewars.com/kata/52fba66badcd10859f00097e/python
```
def disemvowel(string_):
    return ''.join([char for char in string_ if char not in 'aeiouAEIOU'])
```
***
exercise: https://www.codewars.com/kata/554b4ac871d6813a03000035/python
```
def high_and_low(numbers):
    return f'{max(map(int, numbers.split(" ")))} {min(map(int, numbers.split(" ")))}'
```
***
exercise: https://www.codewars.com/kata/53dbd5315a3c69eed20002dd
```
def filter_list(l):
    return [a for a in l if isinstance(a, int)]
```