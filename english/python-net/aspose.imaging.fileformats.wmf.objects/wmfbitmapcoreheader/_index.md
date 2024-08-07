---
title: WmfBitmapCoreHeader Class
type: docs
weight: 60
url: /python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapcoreheader/
---

**Summary:** The BitmapCoreHeader Object contains information about the dimensions<br/>                and color format of a device-independent bitmap(DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapCoreHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfBitmapCoreHeader()](#WmfBitmapCoreHeader__1) | Initializes a new instance of the WmfBitmapCoreHeader class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | Gets or sets a 16-bit unsigned integer that defines the format of<br/>                each pixel, and the maximum number of colors in the DIB. This value<br/>                MUST be in the [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) Enumeration (section 2.1.1.3). |
| header_size | int | r/w | Gets or sets a 32-bit unsigned integer that defines the size of this<br/>                object, in bytes. |
| height | short | r/w | Gets or sets a 16-bit unsigned integer that defines the<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapcoreheader/) of the DIB, in pixels |
| planes | short | r/w | Gets or sets a 16-bit unsigned integer that defines the number of<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) for the target device. This value MUST be<br/>                0x0001. |
| width | short | r/w | Gets or sets a 16-bit unsigned integer that defines the<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapcoreheader/) of the DIB, in pixels |


### Constructor: WmfBitmapCoreHeader() {#WmfBitmapCoreHeader__1}


```
 WmfBitmapCoreHeader() 
```

Initializes a new instance of the WmfBitmapCoreHeader class

