---
title: Enum EmfPlusDriverStringOptionsFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusDriverStringOptionsFlags enum. The DriverStringOptions flags specify properties of graphics text positioning and rendering. These flags can be combined to specify multiple options
type: docs
weight: 4910
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
## EmfPlusDriverStringOptionsFlags enumeration

The DriverStringOptions flags specify properties of graphics text positioning and rendering. These flags can be combined to specify multiple options.

```csharp
[Flags]
public enum EmfPlusDriverStringOptionsFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| DriverStringOptionsCmapLookup | `1` | If set, the positions of character glyphs SHOULD be specified in a character map lookup table. If clear, the glyph positions SHOULD be obtained from an array of coordinates. |
| DriverStringOptionsVertical | `2` | If set, the string SHOULD be rendered vertically. If clear, the string SHOULD be rendered horizontally. |
| DriverStringOptionsRealizedAdvance | `4` | If set, character glyph positions SHOULD be calculated relative to the position of the first glyph. If clear, the glyph positions SHOULD be obtained from an array of coordinates. |
| DriverStringOptionsLimitSubpixel | `8` | If set, less memory SHOULD be used to cache anti-aliased glyphs, which produces lower quality text rendering. If clear, more memory SHOULD be used, which produces higher quality text rendering. |

## Remarks

Graphics text output is specified in [`EmfPlusDrawDriverString`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) records

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


