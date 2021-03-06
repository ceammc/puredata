[< reference home](index.html)
---

# ui.meter~


Shows peak and rms signal level

---

Each cell has 3db range. Full meter range is 39 db.
Values &gt; -3db are red, range [-12, -3) db is hot, [-21, -12) db is warm, [-30,
            -21) is tepid, values &lt; 30 are cold.
<br>


---


![example](examples/ui.meter~-example.jpg)

---
arguments:


---
properties:

@interval(ms): 
            refresh interval<br>
@send: send destination<br>
@receive: receive source<br>
@size: element size (width, height
            pair)<br>
@pinned: pin mode. if 1 - put element
            to the lowest level<br>
@cold_color: extra low-level signal
            color &lt;-31db (list of red, green, blue values in 0-1 range)<br>
@tepid_color: low-level signal color
            &lt;-21db (list of red, green, blue values in 0-1 range)<br>
@warm_color: normal level signal
            color &lt;-9db (list of red, green, blue values in 0-1 range)<br>
@hot_color: loud level signal color
            &lt;-3db (list of red, green, blue values in 0-1 range)<br>
@over_color: extra-loud level signal
            color &gt;-3db (list of red, green, blue values in 0-1 range)<br>
@background_color: element
            background color (list of red, green, blue values in 0-1 range)<br>
@border_color: border color (list
            of red, green, blue values in 0-1 range)<br>
@fontsize: 
            fontsize<br>
@fontname: fontname<br>
@fontweight: font
            weight<br>
@fontslant: font
            slant<br>

