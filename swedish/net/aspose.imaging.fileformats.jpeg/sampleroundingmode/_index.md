---
title: SampleRoundingMode
second_title: Aspose.Imaging för .NET API-referens
description: Definierar ett sätt på vilket ett n-bitars värde konverteras till ett 8-bitars värde.
type: docs
weight: 6800
url: /sv/net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

Definierar ett sätt på vilket ett n-bitars värde konverteras till ett 8-bitars värde.

```csharp
public enum SampleRoundingMode
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Extrapolate | `0` | Extrapolera ett 8-bitars värde för att passa in i n bitar, där 1 &lt; n &lt; 8. Antalet alla möjliga 8-bitars värden är 1 &lt;&lt; 8 = 256, från 0 till 255. Antalet av alla möjliga n-bitars värden är 1 &lt;&lt; n, från 0 till (1 &lt;&lt; n) - 1. Det mest rimliga n-bitarsvärdet Vn som motsvarar något 8-bitars värde V8 är lika med Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Trunkera ett 8-bitars värde för att passa in i n bitar, där 1 &lt; n &lt; 8. Antalet möjliga n-bitars värden är 1 &lt;&lt; n, från 0 till (1 &lt;&lt; n) - 1. Det mest rimliga n-bitarsvärdet Vn som motsvarar något 8-bitars värde V8 är lika med Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
