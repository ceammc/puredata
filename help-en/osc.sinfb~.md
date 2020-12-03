[< reference home](ceammc_lib.html)
---

# osc.sinfb~


Sine oscilator with feedback

---

<br>


---


```


[F]     [ui.knob @min 0 @max 6.28]
|       |
|       |
|       |
|       [@feedback $1(
|       |
[osc.sinfb~ 440 2]
|
[ui.gain~ @size 120 14]  [ui.dsp~]
|\      |
[dac~]  [ui.scope~]







            
```

---
arguments:

freq(Hz): initial
            frequency<br>
feedback: oscillator
            feedback coefficient in range 0..2pi<br>

---
properties:

@feedback: 
            oscillator feedback coefficient<br>
@active: on/off dsp
            processing<br>
