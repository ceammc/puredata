[< reference home](index.html)
---

# flt.eq_peak~


second order &#34;peaking equalizer&#34; section (gain boost or cut near some
            frequency). Also called a &#34;parametric equalizer&#34; section.

---

<br>


---


![example](examples/flt.eq_peak~-example.jpg)

---
arguments:

freq(Hz): peak
            frequency<br>
gain(db): level
            at fx (boost if &gt;0 or cut if &lt;0)<br>
bandwidth(Hz): 
            bandwidth of peak<br>

---
properties:

@freq(Hz): peak frequency<br>
@gain(db): level at fx (boost if &gt;0 or cut if &lt;0)<br>
@bandwidth(Hz): bandwidth of peak<br>
@active: on/off dsp
            processing<br>

---
see also:<br>
[![flt.eq_peak_cq~](img/object_flt.eq_peak_cq~.png)](flt.eq_peak_cq~.html)
[![flt.lowshelf~](img/object_flt.lowshelf~.png)](flt.lowshelf~.html)
[![flt.highshelf~](img/object_flt.highshelf~.png)](flt.highshelf~.html)
