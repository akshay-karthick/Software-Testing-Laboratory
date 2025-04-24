## Ex.No: 5 To search a given element is present in the list using Binary search and introspect the causes for its failure
### AIM: 
Write a program in Python language to search a given element is present in the list using Binary search. Introspect the causes for its failure and write down the possible reasons for its failure.

### Algorithm:

---

1. Start the program
2. Set `low = 0` (first index)  
3. Set `high = length of arr - 1` (last index)  
4. Repeat while `low` is less than or equal to `high`  
 a. Set `mid = (low + high) // 2`  
 b. If `arr[mid] == x`, return `True`  
 c. Else if `arr[mid] < x`, set `low = mid + 1`  
 d. Else set `high = mid - 1`  
5. End loop  
6. Return `False` (element not found)  
7. Stop the program

---

### Program:
```
def binary_search(arr, x):
    low = 0
    high = len(arr) - 1
    while low <= high:
        mid = (low + high) // 2
        if arr[mid] == x:
            return True
        elif arr[mid] < x:
            low = mid + 1
        else:
            high = mid - 1
    return False

arr = [2, 4, 6, 8, 10, 12]
x = int(input("Enter the target:"))
if binary_search(arr, x):
    print("Element found")
else:
    print("Element not found")

```












### Output:
![image](https://github.com/user-attachments/assets/bf6f9d2f-9432-48d3-be81-521668875134)



### Result:
Thus, the python program to search a given element is present in the list using Binary search and the output is verified successfully.

