[< reference home](index.html)
---

# conv.lin2exp


maps linear range to exponential range

---

The output range must not include zero. If the input exceeds the input range, by
            default clip is applied.
<br>


---


![example](examples/conv.lin2exp-example.jpg)

---
arguments:

FROM: begin of input range<br>
TO: end of input range<br>
FROM: begin of output range<br>
TO: end of input output<br>

---
properties:

@in_from: begin of input range<br>
@in_to: end of input range<br>
@out_from: begin of output range<br>
@out_to: end of output range<br>
@clip: 
            noclip (don&#39;t clip) max (clip ceiling) min (clip floor) minmax (clip both).<br>
@noclip: alias to @clip noclip<br>
@min: alias to @clip min<br>
@max: alias to @clip max<br>
@minmax: alias to @clip minmax<br>

---
see also:<br>
[![conv.lin2lin](img/object_conv.lin2lin.png)](conv.lin2lin.html)
[![conv.lin2curve](img/object_conv.lin2curve.png)](conv.lin2curve.html)
