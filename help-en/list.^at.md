[< reference home](index.html)
---

# list.^at


on input index(es) outputs list element(s)

---

<br>


---


![example](examples/list.^at-example.jpg)

---
arguments:

LIST: list content<br>

---
properties:

@default: default output value if element
            was not found<br>
@method: methods
            of processing of negative/invalid indexes<br>
@rel: alias to @method rel. Negative index means position
            from the end of the list<br>
@clip: alias to @method clip. If index &lt; 0 - return
            first element. If index greater or equal list size - return last element<br>
@fold: alias to @method fold. In range [0, LIST_SIZE)
            ordinal elements are returned. [LIST_SIZE, 2*LIST_SIZE) - returned in negative order
            etc.<br>
@wrap: alias to @method wrap. In range [0, LIST_SIZE)
            ordinal elements are returned. Other indexes are wrapped by modulo division.<br>

---
see also:<br>
[![list.at](img/object_list.at.png)](list.at.html)
