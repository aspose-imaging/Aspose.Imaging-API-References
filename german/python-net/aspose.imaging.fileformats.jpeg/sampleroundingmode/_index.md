---
title: "SampleRoundingMode Aufzählung"
type: docs
weight: 80
url: /de/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---

Definiert eine Methode, wie ein n‑Bit‑Wert in einen 8‑Bit‑Wert umgewandelt wird.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.SampleRoundingMode

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| EXTRAPOLIEREN | Extrapoliere einen 8-Bit-Wert, um ihn in n Bits zu passen, wobei 1 &lt; n &lt; 8.<br/>            Die Anzahl aller möglichen 8-Bit-Werte ist 1 &lt;&lt; 8 = 256, von 0 bis 255.<br/>            Die Anzahl aller möglichen n-Bit-Werte ist 1 &lt;&lt; n, von 0 bis (1 &lt;&lt; n) - 1.<br/>            Der sinnvollste n-Bit-Wert Vn, der einem 8-Bit-Wert V8 entspricht, ist Vn = V8 &gt;&gt; (8 - n). |
| KÜRZEN | Kürze einen 8-Bit-Wert, um ihn in n Bits zu passen, wobei 1 &lt; n &lt; 8.<br/>            Die Anzahl aller möglichen n-Bit-Werte ist 1 &lt;&lt; n, von 0 bis (1 &lt;&lt; n) - 1.<br/>            Der sinnvollste n-Bit-Wert Vn, der einem 8-Bit-Wert V8 entspricht, ist Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |
