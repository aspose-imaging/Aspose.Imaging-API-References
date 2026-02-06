---
title: Class EmfMetafileHeader
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfMetafileHeader class. The EMR_HEADER record types define the starting points of EMF metafiles and specify properties of the device on which the image in the metafile was created. The information in the header record makes it possible for EMF metafiles to be independent of any specific output device. The value of the Size field can be used to distinguish between the different EMR_HEADER record types listed earlier in this section. There are three possible headers The base header which is the EmfMetafileHeader record. The fixedsize part of this header is 88 bytes and it contains a Header object. The first extension header which is the EmfMetafileHeaderExtension1 record. The fixedsize part of this header is 100 bytes and it contains a Header object and a HeaderExtension1 object section 2.2.10. The second extension header which is the EmfMetafileHeaderExtension2 record. The fixedsize part of this header is 108 bytes and it contains a Header object a HeaderExtension1 object and a HeaderExtension2 object section 2.2.11
type: docs
weight: 3910
url: /net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
## EmfMetafileHeader class

The EMR_HEADER record types define the starting points of EMF metafiles and specify properties of the device on which the image in the metafile was created. The information in the header record makes it possible for EMF metafiles to be independent of any specific output device. The value of the Size field can be used to distinguish between the different EMR_HEADER record types listed earlier in this section. There are three possible headers: The base header, which is the EmfMetafileHeader record. The fixed-size part of this header is 88 bytes, and it contains a Header object. The first extension header, which is the EmfMetafileHeaderExtension1 record. The fixed-size part of this header is 100 bytes, and it contains a Header object and a HeaderExtension1 object (section 2.2.10). The second extension header, which is the EmfMetafileHeaderExtension2 record. The fixed-size part of this header is 108 bytes, and it contains a Header object, a HeaderExtension1 object, and a HeaderExtension2 object (section 2.2.11).

```csharp
public class EmfMetafileHeader : EmfRecord
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfMetafileHeader](emfmetafileheader/#constructor)() | Initializes a new instance of the `EmfMetafileHeader` class. |
| [EmfMetafileHeader](emfmetafileheader/#constructor_1)(EmfMetafileHeader) | Initializes a new instance of the `EmfMetafileHeader` class. |
| [EmfMetafileHeader](emfmetafileheader/#constructor_2)(EmfRecord) | Initializes a new instance of the `EmfMetafileHeader` class. |

## Properties

| Name | Description |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription/) { get; set; } | Gets or sets the EMF description An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. Its location in the record and number of characters are specified by the offDescription and nDescription fields, respectively, in EmfHeader. If the value of either field is zero, no description string is present. |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer/) { get; set; } | Gets or sets the EMF description buffer An optional array of bytes that contains the EMF description string, which is not required to be contiguous with the fixed portion of the EmfMetafileHeader record. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is optional and MUST be ignored. |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader/) { get; set; } | Gets or sets a Header object (section 2.2.9), which contains information about the content and structure of the metafile |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer/) { get; set; } | Gets or sets an optional array of bytes that contains the remainder of the EMF header record. The size of this field MUST be a multiple of 4 bytes |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfRecord](../emfrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


