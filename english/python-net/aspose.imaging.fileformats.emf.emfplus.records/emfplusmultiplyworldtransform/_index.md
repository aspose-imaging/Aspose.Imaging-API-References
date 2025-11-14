---
title: EmfPlusMultiplyWorldTransform Class
type: docs
weight: 320
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---

**Summary:** The EmfPlusMultiplyWorldTransform record multiplies the current world space transform by a<br/>            specified transform matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusMultiplyWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusMultiplyWorldTransform(source)](#EmfPlusMultiplyWorldTransform_source_1) | Initializes a new instance of the [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| matrix_data | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the multiplication matrix. |
| post_multiplied_matrix | bool | r | Gets a value indicating whether [post multiplied matrix].<br/>            If set, the transform matrix should be post-multipled. If clear, it should be premultiplied. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusMultiplyWorldTransform(source) {#EmfPlusMultiplyWorldTransform_source_1}


```
 EmfPlusMultiplyWorldTransform(source) 
```

Initializes a new instance of the [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

