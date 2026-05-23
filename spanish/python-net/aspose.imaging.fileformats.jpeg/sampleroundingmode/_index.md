---
title: "Enumeración SampleRoundingMode"
type: docs
weight: 80
url: /es/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---

Define una forma en que un valor de n bits se convierte a un valor de 8 bits.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.SampleRoundingMode

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| EXTRAPOLATE | Extrapolar un valor de 8 bits para ajustarlo a n bits, donde 1 &lt; n &lt; 8.<br/>            El número de todos los valores posibles de 8 bits es 1 &lt;&lt; 8 = 256, de 0 a 255.<br/>            El número de todos los valores posibles de n bits es 1 &lt;&lt; n, de 0 a (1 &lt;&lt; n) - 1.<br/>            El valor de n bits más razonable Vn correspondiente a algún valor de 8 bits V8 es igual a Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Truncar un valor de 8 bits para ajustarlo a n bits, donde 1 &lt; n &lt; 8.<br/>            El número de todos los valores posibles de n bits es 1 &lt;&lt; n, de 0 a (1 &lt;&lt; n) - 1.<br/>            El valor de n bits más razonable Vn correspondiente a algún valor de 8 bits V8 es igual a Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |
