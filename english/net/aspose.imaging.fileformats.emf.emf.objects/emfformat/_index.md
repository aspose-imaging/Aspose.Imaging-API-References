---
title: Class EmfFormat
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfFormat class. The EmrFormat object contains information that identifies the format of image data in an EMR_COMMENT_MULTIFORMATS recordsection 2.3.3.4.3
type: docs
weight: 3050
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
## EmfFormat class

The EmrFormat object contains information that identifies the format of image data in an EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

```csharp
public sealed class EmfFormat : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfFormat](emfformat/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [OffData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/offdata/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the offset to the data from the start of the identifier field in an EMR_COMMENT_PUBLIC record (section 2.3.3.4). The offset MUST be 32-bit aligned. |
| [Signature](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/signature/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the format of the image data. This value MUST be in the FormatSignature enumeration (section 2.1.14). |
| [SizeData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/sizedata/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of the data in bytes |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/version/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the format version number. If the Signature field specifies encapsulated PostScript (EPS), this value MUST be 0x00000001; otherwise, this value MUST be ignored |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


