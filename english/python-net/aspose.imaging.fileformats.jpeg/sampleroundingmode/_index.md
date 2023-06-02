---
title: SampleRoundingMode Enumeration
type: docs
weight: 80
url: /python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---

Defines a way in which an n-bit value is converted to an 8-bit value.

**Namespace:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.SampleRoundingMode

**Assembly:**  Aspose.Imaging Version: 23.5.0

## **Members**
|**Member name**|**Description**|
| :- | :- |
|EXTRAPOLATE|Extrapolate an 8-bit value to fit it into n bits, where 1 < n < 8.<br/>            The number of all possible 8-bit values is 1 << 8 = 256, from 0 to 255.<br/>            The number of all possible n-bit values is 1 << n, from 0 to (1 << n) - 1.<br/>            The most reasonable n-bit value Vn corresponding to some 8-bit value V8 is equal to Vn = V8 >> (8 - n).|
|TRUNCATE|Truncate an 8-bit value to fit it into n bits, where 1 < n < 8.<br/>            The number of all possible n-bit values is 1 << n, from 0 to (1 << n) - 1.<br/>            The most reasonable n-bit value Vn corresponding to some 8-bit value V8 is equal to Vn = V8 & ((1 << n) - 1).|
