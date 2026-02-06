---
title: Class EmfHeaderExtension2
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfHeaderExtension2 class. The HeaderExtension2 object defines the second extension to the EMF metafile header. It adds the ability to measure device surfaces in micrometers which enhances the resolution and scalability of EMF metafiles
type: docs
weight: 3090
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---
## EmfHeaderExtension2 class

The HeaderExtension2 object defines the second extension to the EMF metafile header. It adds the ability to measure device surfaces in micrometers, which enhances the resolution and scalability of EMF metafiles.

```csharp
public sealed class EmfHeaderExtension2 : EmfHeaderObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfHeaderExtension2](emfheaderextension2/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive bounds in device units of the smallest rectangle that can be drawn around the image stored in the metafile |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the size of the metafile, in bytes. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device/) { get; set; } | Gets or sets a WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame/) { get; set; } | Gets or sets a WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter units, of a rectangle that surrounds the image stored in the metafile |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile |
| [MicrometersX](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersx/) { get; set; } | Gets or sets the 32-bit horizontal size of the display device for which the metafile image was generated, in micrometers |
| [MicrometersY](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersy/) { get; set; } | Gets or sets the 32-bit vertical size of the display device for which the metafile image was generated, in micrometers. |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters/) { get; set; } | Gets or sets a WMF SizeL object that specifies the size of the reference device, in millimeters |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of characters in the array that contains the description of the metafile's contents. This is zero if there is no description string. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of entries in the metafile palette. The palette is located in the EMR_EOF record |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the offset from the beginning of this record to the array that contains the description of the metafile's contents |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of records in the metafile |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the record signature. This MUST be ENHMETA_SIGNATURE, from the FormatSignature enumeration (section 2.1.14). |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved/) { get; set; } | Gets or sets a 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid/) { get; } | Gets a value indicating whether this [`EmfHeaderObject`](../emfheaderobject/) is valid. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version/) { get; set; } | Gets or sets Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. This SHOULD be 0x00010000 |

### See Also

* class [EmfHeaderObject](../emfheaderobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


