---
title: Class EmfSetTextAlign
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetTextAlign class. The EMR_SETTEXTALIGN record specifies text alignment
type: docs
weight: 4610
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
## EmfSetTextAlign class

The EMR_SETTEXTALIGN record specifies text alignment.

```csharp
public sealed class EmfSetTextAlign : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetTextAlign](emfsettextalign/#constructor)() | Initializes a new instance of the `EmfSetTextAlign` class. |
| [EmfSetTextAlign](emfsettextalign/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfSetTextAlign` class. |

## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [TextAlignmentMode](../../aspose.imaging.fileformats.emf.emf.records/emfsettextalign/textalignmentmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies text alignment by using a mask of text alignment flags. These are either [`WmfTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/) ([MS-WMF] section 2.1.2.3) for text with a horizontal baseline, or [`WmfVerticalTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags/) ([MS-WMF] section 2.1.2.4) for text with a vertical baseline. Only one value can be chosen from those that affect horizontal and vertical alignment. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The EMR_SMALLTEXTOUT, EMR_EXTTEXTOUTA, and EMR_EXTTEXTOUTW records use text alignment values to position a string of text on the output medium. The values specify the relationship between a reference point and a rectangle that bounds the text. The reference point is either the current position or a point passed to a text output record. The rectangle that bounds the text is formed by the character cells in the text string.

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


