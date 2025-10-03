---
title: EmfAlphaBlend Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---

**Summary:** The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, including alpha transparency data, according to a specified blending operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAlphaBlend

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfAlphaBlend(source)](#EmfAlphaBlend_source_1) | Initializes a new instance of the [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bk_src_argb_32_color | int | r/w | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the<br/>            background color of the source bitmap. |
| blend_function | [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) | r/w | Gets or sets a structure that specifies the blending operations for source and <br/>            destination bitmaps |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the <br/>            destination bounding rectangle in device units. |
| cx_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical width of the destination <br/>            rectangle. This value MUST be greater than zero. |
| cx_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle. <br/>            This value MUST be greater than zero. |
| cy_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical height of the destination <br/>            rectangle. This value MUST be greater than zero. |
| cy_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical height of the source <br/>            rectangle. This value MUST be greater than zero. |
| size | int | r/w | Gets or sets the size of the record |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Gets or sets a buffer containing the source bitmap, which is not required to be <br/>            contiguous with the fixed portion of the EMR_ALPHABLEND record. Accordingly, fields in this <br/>            buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9). |
| x_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the destination rectangle. |
| x_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the source rectangle. |
| xform_sr | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| y_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the destination rectangle. |
| y_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the source rectangle. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfAlphaBlend(source) {#EmfAlphaBlend_source_1}


```
 EmfAlphaBlend(source) 
```

Initializes a new instance of the [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | The source. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | The source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


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
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


