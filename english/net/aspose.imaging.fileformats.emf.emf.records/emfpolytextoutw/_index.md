---
title: Class EmfPolyTextOutW
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyTextOutW class. The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors
type: docs
weight: 4190
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
## EmfPolyTextOutW class

The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors.

```csharp
public sealed class EmfPolyTextOutW : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPolyTextOutW](emfpolytextoutw/#constructor)() | Initializes a new instance of the `EmfPolyTextOutW` class. |
| [EmfPolyTextOutW](emfpolytextoutw/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPolyTextOutW` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounding rectangle in device units. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/exscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the X scale from page units to .01mm units if graphics mode is GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/eyscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the Y scale from page units to .01mm units if graphics mode is GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/igraphicsmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the current graphics mode, from the GraphicsMode enumeration (section 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [WEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/wemrtext/) { get; set; } | Gets or sets an array of EmrText objects (section 2.2.5) that specify the output strings in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. The number of EmrText objects is specified by cStrings. |

## Remarks

The font and text colors used for output are specified by properties in the current state of the playback device context. EMR_POLYTEXTOUTW SHOULD be emulated with a series of EMR_EXTTEXTOUTW records (section 2.3.5.7), one per string.

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


