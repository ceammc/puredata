[< reference home](ceammc_lib.html)
---

# conv.samp2ms~


convert samples to milliseconds according to samplerate

---

<br>


---


```


[bang(
|
[plot.linspace~ 0 sr()]
|                    ^|
[samp->ms~]           |
|                     |.
[ui.plot~ @size 400 170 @xlabels 1 @ylabels 1 @ymin 0 @ymax 1000 @ymin_ticks 0]













[ui.dsp~]

            
```

---
arguments:


---
properties:


---
see also:<br>
[![conv.samp2ms~](img/object_conv.samp2ms~.png)](conv.samp2ms~.html)