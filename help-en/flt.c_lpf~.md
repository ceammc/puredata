[< reference home](index.html)
---

# flt.c_lpf~


LPF coefficient calculator for biquad filter

---

Calculates coefficients for transfer function: H(z)=(b0 + b1*z⁻¹ + b2*z⁻²)/(1 +
            a1*z⁻¹ + a2*z⁻²)
<br>


---


![example](examples/flt.c_lpf~-example.jpg)

---
arguments:

freq(Hz): center
            frequency<br>
q: quality
            factory<br>

---
properties:

@freq(Hz): center frequency<br>
@q: quality
            factor: @freq/BANDWIDTH<br>
@active: on/off dsp
            processing<br>

---
see also:<br>
[![flt.biquad~](img/object_flt.biquad~.png)](flt.biquad~.html)
[![flt.lpf12~](img/object_flt.lpf12~.png)](flt.lpf12~.html)
