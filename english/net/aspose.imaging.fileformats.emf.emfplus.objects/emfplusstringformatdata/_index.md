---
title: Class EmfPlusStringFormatData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusStringFormatData class. The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string
type: docs
weight: 5910
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
## EmfPlusStringFormatData class

The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.

```csharp
public sealed class EmfPlusStringFormatData : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusStringFormatData](emfplusstringformatdata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CharRange](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/charrange/) { get; set; } | Gets or sets an optional array of RangeCount EmfPlusCharacterRange objects that specify the range of character positions within a string of text. The bounding region is defined by the area of the display that is occupied by a group of characters specified by the character range. This field MUST be present if the value of the RangeCount field in the EmfPlusStringFormat object is greater than 0. |
| [TabStops](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/tabstops/) { get; set; } | Gets or sets an optional array of floating-point values that specify the optional tab stop locations for this object. Each tab stop value represents the number of spaces between tab stops or, for the first tab stop, the number of spaces between the beginning of a line of text and the first tab stop. This field MUST be present if the value of the TabStopCount field in the EmfPlusStringFormat object is greater than 0. |

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


