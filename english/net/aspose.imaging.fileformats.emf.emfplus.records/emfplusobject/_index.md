---
title: Class EmfPlusObject
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusObject class. The EmfPlusObject record specifies an object for use in graphics operations. The object definition can span multiple records which is indicated by the value of the Flags field
type: docs
weight: 6280
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
## EmfPlusObject class

The EmfPlusObject record specifies an object for use in graphics operations. The object definition can span multiple records, which is indicated by the value of the Flags field.

```csharp
public sealed class EmfPlusObject : EmfPlusObjectRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusObject](emfplusobject/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusObject` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [IsContinuable](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/iscontinuable/) { get; set; } | Gets or sets a value indicating whether this instance is continuable. Indicates that the object definition continues on in the next EmfPlusObject record. This flag is never set in the final record that defines the object. |
| [ObjectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectdata/) { get; set; } | Gets or sets an array of bytes that contains data for the type of object specified in the Flags field. The content and format of the data can be different for each object type. See the individual object definitions in section 2.2.1 for additional information. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectid/) { get; set; } | Gets or sets the object identifier. The index in the EMF+ Object Table to associate with the object created by this record. The value MUST be zero to 63, inclusive. |
| [ObjectType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objecttype/) { get; set; } | Gets or sets the type of the object. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [TotalObjectSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/totalobjectsize/) { get; set; } | Gets or sets the total size of the object. If the record is continuable, when the continue bit is set, this field will be present. Continuing objects have multiple EMF+ records starting with EmfPlusContineudObjectRecord. Each EmfPlusContinuedObjectRecord will contain a TotalObjectSize. Once TotalObjectSize number of bytes has been read, the next EMF+ record will not be treated as part of the continuing object. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

## Remarks

The EmfPlusObject record is generic; it is used for all types of objects. Values that are specific to particular object types are contained in the ObjectData field. A conceptual model for managing graphics objects is described in Managing Graphics Objects (section 3.1.2).

### See Also

* class [EmfPlusObjectRecordType](../emfplusobjectrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


