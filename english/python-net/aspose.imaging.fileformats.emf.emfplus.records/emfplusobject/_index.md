---
title: EmfPlusObject Class
type: docs
weight: 330
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfPlusObject type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusObject(source)|Initializes a new instance of the EmfPlusObject class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|is_continuable|Gets or sets a value indicating whether this instance is continuable.<br/>            Indicates that the object definition continues on in the next EmfPlusObject<br/>            record. This flag is never set in the final record that defines the object.|
|object_type|Gets or sets the type of the object.|
|object_id|Gets or sets the object identifier.<br/>            The index in the EMF+ Object Table to associate with the object<br/>            created by this record. The value MUST be zero to 63, inclusive.|
|total_object_size|Gets or sets the total size of the object.<br/>            If the record is continuable, when the continue bit is set, this field<br/>            will be present. Continuing objects have multiple EMF+ records starting with<br/>            EmfPlusContineudObjectRecord. Each EmfPlusContinuedObjectRecord will contain a<br/>            TotalObjectSize. Once TotalObjectSize number of bytes has been read, the next EMF+<br/>            record will not be treated as part of the continuing object.|
|object_data|Gets or sets an array of bytes that contains data for the type of object specified in<br/>            the Flags field. The content and format of the data can be different for each object type. See<br/>            the individual object definitions in section 2.2.1 for additional information.|
