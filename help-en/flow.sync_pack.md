[< reference home](ceammc_lib.html)
---

# flow.sync_pack


flow pack with all hot inlets

---

<br>


---


```


[B]  [F]   [F]  [1 2(   [1 2 3( [F]
|    |     |    |       |       |
|    |     |.   |       |       |..
[flow.pack' 3 0 0 ABC {w=20}       ]
|
[ui.display @display_type=1]

            
```

---
arguments:

N: number of inputs<br>
VALS: default values for all inlets. If not enough default
            values given it sets to 0<br>

---
properties:


---
see also:<br>
[![pack](img/object_pack.png)](pack.html)
[![flow.pack](img/object_flow.pack.png)](flow.pack.html)