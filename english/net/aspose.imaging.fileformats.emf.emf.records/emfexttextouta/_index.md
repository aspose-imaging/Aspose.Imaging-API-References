---
title: Class EmfExtTextOutA
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtTextOutA class. The EMR_EXTTEXTOUTA record draws an ASCII text string using the current font and text colors
type: docs
weight: 3770
url: /net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
## EmfExtTextOutA class

The EMR_EXTTEXTOUTA record draws an ASCII text string using the current font and text colors.

```csharp
public sealed class EmfExtTextOutA : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfExtTextOutA](emfexttextouta/#constructor)() | Initializes a new instance of the `EmfExtTextOutA` class. |
| [EmfExtTextOutA](emfexttextouta/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfExtTextOutA` class. |

## Properties

| Name | Description |
| --- | --- |
| [AEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/aemrtext/) { get; set; } | Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 8-bit ASCII characters, text attributes, and spacing values. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19). It is not used and MUST be ignored on receipt. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/exscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the X axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/eyscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the Y axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/igraphicsmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the graphics mode from the GraphicsMode enumeration (section 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


