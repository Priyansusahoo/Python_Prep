# Python_Prep

## List
```python
# LISTS:

myList = [1, "Priyansu", 'A', True];

print(myList); # printing list

print(len(myList)); # printing length of the list

print(myList[1:]); # printing elements of the list from index 1 to n



'''
Lists are mutuable:
'''
myList[1] = "new-element";
print(myList);

'''
Methods related to Lists:
'''
# 'append' - add element to the end of the list
myList.append("Bankai");
print(myList);

# 'extend' - add no. of elements to the end of the list
myList.append(['a', True, "Priyansu", 2]); # this will add this list of elements as a list to 'myList'
print(myList); 

myList.extend(['a', True, "Priyansu", 2]); # This will extend 'myList' and add the elements to it
print(myList);
```
