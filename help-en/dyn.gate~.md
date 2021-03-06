[< reference home](index.html)
---

# dyn.gate~


mono signal gate

---

<br>


---


![example](examples/dyn.gate~-example.jpg)

---
arguments:

threshold(db): dB
            level threshold above which gate opens (e.g., 40 dB)<br>
attack(ms): 
            attack time = time constant (ms) for gate to open<br>
hold(ms): hold
            time = time (ms) gate stays open after signal level &lt; threshold<br>
release(ms): 
            release time = time constant (ms) for gate to close<br>
ID: object ID for OSC control path<br>

---
properties:

@threshold(db): dB level threshold above which gate opens<br>
@attack(ms): attack time = time constant (ms) for gate to open<br>
@hold(ms): hold time = time (ms) gate stays open after signal level &lt;
            threshold<br>
@release(ms): release time = time constant (ms) for gate to close<br>
@active: on/off dsp
            processing<br>

---
see also:<br>
[![dyn.gate2~](img/object_dyn.gate2~.png)](dyn.gate2~.html)
