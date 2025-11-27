## Ex.No:2

## Ex.Name: Write the Partition module of Quick Sort in CPP.

## Aim:
To write the Partition module of Quick Sort in CPP.

## Algorithm:
1. Choose the last element as pivot
2. Initialize index i = low - 1
3. Traverse from low to high - 1
4. If element ≤ pivot, increment i and swap arr[i] and arr[j]
5. After traversal, swap pivot with arr[i + 1]
6. Return i + 1 as the partition index

## Program:
```
int partition(int array[], int low, int high) 
{
    int pivot=array[high];
    int i=(low-1);
    for(int j=low; j<high; j++)
    {
        if(array[j]<=pivot)
        {
            i++;
            swap1(&array[i],&array[j]);
        }
    }
    swap1(&array[i+1],&array[high]);
    return(i+1);
    
}
```


## Output:
<img width="1140" height="367" alt="Screenshot 2025-11-05 181812" src="https://github.com/user-attachments/assets/ad6c91ac-dbdc-4d8e-ab92-cc936747962c" />

## Result:
Thus the program created successfully Partition module of Quick Sort in CPP.

