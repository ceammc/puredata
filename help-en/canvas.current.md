[< reference home](index.html)
---

# canvas.current


verbose information about current canvas

---

<br>


---


![example](examples/canvas.current-example.jpg)

---
arguments:


---
properties:

@name: canvas name<br>
@dir: canvas directory (only if top level
            or abstraction)<br>
@args: canvas creation arguments<br>
@root: 1 if canvas is top-level
            (window)<br>
@abstraction: 1 if canvas is
            abstraction<br>
@size: canvas dimensions.
            If root canvas (window) return window size, if subpatch return Graph on Parent
            size<br>
@font: canvas font size<br>
@paths: canvas search paths<br>
@width: canvas width (window
            or GOP)<br>
@height: canvas height (window
            or GOP)<br>
@x: canvas x-pos (window or
            GOP)<br>
@y: canvas y-pos (window or
            GOP)<br>

---
see also:<br>
[![patch.args](img/object_patch.args.png)](patch.args.html)
[![canvas.top](img/object_canvas.top.png)](canvas.top.html)
