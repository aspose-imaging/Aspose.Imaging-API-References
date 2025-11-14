---
title: EmfPlusDrawImagePoints Class
type: docs
weight: 140
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | Initializes a new instance of the [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | Gets or sets a value indicating whether [applying an effect].<br/>            This bit indicates that the rendering of the image includes applying an effect.<br/>            If set, an object of the Effect class MUST have been specified in an earlier<br/>            EmfPlusSerializableObject record (section 2.3.5.2). |
| compressed | bool | r/w | Gets or sets a value indicating whether the PointData is compressed.<br/>            This bit indicates whether the PointData field specifies compressed data.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit integer<br/>            coordinates. If clear, PointData specifies absolute locations in the coordinate space with<br/>            32-bit floating-point coordinates.<br/>            Note If the P flag (below) is set, this flag is undefined and MUST be ignored. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| image_attributes_id | int | r/w | Gets or sets a 32-bit unsigned integer that contains the index of the<br/>            optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table. |
| object_id | System.Byte | r/w | Gets or sets the object identifier.<br/>            The index of an EmfPlusImage object (section 2.2.1.4) in the EMF+<br/>            Object Table, which specifies the image to render. The value MUST be zero to 63, inclusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets an array of Count points that specify three points of a parallelogram.<br/>            The three points represent the upper-left, upper-right, and lower-left corners of the<br/>            parallelogram. The fourth point of the parallelogram is extrapolated from the first three. The<br/>            portion of the image specified by the SrcRect field SHOULD have scaling and shearing<br/>            transforms applied if necessary to fit inside the parallelogram. |
| relative | bool | r/w | Gets or sets a value indicating whether this [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) is relative.<br/>            This bit indicates whether the PointData field specifies relative or absolute locations.<br/>            If set, each element in PointData specifies a location in the coordinate space that is<br/>            relative to the location specified by the previous element in the array. In the case of the<br/>            first element in PointData, a previous location at coordinates (0,0) is assumed. If clear,<br/>            PointData specifies absolute locations according to the C flag.<br/>            Note If this flag is set, the C flag (above) is undefined and MUST be ignored. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines a portion of the image to be rendered. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Gets or sets a 32-bit signed integer that defines the units of the SrcRect field. It MUST<br/>            be the UnitPixel value of the UnitType enumeration (section 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

Initializes a new instance of the [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

