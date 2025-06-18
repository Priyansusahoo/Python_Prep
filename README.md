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

myList.extend(['a', True, "Priyansu", 2]); # This will extend 'myList' and add the elements to the list
print(myList);

# 'pop' - remove element from list 
#       - pop() returns the element

myList.pop(4);
print(myList);

elementPoped = myList.pop(0); # pop() retuens the element and we store it in 'elementPoped' variable
print(elementPoped);
print(myList);

# 'reverse()'
#          - this reverses the element in place
#          - and doesn't return the new reversed list
myList.reverse();
print(myList);

print(myList.reverse()); # OUTPUT - None

# 'sort()'
newMyList1 = [1,5,6,3,2,7,8,3,6,4,6,8,1,23,4,5,6,6,7,8,8];
newMyList1.sort();
print(newMyList1);


# LIST COMPREHENSION

matrix = [[1,2,3], [4,5,6],[7,8,9]];
print(matrix[0][1]);

# printing 1st element in each row of a matrix
firstColumn = [row[0] for row in matrix]

print(firstColumn); # OUTPUT - [1, 4, 7]

myList = [1,2,3,4,5,6,6,7,8,8,9]


print(myList[:])

# copy content from one list to another
copyList = list(myList[0:4]);
copyList = myList[0:4];
copyList = myList.copy();

print(copyList)

# Slicing Syntax in Python
print(myList[0::2]);

# print in reverse order
print(myList[::-1]);

# start - not mentioned
# end   - not mentioned
# step  - it's negative steps so it will start from last and also include the step

print(myList[::-3]);
```
