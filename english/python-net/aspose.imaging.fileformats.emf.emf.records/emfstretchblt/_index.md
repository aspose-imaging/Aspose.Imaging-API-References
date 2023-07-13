---
title: EmfStretchBlt Class
type: docs
weight: 1370
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---

The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster<br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchBlt

**Inheritance:** EmfBitmapRecordType

**Aspose.Imaging Version:** 23.6

The EmfStretchBlt type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfStretchBlt(source)](#EmfStretchBlt_source_0) | Initializes a new instance of the [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) class. |
| [EmfStretchBlt()](#EmfStretchBlt__1) | Initializes a new instance of the [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the <br/>            destination bounding rectangle in device units. |
| x_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the destination rectangle. |
| y_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the destination rectangle. |
| cx_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| cy_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the raster operation <br/>            code. This code defines how the color data of the source rectangle is to be combined with the <br/>            color data of the destination rectangle and optionally a brush pattern, to achieve the final color |
| x_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the source rectangle. |
| y_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the source rectangle. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix) | r/w | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| argb_32_bk_color_src | int | r/w | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the <br/>            background color of the source bitmap. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9). |
| cx_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle. |
| cy_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical height of the source rectangle. |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Gets or sets a buffer containing the source bitmap, which is not required to be <br/>            contiguous with the fixed portion of the EMR_STRETCHBLT record. Accordingly, fields in this <br/>            buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets the source rect. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets the dest rect. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfStretchBlt(source) {#EmfStretchBlt_source_0}


```
 EmfStretchBlt(source) 
```

Initializes a new instance of the [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfStretchBlt() {#EmfStretchBlt__1}


```
 EmfStretchBlt() 
```

Initializes a new instance of the [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) class.

### create_from_record(source)  [static] {#create_from_record_source_2}


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


### create_from_type(type)  [static] {#create_from_type_type_3}


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


