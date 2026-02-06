---
title: Class EmfLogPenEx
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogPenEx class. The LogPenEx object specifies the style width and color of an extended logical pen
type: docs
weight: 3180
url: /net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
## EmfLogPenEx class

The LogPenEx object specifies the style, width, and color of an extended logical pen.

```csharp
public sealed class EmfLogPenEx : EmfBasePen
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfLogPenEx](emflogpenex/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| override [Argb32ColorRef](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/argb32colorref/) { get; set; } | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8). The interpretation of this field depends on the BrushStyle value, as shown in the table later in this section. |
| [BrushDibPattern](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushdibpattern/) { get; set; } | Gets or sets the brush dib pattern. |
| [BrushHatch](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushhatch/) { get; set; } | Gets or sets the brush hatch pattern. The definition of this field depends on the BrushStyle value, as shown in the table later in this section. |
| [BrushStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushstyle/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies a brush style for the pen from the WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). If the pen type in the PenStyle field is PS_GEOMETRIC, this value MUST be either BS_SOLID or BS_HATCHED. The value of this field can be BS_NULL, but only if the line style specified in PenStyle is PS_NULL. The BS_NULL style SHOULD be used to specify a brush that has no effect. |
| [NumStyleEntities](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/numstyleentities/) { get; } | Gets the number of elements in the array specified in the StyleEntry field. This value SHOULD be zero if PenStyle does not specify PS_USERSTYLE. |
| override [PenStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/penstyle/) { get; set; } | Gets or sets the pen style |
| [StyleEntry](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/styleentry/) { get; set; } | Gets or sets an optional array of 32-bit unsigned integers that defines the lengths of dashes and gaps in the line drawn by this pen, when the value of PenStyle is PS_USERSTYLE line style for the pen. The array contains a number of entries specified by NumStyleEntries, but it is used as if it repeated indefinitely The first entry in the array specifies the length of the first dash. The second entry specifies the length of the first gap. Thereafter, lengths of dashes and gaps alternate. If the pen type in the PenStyle field is PS_GEOMETRIC, the lengths are specified in logical units; otherwise, the lengths are specified in device units. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/width/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the width of the line drawn by the pen. If the pen type in the PenStyle field is PS_GEOMETRIC, this value is the width in logical units; otherwise, the width is specified in device units. If the pen type in the PenStyle field is PS_COSMETIC, this value MUST be 0x00000001. |

### See Also

* class [EmfBasePen](../emfbasepen/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


