# Python-Loops

```
A loop in Python is a control flow statement that allows code to be executed repeatedly.
 Python supports two main types of loops: for loops and while loops. 
```
 ```
#### For Loop:
Used to iterate over a sequence (such as a list, tuple, string, or range) or other iterable objects.
 The code block within the loop is executed once for each item in the sequence.
```
```js
    for item in sequence:
        # Code to be executed for each item
```
```js
  print my name three time

for i in [0,1,2]:
    print("Irfan")
--------
for i in range(3):
    print("Irfan")
---------
for _ in [0,1,2]:
    print("Irfan")
```
```js
print("Irfan\n" * 3)

```
```js
while True:
    n = int(input("What,s n?"))
    if n > 0:
        break

for _ in range(n):
    print("Irfan")    
```

```js

def main():
    number = get_number()
    name(number)

def get_number():
    while True:
        n = int(input("What's n?"))
        if n > 0:
            break
    return n

def name(n):
    for _ in range(n):
        print("Irfan")

main()


```







```
#### While loop: 
Used to repeatedly execute a block of code as long as a condition is true.
The loop continues until the condition becomes false. 
```
```js
    while condition:
        # Code to be executed while the condition is true
i = 0
while i < 3:
    print("Irfan")
    i = i + 1
```
```js
i = 3
while i !=0:
    print("Irfan")
    i = i - 1
```
