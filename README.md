# Coding-Dojo
Projects and Assignments from my time at the Coding Dojo
def countdown(num):
    newlist = []
    for num in range(num, -1, -1):
        newlist.append(num)
    return newlist
print(countdown(5))

print("----------")

b = 1
print(b)
def a(b):
    a = b + 1
    return a
print(a(b))

print("----------")

first = [1,2,3,4,5]
def a(num):
    for num in range(1, 2, 1):
        first.append(6)
    return first
print(a(first))

print("-----------")

x = [2, 3, 5, 4, 1]
def a(x):
    for x in range(0, 5, 1):
        if x < 2:
            return 5, 3, 4
        elif x > 10:
            return "False"
print(a(x))

print("------------")

def a(value, size):
    newList = []
    while value > 0:
        newList.append(size)
        value = value - 1
    return newList
print(a(4,7))

print("-------------")

def a(value, size):
    newList = []
    while value > 0:
        newList.append(size)
        value = value - 1
    return newList
print(a(6,2))
