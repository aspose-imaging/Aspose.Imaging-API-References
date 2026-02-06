---
title: Class EmfPolyTextOutA
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyTextOutA class. The EMR_POLYTEXTOUTA record draws one or more ASCII text strings using the current font and text colors
type: docs
weight: 4180
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
## EmfPolyTextOutA class

The EMR_POLYTEXTOUTA record draws one or more ASCII text strings using the current font and text colors.

```csharp
public sealed class EmfPolyTextOutA : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPolyTextOutA](emfpolytextouta/#constructor)() | Initializes a new instance of the `EmfPolyTextOutA` class. |
| [EmfPolyTextOutA](emfpolytextouta/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPolyTextOutA` class. |

## Properties

| Name | Description |
| --- | --- |
| [AEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/aemrtext/) { get; set; } | Gets or sets an array of EmrText objects (section 2.2.5) that specify the output strings in 8-bit ASCII characters, with text attributes, and spacing values. The number of EmrText objects is specified by cStrings. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounding rectangle in device units. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/exscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the X scale from page units to .01mm units if graphics mode is GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/eyscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the Y scale from page units to .01mm units if graphics mode is GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/igraphicsmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the current graphics mode, from the GraphicsMode enumeration (section 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The font and text colors used for output are specified by properties in the current state of the playback device context. EMR_POLYTEXTOUTA SHOULD be emulated with a series of EMR_EXTTEXTOUTW records (section 2.3.5.7), one per string. This requires the ASCII text string in each EmrText object to be converted to Unicode UTF16-LE encoding.

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


