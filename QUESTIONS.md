## What is the difference between list, tuple, set, dict?

```python
"""
 list:
  - mutuable
  - []
  - indexed
  - ordered

 tuple:
  - immutuable
  - ()
  - indexed
  - ordered

 set:
  - mutuable
  - {}
  - unordered
  - unique

 dictionary:
  - key-value pair
  - {}
  - unordered
  - unique keys
  - mutuable
  - key should be immutable type e.g. String, number, tuples.
"""
```


## How do you slice a list to reverse it? To get every second item?

```python
myList = [1,2,3,4,5,6,7,8,9,0];

new_reversed = myList[::-1][::2];

print(new_reversed);
```



## What does this do: `a, b = b, a`?
```python
a = 10;
b = 15;

print("a = ", a, " b = ", b);

#SWAP
a,b = b,a;
print("a = ", a, " b = ", b);
```


## What's the difference between is vs ==?
```python
a = [1,2,3];
b = a;

c = [1,2,3];

print(a==b); # True
print(a==c); # True

print(a is b); # True
print(a is c); # False # Cause: 'a' & 'b' are refering to different memory location

"""
 == :
  - this checks content
 is :
  - this checks memory reference
"""
```