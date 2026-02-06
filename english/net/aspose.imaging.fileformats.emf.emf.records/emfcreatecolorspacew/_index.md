---
title: Class EmfCreateColorSpaceW
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateColorSpaceW class. The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with a name consisting of Unicode characters
type: docs
weight: 3580
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
## EmfCreateColorSpaceW class

The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with a name consisting of Unicode characters.

```csharp
public sealed class EmfCreateColorSpaceW : EmfObjectCreationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCreateColorSpaceW](emfcreatecolorspacew/)(EmfRecord) | Initializes a new instance of the `EmfCreateColorSpaceW` class. |

## Properties

| Name | Description |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/cbdata/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/data/) { get; set; } | Gets or sets an optional array of bytes that specifies color profile data. |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/dwflags/) { get; set; } | Gets or sets a 32-bit unsigned integer that provides information about the data in this record. |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/ihcs/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space object in the EMF object table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified. |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/lcs/) { get; set; } | Gets or sets a WMF LogColorSpaceW object ([MS-WMF] section 2.2.2.12) that can specify the name of a color profile in Unicode UTF16-LE characters |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The logical color space object defined by this record can be selected into the playback device context by an EMR_SETCOLORSPACE record (section 2.3.8.7), which defines the logical color space to use in subsequent graphics operations.

### See Also

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


