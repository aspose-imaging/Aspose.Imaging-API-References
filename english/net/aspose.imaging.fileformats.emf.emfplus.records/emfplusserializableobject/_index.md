---
title: Class EmfPlusSerializableObject
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSerializableObject class. The EmfPlusSerializableObject record defines an image effects parameter block that has been serialized into a data buffer
type: docs
weight: 6390
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
## EmfPlusSerializableObject class

The EmfPlusSerializableObject record defines an image effects parameter block that has been serialized into a data buffer.

```csharp
public sealed class EmfPlusSerializableObject : EmfPlusObjectRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSerializableObject](emfplusserializableobject/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSerializableObject` class. |

## Properties

| Name | Description |
| --- | --- |
| [Buffer](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/buffer/) { get; set; } | Gets or sets an array of BufferSize bytes that contain the serialized image effects parameter block that corresponds to the GUID in the ObjectGUID field. This MUST be one of the Image Effects objects (section 2.2.3). |
| [BufferSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/buffersize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size in bytes of the 32-bitaligned Buffer field. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero and MUST be ignored upon receipt. |
| [ImageEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/imageeffect/) { get; set; } | Gets or sets the image effect. |
| [ObjectGuid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/objectguid/) { get; set; } | Gets or sets the GUID packet representation value ([MS-DTYP] section 2.3.4.2) for the image effect. This MUST correspond to one of the ImageEffects identifiers (section 2.1.3.1). |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusObjectRecordType](../emfplusobjectrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


