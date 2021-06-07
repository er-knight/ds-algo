<h2 align="center"> Time Complexity Analysis </h2>

⦿ What is Time Complexity of following code?
<b>

```py
print("hello")
```
</b>

<details>
<summary> Answer </summary>

<b> `O(1)` </b>
</details>

---

⦿ What is Time Complexity of following code?
<b>

```py
for i in range(0, 1, 1):
    print("hello")
```
</b>

<details>
<summary> Answer </summary>

<b> `O(1)` </b>
</details>

---

⦿ What is Time Complexity of following code?
<b>

```py
for i in range(0, n, 1):
    print("hello")
```
</b>

<details>
<summary> Answer </summary>

<b> `O(n)` </b>
</details>

---

⦿ What is Time Complexity of following code?
<b>

```py
for i in range(0, n, 1):
    for j in range(0, n, 1):
        print("hello")
```
</b>

<details>
<summary> Answer </summary>

<b> `O(n²)` </b>
</details>

---

⦿ What is Time Complexity of following code?
<b>

```py
for i in range(0, m, 1):
    for j in range(0, n, 1):
        print("hello")
```
</b>

<details>
<summary> Answer </summary>

<b> `O(m×n)` </b>
</details>

---

⦿ What is Time Complexity of following code?
<b>

```py
i = 1
while i < n:
    print("hello")
    i *= 2
```
</b>

<details>
<summary> Answer </summary>

<b> `O(log₂n)` </b>
</details>

---

⦿ What is Time Complexity of following code?
<b>

```py
for i in range(0, n, 1):
    j = 1
    while j < n:
        print("hello")
        j *= 2
```
</b>

<details>
<summary> Answer </summary>

<b> `O(n×log₂n)` </b>
</details>

--- 

⦿ What is Time Complexity of following code?
<b>

```py
for i in range(0, m, 1):
    j = 1
    while j < n:
        print("hello")
        j *= 2
```
</b>

<details>
<summary> Answer </summary>

<b> `O(m×log₂n)` </b>
</details>

--- 

⦿ What is Time Complexity of following code?
<b>

```py
i = 1
while i < n:
    j = 1
    while j < n:
        print("hello")
        j *= 2
    i *= 2
```
</b>

<details>
<summary> Answer </summary>

<b> `O((log₂n)²)` </b>
</details>

---

⦿ What is Time Complexity of following code?
<b>

```py
i = 1
while i < m:
    j = 1
    while j < n:
        print("hello")
        j *= 2
    i *= 2
```
</b>

<details>
<summary> Answer </summary>

<b> `O(log₂m×log₂n)` </b>
</details>

---

⦿ What is Time Complexity of following code?
<b>

```py
def fib(n):
    if n <= 1:
        return n
    else:
        return fib(n-1) + fib(n-2)
```
</b>

<details>
<summary> Answer </summary>

<b> `O(2ⁿ)` </b>  

<img src="https://raw.githubusercontent.com/er-knight/ds-algo/master/images/exponential.png" width="300">
</details>

---