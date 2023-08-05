# !/usr/bin/python3  
#  
## Python program to demonstrate for loops.  
#  
  
### The for loop goes through a list, like foreach in  
### some other languages.  A useful construct.  
> for x in ['Bill', 'Alice', 'Joe', 'Sue' ]:  
    print(x, 'likes jelly beans.')  
  
### The range operator simply creates a list of numbers  
# in the indicated range.  Note that the range ends  
# before the second argument.  
> print(range(5, 10))  
  
### Range works with for to create the traditional for loop.  
> for y in range(2, 10):  
    print(y,end=' ')  
print()  
  
for y in range(2, 10, 2):  
    print(y,end=' ')  
print()  
  
for y in range(20, 10, -1):  
    print(y,end=' ')  
print()


# #!/usr/bin/python3  
  
## Dictionaries map keys to values.  
  
> fred = { 'mike': 456, 'bill': 399, 'sarah': 521 }  
  
### Subscripts.  
try:  
   > print(fred)  
    print(fred['bill'])  
    print(fred['nora'])  
    print("Won't see this!")  
except KeyError as rest:  
    print("Lookup failed:", rest)  
print()  
  
### Entries can be added, udated, or deleted.  
> fred['bill'] = 'Sopwith Camel'  
fred['wilma'] = 2233  
del fred['mike']  
print(fred)  
print()  
  '''
### Get all the keys.  
> print(fred.keys())  
for k in fred.keys():  
    print(k, "=>", fred[k])  
print()  
  
### Test for presence of a key.  
> for t in [ 'zingo', 'sarah', 'bill', 'wilma' ]:  
    print(t,end=' ')  
    if t in fred:  
        print('=>', fred[t])  
    else:  
        print('is not present.')

# !/usr/bin/python3  
  
### Tuples are immutable sequences, much like lists.  
> a = 5, 9, 'frank', 33  
b = ('this', 'that', 'the other')  
print("A:", a, b)  
  
### They can be concatinated, subscripted, and sliced.  
> c = a + b  
print("B:", c)  
print("C:", a[2], c[3:])  
  
### They can be taken apart, but the sizes must match!  
> w, x, y = b  
print("D:", w, x, y)  
try:  
    print("E", len(c))  
    (p, q, s, f) = c  
    print("F:", p, q, s, f)  
except ValueError as descr:  
    print("*** That won't work:", descr, "***")  
(p, q, s, f) = c[:4]  
print("G:", p, q, s, f)  
  
### Sub-tuples are allowed.  
> mrbig = (5, 17, 4, ('mac', 'alex', 'sally'), 888, b)  
print("H:", mrbig)  
  
### Empty tuples are allowed, and singleton tuples are ugly.  
> mt = ()  
singleton = (5,)  
print("I:", mt, singleton)  
  
### Tuples are immutable.  
try:  
    > fred = 5, 9, 22  
    fred[1] = 3  
    print("Won't see this.")  
except TypeError as descr:  
    print("*** That won't work:", descr, "***")  
  
### Tuples may contain mutable objects.  
> fred = (5, 9, [3, 4, 7])  
print("J:", fred)  
fred[2][1] = 'cow'  
print("K:", fred)
***

``` { .html .foo .bar }
<p>HTML Document</p>
```

``` { #example }
A linkable code block
```
