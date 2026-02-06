---
title: Class EmfHeaderObject
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfHeaderObject class. The Header object defines the EMF metafile header. It specifies properties of the device on which the image in the metafile was created
type: docs
weight: 3100
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
## EmfHeaderObject class

The Header object defines the EMF metafile header. It specifies properties of the device on which the image in the metafile was created.

```csharp
public class EmfHeaderObject : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfHeaderObject](emfheaderobject/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive bounds in device units of the smallest rectangle that can be drawn around the image stored in the metafile |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the size of the metafile, in bytes. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device/) { get; set; } | Gets or sets a WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame/) { get; set; } | Gets or sets a WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter units, of a rectangle that surrounds the image stored in the metafile |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters/) { get; set; } | Gets or sets a WMF SizeL object that specifies the size of the reference device, in millimeters |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of characters in the array that contains the description of the metafile's contents. This is zero if there is no description string. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of entries in the metafile palette. The palette is located in the EMR_EOF record |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the offset from the beginning of this record to the array that contains the description of the metafile's contents |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of records in the metafile |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the record signature. This MUST be ENHMETA_SIGNATURE, from the FormatSignature enumeration (section 2.1.14). |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved/) { get; set; } | Gets or sets a 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid/) { get; } | Gets a value indicating whether this `EmfHeaderObject` is valid. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version/) { get; set; } | Gets or sets Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. This SHOULD be 0x00010000 |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


