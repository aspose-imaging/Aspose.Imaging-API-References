---
title: EmfStretchDiBits Class
type: docs
weight: 1410
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---

**Summary:** The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster <br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchDiBits

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfStretchDiBits(source)](#EmfStretchDiBits_source_1) | Initializes a new instance of the [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Gets or sets a 32-bit unsigned integer that specifies a raster operation <br/>            code. These codes define how the color data of the source rectangle is to be combined with <br/>            the color data of the destination rectangle and optionally a brush pattern, to achieve the final color. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the <br/>            destination bounding rectangle in device units. |
| cx_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| cx_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle. |
| cy_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| cy_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle. |
| size | int | r/w | Gets or sets the size of the record |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Gets or sets a buffer containing the source bitmap, which is not required to be <br/>            contiguous with the fixed portion of the EMR_STRETCHDIBITS record. Accordingly, fields in <br/>            this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9). |
| x_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the destination rectangle. |
| x_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the upper-left <br/>            corner of the source rectangle. |
| y_dest | int | r/w | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the destination rectangle. |
| y_src | int | r/w | Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the upper-left <br/>            corner of the source rectangle. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfStretchDiBits(source) {#EmfStretchDiBits_source_1}


```
 EmfStretchDiBits(source) 
```

Initializes a new instance of the [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/) class.

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


