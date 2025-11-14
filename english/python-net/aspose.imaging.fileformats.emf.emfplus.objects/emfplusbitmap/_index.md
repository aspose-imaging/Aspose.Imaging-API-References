---
title: EmfPlusBitmap Class
type: docs
weight: 50
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | Initializes a new instance of the EmfPlusBitmap class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | Gets or sets bitmap data<br/>            BitmapData (variable): Variable-length data that defines the bitmap data object specified in the Type field. The<br/>            content and format of the data can be different for every bitmap type. |
| height | int | r/w | Gets or sets bitmap height<br/>            Height (4 bytes): A 32-bit signed integer that specifies the height in pixels of the area occupied by the bitmap.<br/>            If the image is compressed, according to the Type field, this value is undefined and MUST be ignored. |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | Gets or sets pixel format<br/>            PixelFormat (4 bytes): A 32-bit unsigned integer that specifies the format of the pixels that make up the bitmap<br/>            image. The supported pixel formats are specified in the [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) enumeration (section<br/>            2.1.1.25).<br/>            If the image is compressed, according to the Type field, this value is undefined and MUST be ignored. |
| stride | int | r/w | Gets or sets stride of the image<br/>            Stride (4 bytes): A 32-bit signed integer that specifies the byte offset between the beginning of one scan-line and<br/>            the next. This value is the number of bytes per pixel, which is specified in the PixelFormat field, multiplied by<br/>            the width in pixels, which is specified in the Width field. The value of this field MUST be a multiple of four.<br/>            If the image is compressed, according to the Type field, this value is undefined and MUST be ignored. |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | Gets or sets type of the image<br/>            Type (4 bytes): A 32-bit unsigned integer that specifies the type of data in the BitmapData field. This value MUST<br/>            be defined in the [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) enumeration (section 2.1.1.2). |
| width | int | r/w | Gets or sets image Width<br/>            Width (4 bytes): A 32-bit signed integer that specifies the width in pixels of the area occupied by the bitmap.<br/>            If the image is compressed, according to the Type field, this value is undefined and MUST be ignored. |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

Initializes a new instance of the EmfPlusBitmap class

