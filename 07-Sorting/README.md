<b> `⦿ Sorting Algorithms` </b>

- <b> `Bubble Sort` 
```py
def bubble_sort(a: list):
    n = len(a)
    for i in range(n):
        swapped = False
        for j in range(n-i-1):
            if a[j] > a[j+1]:
                a[j], a[j+1] = a[j+1], a[j]
                swapped = True
        if not swapped:
            break
```
</b>

- <b> `Selection Sort`
```py
def selection_sort(a: list):
    n = len(a)
    for i in range(n):
        m = i # index of min element
        for j in range(i+1, n):
            if a[j] < a[m]:
                m = j
        a[i], a[m] = a[m], a[i]
```
</b>

- <b> `Insertion Sort` 
```py
def insertion_sort(a: list):
    n = len(a)
    for i in range(1, n):
        k = a[i] # key
        j = i-1    
        while j >= 0 and k < a[j]:
            a[j+1] = a[j]
            j -= 1
        a[j+1] = k
```
</b>

- <b> `Counting Sort` 
```py
def counting_sort(a: list):
    m = max(a)
    c = [0 for _ in range(m+1)]
    for i in a:
        c[i] += 1
    p = 0 # pointer
    for i in range(m+1):
        for j in range(c[i]):
            a[p] = i
            p += 1
```
</b>
