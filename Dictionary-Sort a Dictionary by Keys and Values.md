# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program

```python
def dictionairy():
   key_value ={}
   key_value[2] = 56
   key_value[1] = 2
   key_value[5] = 12
   key_value[4] = 24
   key_value[6] = 18     
   key_value[3] = 323
   s=sorted(key_value.items(),key=lambda x:x[1])
   print ("Keys and Values sorted in alphabetical order by the value")
   print(s)
 
dictionairy()
      
```

## Sample Output

![image](https://github.com/user-attachments/assets/0014c95a-ec14-4ae5-b5ce-f6d66667ea73)

## Result

The program successfully sorts the dictionary by its keys and values in alphabetical order and prints both sorted versions along with the original dictionary.
