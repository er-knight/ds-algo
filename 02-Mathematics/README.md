⦿ Finding the number of digits in a number.
<b>

```py
n = 12345
m = n # copy of n 
d = 0 # number of digits

while m > 0:
    m = int(m/10)
    d += 1

print(d) # 5
```
```py
from math import log10

n = 12345
d = int(log10(n)) + 1 # number of digits
print(d) # 5
```
</b>

--- 

⦿ Finding the number of bits in a number.
<b>

```py
n = 12
m = n # copy of n 
b = 0 # number of bits

while m > 0:
    m = int(m/2)
    b += 1

print(b) # 4
```
```py
from math import log2

n = 12
b = int(log2(n)) + 1 # number of bits
print(b) # 4
```
</b>

--- 

⦿ Arithmetic Progressions.

- <b>`a`</b> is first term, <b>`b`</b> is last term and <b>`d`</b> is common difference.
- n<sup>th</sup> term of arithmetic progression  
 <b> `a + (n - 1) * d` </b>
- sum of n terms of arithmetic progression  
 <b> `(n * (2 * a + (n - 1) * d)) / 2` </b> or <b> `(n * (a + b)) / 2` </b>
- arithmetic mean  
 <b> `(2 * a + (n - 1) * d) / 2` </b> or <b> `(a + b) / 2` </b>

---

⦿ Geometric Progressions.

- <b>`a`</b> is first term, <b>`b`</b> is last term and <b>`r`</b> is common ratio.
- n<sup>th</sup> term of geometric progression   
 <b> `a * r ^ (n - 1)` </b>
- sum of n terms of geometric progression (when <b> `r < 1` </b>)  
 <b> `a * (1 - (r ^ n)) / (1 - r)` </b>
- sum of n terms of geometric progression (when <b> `r > 1` </b>)  
 <b> `a * ((r ^ n) - 1) / (r - 1)` </b>
- sum of infinite terms of geometric progression (when <b> `r < 1` </b>)  
 <b> `a / (1 - r)` </b>

---