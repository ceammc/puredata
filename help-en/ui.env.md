[< reference home](index.html)
---

# ui.env


envelope editor widget

---

Editor of sound envelope function
<br>


---


![example](examples/ui.env-example.jpg)

---
arguments:


---
properties:

@length(ms): 
            envelope time length<br>
@presetname: preset name for using with
            [ui.preset]<br>
@send: send destination<br>
@receive: receive source<br>
@size: element size (width, height
            pair)<br>
@pinned: pin mode. if 1 - put element
            to the lowest level<br>
@active_color: element active color
            (list of red, green, blue values in 0-1 range)<br>
@line_color: line color (list of
            red, green, blue values in 0-1 range)<br>
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
@mouse_events: mouse events output
            mode. If on outputs @mouse_down, @mouse_up and @mouse_drag events<br>
@output_mode: 
            output envelope mode. If set to &#34;mouse_up&#34; - output envelope on mouse up if Ctrl/Cmd
            key not pressed. If set to &#34;drag&#34; - output envelope on every change. Note: in any mode
            you can output evenlope with Ctrl/Cmd + mouse down.<br>

