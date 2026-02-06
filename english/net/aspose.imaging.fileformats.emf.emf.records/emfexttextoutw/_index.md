---
title: Class EmfExtTextOutW
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtTextOutW class. The EMR_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors
type: docs
weight: 3780
url: /net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---
## EmfExtTextOutW class

The EMR_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors.

```csharp
public sealed class EmfExtTextOutW : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfExtTextOutW](emfexttextoutw/#constructor)() | Initializes a new instance of the `EmfExtTextOutW` class. |
| [EmfExtTextOutW](emfexttextoutw/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfExtTextOutW` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19). It is not used and MUST be ignored on receipt. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/exscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the X axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/eyscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the Y axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/igraphicsmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the graphics mode from the GraphicsMode enumeration (section 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [WEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/wemrtext/) { get; set; } | Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


