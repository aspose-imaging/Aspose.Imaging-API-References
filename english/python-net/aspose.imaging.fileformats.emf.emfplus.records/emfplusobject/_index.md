---
title: EmfPlusObject Class
type: docs
weight: 330
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | Initializes a new instance of the [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| is_continuable | bool | r/w | Gets or sets a value indicating whether this instance is continuable.<br/>            Indicates that the object definition continues on in the next EmfPlusObject<br/>            record. This flag is never set in the final record that defines the object. |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | Gets or sets an array of bytes that contains data for the type of object specified in<br/>            the Flags field. The content and format of the data can be different for each object type. See<br/>            the individual object definitions in section 2.2.1 for additional information. |
| object_id | System.Byte | r/w | Gets or sets the object identifier.<br/>            The index in the EMF+ Object Table to associate with the object<br/>            created by this record. The value MUST be zero to 63, inclusive. |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | Gets or sets the type of the object. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| total_object_size | int | r/w | Gets or sets the total size of the object.<br/>            If the record is continuable, when the continue bit is set, this field<br/>            will be present. Continuing objects have multiple EMF+ records starting with<br/>            EmfPlusContineudObjectRecord. Each EmfPlusContinuedObjectRecord will contain a<br/>            TotalObjectSize. Once TotalObjectSize number of bytes has been read, the next EMF+<br/>            record will not be treated as part of the continuing object. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

Initializes a new instance of the [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

