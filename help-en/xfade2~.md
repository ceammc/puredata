[< reference home](index.html)
---

# xfade2~


multi stereo-signal crossfade

---

control float value in range [0-1) controls xfade between first and second
            signals, [1-2) between second and third etc.
<br>


---


![example](examples/xfade2~-example.jpg)

---
arguments:

N: number of signal inputs
            (multiplied 2)<br>

---
properties:

@smooth(ms): 
            signal change smooth time<br>
@type: fade curve type:
            linear or power<br>
@lin: alias to @type lin<br>
@pow: alias to @type pow<br>

---
see also:<br>
[![xfade~](img/object_xfade~.png)](xfade~.html)
