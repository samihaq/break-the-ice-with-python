# Question 44

### **Question:**

> **_Write a program which can map() to make a list whose elements are square of numbers between 1 and 20 (both included)._**

---

### Hints:

> **_Use map() to generate a list. Use lambda to define anonymous functions._**

---

**Main Author's Solution: Python 2**

```python
squaredNumbers = map(lambda x: x**2, range(1,21))
print squaredNumbers
```

---

**My Solution: Python 3**

```python
def sqr(x):
    return x*x

squaredNumbers = list(map(sqr, range(1,21)))
print (squaredNumbers)
```



---

[**_go to previous day_**](https://github.com/darkprinx/100-plus-Python-programming-exercises-extended/blob/master/Status/Day_11.md "Day 11")

[**_go to next day_**](https://github.com/darkprinx/100-plus-Python-programming-exercises-extended/blob/master/Status/Day_13.md "Day 13")

[**_Discussion_**](https://github.com/darkprinx/100-plus-Python-programming-exercises-extended/issues/3)
