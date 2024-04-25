---
title: EmfStretchDiBits
second_title: Aspose.Imaging for Java API Reference
description: The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a destination rectangle optionally in combination with a brush pattern according to a specified raster operation stretching or compressing the output to fit the dimensions of the destination if necessary.
type: docs
weight: 147
url: /com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

The EMR\_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

This record supports source images in JPEG and PNG formats. The Compression field in the source bitmap header specifies the image format. If the signs of the source and destination height and width fields differ, this record specifies a mirror-image copy of the source bitmap to the destination. That is, if cxSrc and cxDest have different signs, a mirror image of the source bitmap along the x-axis is specified. If cySrc and cyDest have different signs, a mirror image of the source bitmap along the y-axis is specified.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfStretchDiBits` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [getXDest()](#getXDest--) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [setXDest(int value)](#setXDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [getYDest()](#getYDest--) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [setYDest(int value)](#setYDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [getXSrc()](#getXSrc--) | Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the upper-left corner of the source rectangle. |
| [setXSrc(int value)](#setXSrc-int-) | Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the upper-left corner of the source rectangle. |
| [getYSrc()](#getYSrc--) | Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the upper-left corner of the source rectangle. |
| [setYSrc(int value)](#setYSrc-int-) | Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the upper-left corner of the source rectangle. |
| [getCxSrc()](#getCxSrc--) | Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle. |
| [setCxSrc(int value)](#setCxSrc-int-) | Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle. |
| [getCySrc()](#getCySrc--) | Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle. |
| [setCySrc(int value)](#setCySrc-int-) | Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle. |
| [getUsageSrc()](#getUsageSrc--) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Gets or sets a 32-bit unsigned integer that specifies a raster operation code. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Gets or sets a 32-bit unsigned integer that specifies a raster operation code. |
| [getCxDest()](#getCxDest--) | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| [setCxDest(int value)](#setCxDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| [getCyDest()](#getCyDest--) | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| [setCyDest(int value)](#setCyDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| [getSourceBitmap()](#getSourceBitmap--) | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR\_STRETCHDIBITS record. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR\_STRETCHDIBITS record. |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


Initializes a new instance of the `EmfStretchDiBits` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the upper-left corner of the source rectangle.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the upper-left corner of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the upper-left corner of the source rectangle.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the upper-left corner of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Gets or sets a 32-bit unsigned integer that specifies a raster operation code. These codes define how the color data of the source rectangle is to be combined with the color data of the destination rectangle and optionally a brush pattern, to achieve the final color.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Gets or sets a 32-bit unsigned integer that specifies a raster operation code. These codes define how the color data of the source rectangle is to be combined with the color data of the destination rectangle and optionally a brush pattern, to achieve the final color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR\_STRETCHDIBITS record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR\_STRETCHDIBITS record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

