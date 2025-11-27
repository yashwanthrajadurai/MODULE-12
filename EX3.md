## Ex.No:3

## Ex.Name: Write the mergeSort Module of Merge Sort in CPP.

## Aim:
To write the mergeSort Module of Merge Sort in CPP.

## Algorithm:
1. If low < high, find mid = (low + high)/2
2. Recursively call mergeSort for left part (low, mid)
3. Recursively call mergeSort for right part (mid + 1, high)
4. Merge the two sorted parts using merge() function

## Program:
```
void mergeSort(int arr[], int l, int r)
{
    if(l<r)
    {
        int m = l+(r-l)/2;
        mergeSort(arr,l,m);
        mergeSort(arr,m+1,r);
        merge(arr,l,m,r);
    }
}
```


## Output:
<img width="1048" height="319" alt="Screenshot 2025-11-05 182202" src="https://github.com/user-attachments/assets/dc3d9635-fefa-46d8-a331-4194b7492d6e" />

## Result:
Thus the program created successfully mergeSort Module of Merge Sort in CPP.

