---
layout: default
---

# Background
Diffraction is a beautiful phenomenon that causes iridescent lighting effects in materials.
Diffraction happens when a planar wave encouters an obstacle or a slit. As shown in Figure 1,
the planar wave bends around the corners. This phonomenon is a property of any type of wave.
However, diffraction is generally talked about in terms of light. Light is a wave and will 
also bend around corners. If a slit decreases to a size comparable to the wavelength of light
then the "wave" becomes spherical. Another way to look at it is the slit becomes a point source
for the wave instead of a directional source.

![Wave Diffraction]({{site.url}}{{site.baseurl}}/assets/images/wave_diffraction.png)
***Figure 1:** Planar wave (left) turning into a spherical wave (right) due to a small slit.*

Most of the diffraction we see in the world happens on materials that have many small
slits. Materials with many small slits are called diffraction gratings. Since every slit
becomes a point source of light, diffraction gratings create a series of point lights
close together. The combination of all of the waves causes interference, both constructive
and destructive, and a pattern emerges. As shown in Figure 2, diffraction grating with multiple
wavelengths of light will cause peaks of wavelengths at different viewing angles. The intensity
of the light also falls off as the viewing angle is increased. This pattern is what we see when we
look at a CD or certain meats.

![Diffraction Grating]({{site.url}}{{site.baseurl}}/assets/images/diffraction_grating.png)
***Fig 1:** Planar wave (left) encountering a diffraction grating with many slits causing a pattern (right).*

# Current Work

Diffraction in graphics is an interesting problem to be solved in order to generate beautiful and 
photorealistic materials. Since photorealism is the goal, I use a ray tracer to implement diffraction.
The ray tracer is a custom ray tracer built as an assignment in CS354. The ray tracer is extended
to support diffraction materials.

Diffraction in a ray tracer works by simply adding a diffraction term to the Phong shading model.
The computation of the diffraction term is derived by Emmanuel Agu and Francis Hill Jr. in their 
paper "A Simple Method for Ray Tracing Diffraction." 

# Results

![diff_d]({{site.url}}{{site.baseurl}}/assets/images/diff_d.gif)
***Fig 1:** Hello*

![diff_n]({{site.url}}{{site.baseurl}}/assets/images/diff_n.gif)
***Fig 1:** Hello*

![diff_dir_planar]({{site.url}}{{site.baseurl}}/assets/images/diff_dir_planar.gif)
***Fig 1:** Hello*

![diff_point_planar]({{site.url}}{{site.baseurl}}/assets/images/diff_point_planar.gif)
***Fig 1:** Hello*

![diff_dir_radial]({{site.url}}{{site.baseurl}}/assets/images/diff_dir_radial.gif)
***Fig 1:** Hello*

![diff_point_radial]({{site.url}}{{site.baseurl}}/assets/images/diff_point_radial.gif)
***Fig 1:** Hello*

![DragonXL]({{site.url}}{{site.baseurl}}/assets/images/DragonXL.gif)
***Fig 1:** Hello*

# References

**bold**
_italic_
~~strikethrough~~
[Text link](link.html)
> Blockquote
```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```
*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.
1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *
- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

![Octocat](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>


