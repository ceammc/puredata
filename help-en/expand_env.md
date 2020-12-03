[< reference home](ceammc_lib.html)
---

# expand_env


Substitute enviroment variables in data stream

---

Environment variable %HOME% will be replaced by home user directory under
            UNIXSome special variables defined: %DOC% - path to PureData doc directory, %CEAMMC% -
            path to ceammc library directory<br>


---


```


[B] [F]  [symbol user:%USER%( [list current shell: %SHELL%(
|   |    |                    |
|   |    |  [doc: %DOC%(      |  [doc: %CEAMMC%(
|   |    |  |                 |  |
|   |    |  |  [%DOC%(        |  | [home: %HOME%(
|   |    |  |  |              |  | |
[expand_env                        ]
|
[ui.display @display_type=1]




[%CEAMMC%(
|
[expand_env @any]
|
[symbol]
|
[S digits=70]
|
[print]

            
```

---
arguments:


---
properties:

@any: if specified - also do substitution in message
            selector<br>

---
see also:<br>
[![replace](img/object_replace.png)](replace.html)