[< reference home](index.html)
---

# hoa.2d.decoder~


hoa 2d decoder

---

Decodes an ambisonics soundfield for several loudspeakers configuration or for
            headphones.
Mode:
• regular for a regular loudspeakers repartition over a circle.
• irregular if the loudspeakers are not equally spaced on a
            circle.
• binaural for headphones
The default mode is regular for an array of 2 * order + 2 loudspeakers. The
            default irregular configuration is 5.1 standard multichannel configuration.
<br>


---


![example](examples/hoa.2d.decoder~-example.jpg)

---
arguments:

ORDER: the order of
            decomposition<br>
MODE: decoding
            mode<br>
N: number of loud speakers (minimum 2*ORDER+1 for ambisonic
            mode)<br>

---
properties:

@order: the order of decomposition<br>
@mode: 
            decoding mode<br>
@regular: alias for @mode regular<br>
@irregular: alias for @mode irregular<br>
@binaural: alias for @mode binaural<br>
@crop(samp): crop HRIR response. Only in @binaural mode.<br>
@offset(deg): rotation of
            loudspeakers. Only available for @regular and @irregular mode.<br>
@angles(deg): angles of loudspeakers. Only
            available for @irregular mode.<br>
@pw_x(rad): list of plain wave x-coordinates (abscissas). -1 is the left of the
            soundfield, 0 is the center of the soundfield and 1 is the right of the
            soundfield.<br>
@pw_y(rad): list of plain wave y-coordinates (ordinatas). -1 is the back of the
            soundfield, 0 is the center of the soundfield and 1 is the front of the
            soundfield.<br>
@pw_z(rad): list of plain wave z-coordinates (heights). -1 is the bottom of the
            soundfield, 0 is the center of the soundfield and 1 is the top of the
            soundfield.<br>
@nharm: number of
            circular harmonics.<br>
@nwaves: number of
            plain waves.<br>

---
see also:<br>
[![hoa.encoder~](img/object_hoa.encoder~.png)](hoa.encoder~.html)
