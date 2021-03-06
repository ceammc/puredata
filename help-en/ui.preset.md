[< reference home](index.html)
---

# ui.preset


Preset manager

---

Saves presets value of UI objects that have @presetname property. Can handle UI
            objects only on the save canvas, no subpatches or abstractions are supported.
NOTE: if no UI widgets with @presetname on canvas - *Shift-click* is
            disabled.
Active slot is highlighted, available slots are dark gray
<br>


---


![example](examples/ui.preset-example.jpg)

---
arguments:


---
properties:

@current: current preset
            index<br>
@send: send destination<br>
@receive: receive source<br>
@size: element size (width, height
            pair)<br>
@pinned: pin mode. if 1 - put element
            to the lowest level<br>
@active_color: active color (list of
            red, green, blue values in 0-1 range)<br>
@text_color: text color (list of red,
            green, blue values in 0-1 range)<br>
@empty_color: empty cell color
            (list of red, green, blue values in 0-1 range)<br>
@stored_color: stored cell color
            (list of red, green, blue values in 0-1 range)<br>
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

---
see also:<br>
[![preset.float](img/object_preset.float.png)](preset.float.html)
[![preset.storage](img/object_preset.storage.png)](preset.storage.html)
