---
title: EmfPlgBlt Class
type: docs
weight: 740
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

**Aspose.Imaging Version:** 23.6

The EmfPlgBlt type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_0) | Initializes a new instance of the [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the <br/>            bounding rectangle, in device units, for output to the destination. |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point) | r/w | Gets or sets an array of three WMF PointL objects ([MS-WMF] section 2.2.2.15) that <br/>            specifies three corners a parallelogram destination area for the block transfer.<br/>            The upper-left corner of the source rectangle is mapped to the first point in this array, the <br/>            upper-right corner to the second point, and the lower-left corner to the third point. The lower-right corner of the source rectangle is mapped to the implicit fourth point in the <br/>            parallelogram, which is computed from the first three points (A, B, and C) by treating them as <br/>            vectors. <br/>            D = B + C A |
| x_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the source rectangle. |
| y_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the source rectangle. |
| cx_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle. |
| cy_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical height of the source rectangle. |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix) | r/w | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| bk_src_argb_32_color | int | r/w | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the <br/>            background color of the source bitmap. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration |
| x_mask | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the mask bitmap. |
| y_mask | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the mask bitmap. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the mask bitmap header. This value MUST be in the DIBColors enumeration. |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Gets or sets a buffer containing the source bitmap, which are not <br/>            required to be contiguous with the fixed portion of the EMR_PLGBLT record or with each other. <br/>            Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Gets or sets a buffer containing the mask bitmap, which are not <br/>            required to be contiguous with the fixed portion of the EMR_PLGBLT record or with each other. <br/>            Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfPlgBlt(source) {#EmfPlgBlt_source_0}


```
 EmfPlgBlt(source) 
```

Initializes a new instance of the [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |


### create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | The record type. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |


