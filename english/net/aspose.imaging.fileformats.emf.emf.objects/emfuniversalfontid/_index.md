---
title: Class EmfUniversalFontId
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfUniversalFontId class. The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles
type: docs
weight: 3270
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
## EmfUniversalFontId class

The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

```csharp
public sealed class EmfUniversalFontId : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfUniversalFontId](emfuniversalfontid/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Checksum](../../aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/checksum/) { get; set; } | Gets or sets a 32-bit unsigned integer that is the checksum of the font. The checksum value has the following meanings. 0x00000000 The object is a device font. 0x00000001 The object is a Type 1 font that has been installed on the client machine and is enumerated by the PostScript printer driver as a device font. 0x00000002 The object is not a font but is a Type 1 rasterizer. 3 ≤ value The object is a bitmap, vector, or TrueType font, or a Type 1 rasterized font that was created by a Type 1 rasterizer. |
| [Index](../../aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/index/) { get; set; } | Gets or sets a 32-bit unsigned integer that is an index associated with the font object. The meaning of this field is determined by the type of font. |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


