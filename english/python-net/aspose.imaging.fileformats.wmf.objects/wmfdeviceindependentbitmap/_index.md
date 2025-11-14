---
title: WmfDeviceIndependentBitmap Class
type: docs
weight: 180
url: /python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | Initializes a new instance of the WmfDeviceIndependentBitmap class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | Gets or sets an array of bytes that define the image. The size and<br/>                format of this data is determined by information in the<br/>                DIBHeaderInfo field. |
| cached_image | System.Byte | r/w | Gets or sets the cached raster image. |
| colors_data | System.Byte | r/w | Gets or sets an optional array of either RGBQuad Objects (section<br/>                2.2.2.20) or 16-bit unsigned integers that define a color table. The<br/>                size and contents of this field SHOULD be determined from the<br/>                metafile record or object that contains this DeviceIndependentBitmap<br/>                and from information in the DIBHeaderInfo field. See ColorUsage<br/>                Enumeration (section 2.1.1.6) and BitCount Enumeration (section<br/>                2.1.1.3) for additional details |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | Gets or sets either a BitmapCoreHeader Object (section 2.2.2.2) or a<br/>                BitmapInfoHeader Object (section 2.2.2.3) that specifies information<br/>                about the image |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

Initializes a new instance of the WmfDeviceIndependentBitmap class

