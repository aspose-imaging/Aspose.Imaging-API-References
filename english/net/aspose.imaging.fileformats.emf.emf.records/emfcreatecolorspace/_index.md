---
title: Class EmfCreateColorSpace
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateColorSpace class. The EMR_CREATECOLORSPACE record creates a logical color space object from a color profile with a name consisting of ASCII characters
type: docs
weight: 3570
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
## EmfCreateColorSpace class

The EMR_CREATECOLORSPACE record creates a logical color space object from a color profile with a name consisting of ASCII characters.

```csharp
public sealed class EmfCreateColorSpace : EmfObjectCreationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCreateColorSpace](emfcreatecolorspace/)(EmfRecord) | Initializes a new instance of the `EmfCreateColorSpace` class. |

## Properties

| Name | Description |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/ihcs/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space object in the EMF object table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified. |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/lcs/) { get; set; } | Gets or sets a WMF LogColorSpace object ([MS-WMF] section 2.2.2.11), which can specify the name of a color profile in ASCII characters. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The logical color space object defined by this record can be selected into the playback device context by an EMR_SETCOLORSPACE record (section 2.3.8.7), which defines the logical color space to use in subsequent graphics operations.

### See Also

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


