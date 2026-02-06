---
title: Class EmfMetafileHeaderExtension2
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfMetafileHeaderExtension2 class. The EmfMetafileHeaderExtension2 record is the header record used in the second extension to EMF metafiles. Following the EmfHeaderExtension2 field the remaining fields are optional and can be present in any order
type: docs
weight: 3930
url: /net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/
---
## EmfMetafileHeaderExtension2 class

The EmfMetafileHeaderExtension2 record is the header record used in the second extension to EMF metafiles. Following the EmfHeaderExtension2 field, the remaining fields are optional and can be present in any order.

```csharp
public sealed class EmfMetafileHeaderExtension2 : EmfMetafileHeaderExtension1
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfMetafileHeaderExtension2](emfmetafileheaderextension2/#constructor)(EmfMetafileHeaderExtension1) | Initializes a new instance of the `EmfMetafileHeaderExtension2` class. |
| [EmfMetafileHeaderExtension2](emfmetafileheaderextension2/#constructor_1)(EmfMetafileHeaderExtension2) | Initializes a new instance of the `EmfMetafileHeaderExtension2` class. |

## Properties

| Name | Description |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription/) { get; set; } | Gets or sets the EMF description An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. Its location in the record and number of characters are specified by the offDescription and nDescription fields, respectively, in EmfHeader. If the value of either field is zero, no description string is present. |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer/) { get; set; } | Gets or sets the EMF description buffer An optional array of bytes that contains the EMF description string, which is not required to be contiguous with the fixed portion of the EmfMetafileHeader record. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is optional and MUST be ignored. |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader/) { get; set; } | Gets or sets a Header object (section 2.2.9), which contains information about the content and structure of the metafile |
| [EmfHeaderExtension1](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfheaderextension1/) { get; set; } | Gets or sets a HeaderExtension1 object, which specifies additional information about the image in the metafile. |
| [EmfHeaderExtension2](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/emfheaderextension2/) { get; set; } | Gets or sets a HeaderExtension2 object, which specifies additional information about the image in the metafile |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer/) { get; set; } | Gets or sets an optional array of bytes that contains the remainder of the EMF header record. The size of this field MUST be a multiple of 4 bytes |
| [EmfPixelFormatBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfpixelformatbuffer/) { get; set; } | Gets or sets an optional array of bytes that contains the EMF pixel format descriptor, which is not required to be contiguous with the fixed portion of the EmfMetafileHeaderExtension1 record or with the EMF description string. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is optional and MUST be ignored |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfMetafileHeaderExtension1](../emfmetafileheaderextension1/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


