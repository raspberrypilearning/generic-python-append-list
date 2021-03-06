Python lists are mutable. This means data can be added or removed from them. Let's try this out!

- Start by creating an empty list.

```python
my_list = []
```

- By using the keyword `append`, you can add any data you want to the list.

```python
my_list.append('A string')
```
- This will produce a list that looks like this:
```python
['A string']
```

- Lists can hold data of any type:
```python
my_list.append(1)
my_list.append(['another', 'list'])
my_list.append(('a', 'tuple'))
```

- The final result of all these operations would be:
```python
['A string', 1, ['another', 'list'], ('a', 'tuple')]
```
