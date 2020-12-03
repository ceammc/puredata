[< reference home](ceammc_lib.html)
---

# math.gamma


gamma function

---

Extension of factorial function to real numbersFor any positive integer n, Γ(n) = (n−1)!<br>


---


```


[bang(                   [array GAMMA size=161 w=300 h=150 yr=-40..40]
|
[list.seq -4 4 0.05]
|
[list.each #a] [math.gamma #b]
|              |
|              [clip -50 50 #c]
|
|
[list.sep @enumerate 1]
|
[swap]
|   ^|.
[tabwrite GAMMA]
[X a:1->b] [X c->a:1]

            
```

---
arguments:


---
properties:


---
see also:<br>
[![math.gamma](img/object_math.gamma.png)](math.gamma.html)
[![math.lgamma~](img/object_math.lgamma~.png)](math.lgamma~.html)