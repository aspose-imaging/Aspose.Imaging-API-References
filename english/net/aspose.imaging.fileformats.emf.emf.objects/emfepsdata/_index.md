---
title: Class EmfEpsData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfEpsData class. The EpsData object is a container for EPS data
type: docs
weight: 3040
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
## EmfEpsData class

The EpsData object is a container for EPS data

```csharp
public sealed class EmfEpsData : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfEpsData](emfepsdata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Points](../../aspose.imaging.fileformats.emf.emf.objects/emfepsdata/points/) { get; set; } | Gets or sets an array of three Point28_4 objects (section 2.2.23) that defines the coordinates of the output parallelogram using 28.4 bit FIX notation |
| [PostScriptData](../../aspose.imaging.fileformats.emf.emf.objects/emfepsdata/postscriptdata/) { get; set; } | Gets or sets an array of bytes of PostScript data. The length of this array can be computed from the SizeData field. This data MAY be used to render an image. |
| [SizeData](../../aspose.imaging.fileformats.emf.emf.objects/emfepsdata/sizedata/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the total size of this object, in bytes |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfepsdata/version/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the PostScript language level. This value MUST be 0x00000001 |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


