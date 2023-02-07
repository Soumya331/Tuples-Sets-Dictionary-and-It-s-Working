Ans 1. Tuple is a collection of values separated by comma and enclosed in parenthesis. 
Characteristics 
●	Tuples are immutable.
●	Tuples are ordered.
●	Allowes duplicate elements.
Yes, tuple is immutable.

Ans 2. There are only two tuple methods count() and index() that a tuple object can call.

count ()      fruits = ('a', 'p', 'p', 'l', 'e',)

print(fruits.count('p'))  
print(fruits.index('e'))  

index ()
letters = ("s", "o", "u", "m", "y", "a")

print(letters[3]) 
print(letters[4])  

Tuple has only two built-in functions because of immutability hence it doesn't allow much operations.


Ans 3) Set, dictionary do no allow duplicate items.


```python
list = {1, 1, 1, 2, 1, 3, 1, 4, 2, 1, 2, 2, 2, 3, 2, 4, 3, 1, 3, 2, 3, 3, 3, 4, 4, 1, 4, 2, 4, 3, 4, 4}
```


```python
list
```




    {1, 2, 3, 4}



Ans. 4 Both update() and union() perform the union operation. However, update() adds all missing elements to the set on which it is called whereas union() creates a new set. Consequently, the return value of update() is None and the return value of union() is a set. 

Example
Update
 s = {1, 2, 3}
 s.update({4, 5})
 s
{1, 2, 3, 4, 5}

Union
s = {1, 2, 3}
s.union({4, 5})
{1, 2, 3, 4, 5}



Ans 5. The dictionary is a useful data structure for storing (key, value) pairs.  

age = {"soumya" : 23, "Soum" : 19, "Shreya" : 32}

Dictionary is ordered.


Ans 6. Yes, we can create a nested dictionary.
people = {1: {'name': 'Soumya', 'age': '27', 'course':'Data Science Masters'},
          2: {'name': 'Shreya', 'age': '22', 'course':'Web Development'}}
print(people)

Ans 7)


```python
dict1 = {'language':'Python','course':'Data Science Masters'}
dict1.setdefault('Topics',['Python','Machine Learning','Deep Learning'])
print(dict1)

```

    {'language': 'Python', 'course': 'Data Science Masters', 'Topics': ['Python', 'Machine Learning', 'Deep Learning']}


Ans8)	

dict1 = {'Sport': 'Cricket' , 'Teams': ['India', 'Australia', 'England', 'South Africa', 'Sri Lanka', 'New Zealand']}



```python
dict1 = {'Sport': 'Cricket' , 'Teams': ['India', 'Australia', 'England', 'South Africa', 'Sri Lanka', 'New Zealand']} 
dict1.items()

```




    dict_items([('Sport', 'Cricket'), ('Teams', ['India', 'Australia', 'England', 'South Africa', 'Sri Lanka', 'New Zealand'])])




```python
dict1.values()
```




    dict_values(['Cricket', ['India', 'Australia', 'England', 'South Africa', 'Sri Lanka', 'New Zealand']])




```python
dict1.copy()
```




    {'Sport': 'Cricket',
     'Teams': ['India',
      'Australia',
      'England',
      'South Africa',
      'Sri Lanka',
      'New Zealand']}




```python

```

