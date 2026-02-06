---
title: Enum SampleRoundingMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Jpeg.SampleRoundingMode enum. Defines a way in which an nbit value is converted to an 8bit value
type: docs
weight: 6910
url: /net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

Defines a way in which an n-bit value is converted to an 8-bit value.

```csharp
public enum SampleRoundingMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Extrapolate | `0` | Extrapolate an 8-bit value to fit it into n bits, where 1 &lt; n &lt; 8. The number of all possible 8-bit values is 1 &lt;&lt; 8 = 256, from 0 to 255. The number of all possible n-bit values is 1 &lt;&lt; n, from 0 to (1 &lt;&lt; n) - 1. The most reasonable n-bit value Vn corresponding to some 8-bit value V8 is equal to Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Truncate an 8-bit value to fit it into n bits, where 1 &lt; n &lt; 8. The number of all possible n-bit values is 1 &lt;&lt; n, from 0 to (1 &lt;&lt; n) - 1. The most reasonable n-bit value Vn corresponding to some 8-bit value V8 is equal to Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### See Also

* namespace [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg/)
* assembly [Aspose.Imaging](../../)


