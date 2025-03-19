61. What is the difference between a shallow copy and a deep copy in Python?

- [ ] A shallow copy copies only the object, while a deep copy copies the object and all nested objects
- [ ] A deep copy copies only the object, while a shallow copy copies the object and all nested objects
- [ ] A shallow copy can only be used with lists, while a deep copy works with all data types
- [ ] There is no difference; they are two names for the same operation

---

62. Write a Python function that uses the `sorted()` function with a custom key to sort a list of strings by their length.

---

63. What will the following code output?
```python
def outer_function():
    x = 10
    def inner_function():
        nonlocal x
        x = 20
    inner_function()
    return x

print(outer_function())
```

- [ ] 10
- [ ] 20
- [ ] None
- [ ] Error

---

64. What is a generator in Python? Select all that apply.

- [ ] A function that uses the `yield` keyword instead of `return`
- [ ] A data structure that can store multiple items
- [ ] A way to create iterators with less memory usage
- [ ] A class that creates instances of objects

---

65. Write a Python function that uses the `filter()` function to filter out all even numbers from a list.

---

66. What is the purpose of `*args` and `**kwargs` in Python function definitions?

- [ ] `*args` allows a function to accept a variable number of positional arguments, and `**kwargs` allows a variable number of keyword arguments
- [ ] `*args` and `**kwargs` are used to make functions run faster
- [ ] `*args` unpacks dictionaries, and `**kwargs` unpacks lists and tuples
- [ ] `*args` is for mandatory arguments, and `**kwargs` is for optional arguments

---

67. Create a simple class named `Rectangle` with attributes `width` and `height`, and methods to calculate the area and perimeter.

---

68. What is the output of the following code?
```python
numbers = [1, 2, 3, 4, 5]
squared = map(lambda x: x**2, numbers)
print(list(squared))
```

- [ ] [1, 2, 3, 4, 5]
- [ ] [1, 4, 9, 16, 25]
- [ ] [2, 4, 6, 8, 10]
- [ ] Error

---

69. Which of the following statements about Python's GIL (Global Interpreter Lock) is true?

- [ ] It allows multiple threads to execute Python bytecode at the same time
- [ ] It prevents multiple threads from executing Python bytecode at the same time
- [ ] It optimizes memory management in Python
- [ ] It is only present in Python 2, not in Python 3

---

70. Write a Python function that uses regular expressions to validate if a given string is a valid email address.
