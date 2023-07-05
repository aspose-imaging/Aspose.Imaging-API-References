---
title: EmfPlusSerializableObject Class
type: docs
weight: 440
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---

The EmfPlusSerializableObject record defines an image effects parameter block that has been<br/>            serialized into a data buffer.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSerializableObject

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusSerializableObject type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusSerializableObject(source)|Initializes a new instance of the EmfPlusSerializableObject class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero<br/>            and MUST be ignored upon receipt.|
|size|  |
|data_size|  |
|object_guid|Gets or sets the GUID packet representation value ([MS-DTYP] section 2.3.4.2)<br/>            for the image effect. This MUST correspond to one of the ImageEffects identifiers (section 2.1.3.1).|
|buffer_size|Gets or sets a 32-bit unsigned integer that specifies the size in bytes of the 32-bitaligned Buffer field.|
|buffer|Gets or sets an array of BufferSize bytes that contain the serialized image effects<br/>            parameter block that corresponds to the GUID in the ObjectGUID field. This MUST be one of<br/>            the Image Effects objects (section 2.2.3).|
|image_effect|Gets or sets the image effect.|
