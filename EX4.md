## Ex.No:4

## Ex.Name: Write the Element found module of Binary Search in CPP.

## Aim:
To write the Element found module of Binary Search in CPP.

## Algorithm:
1. Read the array and key to search
2. Set low = 0 and high = n - 1
3. While low ≤ high, find mid = (low + high)/2
4. If arr[mid] == key, element is found — return index
5. If arr[mid] > key, set high = mid - 1
6. Else set low = mid + 1
7. If loop ends, element not found

## Program:
```
int ElementFound(int a[], int mid, int search){
    if(a[mid]==search)
        {
            printf("Element found at %d position",mid + 1);
            return 1;
        }
        else{
            return 0;
        }
}
```


## Output:
<img width="1023" height="450" alt="Screenshot 2025-11-05 182557" src="https://github.com/user-attachments/assets/92dbb8c5-99d6-43e6-8212-f08477c7d41d" />

## Result:
Thus the program created successfully found module of Binary Search in CPP.

