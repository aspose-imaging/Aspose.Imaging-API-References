---
title: EmfPlusBitmapData Class
type: docs
weight: 60
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---

**Summary:** The EmfPlusBitmapData object specifies a bitmap image with pixel data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmapData

**Inheritance:** EmfPlusBaseBitmapData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData__1) | Initializes a new instance of the EmfPlusBitmapData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colors | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Gets or sets the palette colors <br/>            Colors (variable): An optional [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) object (section 2.2.2.28), which specifies the palette<br/>            of colors used in the pixel data. This field MUST be present if the I flag is set in the PixelFormat field of the<br/>            [EmfPlusBitmap](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/) object. |
| pixel_data | System.Byte | r/w | Gets or sets pixel data <br/>            PixelData (variable): An array of bytes that specify the pixel data. The size and format of this data can be<br/>            computed from fields in the EmfPlusBitmap object, including the pixel format from the<br/>            [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) enumeration (section 2.1.1.25). |


### Constructor: EmfPlusBitmapData() {#EmfPlusBitmapData__1}


```
 EmfPlusBitmapData() 
```

Initializes a new instance of the EmfPlusBitmapData class

