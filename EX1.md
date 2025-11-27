## Ex.No:1

## Ex.Name: Write a CPP Program to perform insertion sort on a set of input.

## Aim:
To write a CPP Program to perform insertion sort on a set of input

## Algorithm:
1. Start
2. Read number of elements and the array elements
3. For each element from index 1 to n–1, store it as key
4. Compare key with previous elements
5. Shift all elements greater than key one position ahead
6. Insert key into the correct position
7. Repeat until the entire array is sorted
8. Print the sorted array
9. Stop

## Program:
```
void insertion(int arr[])
{
    int i,j,key;
    for(i=1;i<5;i++)
    {
        key = arr[i];
        j = i-1;
        while(j>=0 && arr[j] > key)
        {
            arr[j+1] = arr[j];
            j = j-1;
        }
        arr[j+1] = key;
    }
}
```


## Output:
<img width="977" height="536" alt="Screenshot 2025-11-05 181343" src="https://github.com/user-attachments/assets/5f7adf2a-e65a-4b52-85d8-1ac5a6b2367f" />

## Result:
Thus the program created successfully to perform insertion sort on a set of input.


