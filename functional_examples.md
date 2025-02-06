





# Ejemplos de programación funcional

## map

```python
numbers = [1, 2, 3, 4, 5]
squares = list(map(lambda x: x ** 2, numbers))
print(squares)  # Output: [1, 4, 9, 16, 25]
```

## filter 
```python
numbers = [1, 2, 3, 4, 5, 6]
even_numbers = list(filter(lambda x: x % 2 == 0, numbers))
print(even_numbers)  # Output: [2, 4, 6]
```

## sort
````python
students = [('Alice', 22), ('Bob', 18), ('Charlie', 25)]
students.sort(key=lambda student: student[1])
print(students)  # Output: [('Bob', 18), ('Alice', 22), ('Charlie', 25)]
````