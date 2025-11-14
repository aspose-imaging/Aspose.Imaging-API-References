---
title: EmfPlusDrawImage Class
type: docs
weight: 130
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | Initializes a new instance of the [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Gets or sets a value indicating whether the PointData is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38).<br/>            If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39). |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| image_attributes_id | int | r/w | Gets or sets the image attributes identifier<br/>            A 32-bit unsigned integer that specifies the index of an optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table. |
| object_id | System.Byte | r/w | Gets or sets the object identifier.<br/>            The index of an EmfPlusImage object (section 2.2.1.4) in the EMF+<br/>            Object Table, which specifies the image to render. The value MUST be zero to 63, inclusive. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Gets or sets the rect data<br/>            Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the image.<br/>            The portion of the image specified by the SrcRect field is scaled to fit this rectangle. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Gets or sets the source rect<br/>            An EmfPlusRectF object that specifies a portion of the image to be rendered.<br/>            The portion of the image specified by this rectangle is scaled to fit the destination<br/>            rectangle specified by the RectData field. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Gets or sets the source unit<br/>            32-bit signed integer that specifies the units of the SrcRect field.<br/>            It MUST be the UnitTypePixel member of the UnitType enumeration (section 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

Initializes a new instance of the [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

