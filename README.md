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
```js
students = ["Irfan","Ali","Ron","Jon"]

for student in students:
    print(student)
```
```js
students = ["Irfan","Ali","Ron","Jon"]

print(students[0])
print(students[1])
print(students[2])
print(students[3])

```
```js
students = ["Irfan","Ali","Ron","Jon"]

for i in range(len(students)):
    print(students[i])
```
```js
students = ["Irfan","Ali","Ron","Jon"]

for i in range(len(students)):
    print(i+1,students[i])
```
```
### List Print

students={
    "Ali":"B",
    "Ron":"f",
    "Jon":"A",
    "Haris":"C"
    
}
print(students["Ali"])
print(students["Ron"])
print(students["Jon"])
print(students["Haris"])
```
```js

students={
    "Ali":"B",
    "Ron":"f",
    "Jon":"A",
    "Haris":"C"
    
}

for student in students:
 print(student)

```

```js

students={
    "Ali":"B",
    "Ron":"f",
    "Jon":"A",
    "Haris":"C"
    
}

for student in students:
 print(student,students[student])


```
```js


students = [
    {"name":"Ali","English":"51","Urdu":"73","Math":"51","Science":"71"},
    {"name":"Ron","English":"43","Urdu":"40","Math":"33","Science":"63"},
    {"name":"Jone","English":"4","Urdu":"41","Math":"55","Science":"51"},
    {"name":"Harry","English":"41","Urdu":"64","Math":"77","Science":"37"},
    {"name":"Aloha","English":"16","Urdu":"35","Math":"22","Science":"64"}
]

for student in students:
    print(student["name"])


```
```js


students = [
    {"name":"Ali","English":"51","Urdu":"73","Math":"51","Science":"71"},
    {"name":"Ron","English":"43","Urdu":"40","Math":"33","Science":"63"},
    {"name":"Jone","English":"4","Urdu":"41","Math":"55","Science":"51"},
    {"name":"Harry","English":"41","Urdu":"64","Math":"77","Science":"37"},
    {"name":"Aloha","English":"16","Urdu":"35","Math":"22","Science":"64"}
]

for student in students:
    print(student["name"],student["English"],student["Urdu"],student["Math"],student["Science"])
```
```js


students = [
    {"name":"Name","English":"English","Urdu":"Urdu","Math":"Math","Science":"Science" },

    {"name":"Ali","English":"51","Urdu":"73","Math":"51","Science":"71"},
    {"name":"Ron","English":"43","Urdu":"40","Math":"33","Science":"63"},
    {"name":"Jone","English":"4","Urdu":"41","Math":"55","Science":"51"},
    {"name":"Harry","English":"41","Urdu":"64","Math":"77","Science":"37"},
    {"name":"Aloha","English":"16","Urdu":"35","Math":"22","Science":"64"}
]

for student in students:
    print(student["name"],student["English"],student["Urdu"],student["Math"],student["Science"], sep=",     ")
```









```
### While loop: 
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
##### Built Game Block Column Height Width 
```js


def main():
    print_colum(3)



def print_colum(height):
    for _ in range(height):
        print("#") 

main()           

```

```js
print row

def main():
   print_row(4)



def print_row(width):
   print("#"  * width)   

main()           

```
##### Print Squre 
```js

def main():
    print_squre(5)

def print_squre(size):

    for i in range(size):

        for j in range(size):
            print("@", end="") 

        print()     
  
main()           

```
```js

def main():
    print_squre(5)

def print_squre(size):

    for i in range(size):
        print("#" * size)   
  
main()           

```







