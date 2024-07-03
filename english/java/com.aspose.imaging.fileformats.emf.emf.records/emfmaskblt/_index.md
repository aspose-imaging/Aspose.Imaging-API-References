---
title: EmfMaskBlt
second_title: Aspose.Imaging for Java API Reference
description: The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle optionally in combination with a brush pattern and with the application of a color mask bitmap according to specified foreground and background raster operations.
type: docs
weight: 69
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfMaskBlt extends EmfBitmapRecordType
```

The EMR\_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern and with the application of a color mask bitmap, according to specified foreground and background raster operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfMaskBlt(EmfRecord source)](#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfMaskBlt` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [getXDest()](#getXDest--) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [setXDest(int value)](#setXDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [getYDest()](#getYDest--) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [setYDest(int value)](#setYDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [getCxDest()](#getCxDest--) | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| [setCxDest(int value)](#setCxDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| [getCyDest()](#getCyDest--) | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| [setCyDest(int value)](#setCyDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| [getRop4()](#getRop4--) | Gets or sets a quaternary raster operation, which specifies ternary raster operations for the foreground and background colors of a bitmap. |
| [setRop4(EmfRop4 value)](#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-) | Gets or sets a quaternary raster operation, which specifies ternary raster operations for the foreground and background colors of a bitmap. |
| [getXSrc()](#getXSrc--) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle. |
| [setXSrc(int value)](#setXSrc-int-) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle. |
| [getYSrc()](#getYSrc--) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle. |
| [setYSrc(int value)](#setYSrc-int-) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle. |
| [getXformSrc()](#getXformSrc--) | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the background color of the source bitmap. |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the background color of the source bitmap. |
| [getUsageSrc()](#getUsageSrc--) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. |
| [getXMask()](#getXMask--) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the mask bitmap. |
| [setXMask(int value)](#setXMask-int-) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the mask bitmap. |
| [getYMask()](#getYMask--) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the mask bitmap. |
| [setYMask(int value)](#setYMask-int-) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the mask bitmap. |
| [getUsageMask()](#getUsageMask--) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the mask bitmap header. |
| [setUsageMask(int value)](#setUsageMask-int-) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the mask bitmap header. |
| [getSourceBitmap()](#getSourceBitmap--) | Gets or sets a buffer containing the source bitmaps, which are not required to be contiguous with the fixed portion of the EMR\_MASKBLT record or with each other. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets a buffer containing the source bitmaps, which are not required to be contiguous with the fixed portion of the EMR\_MASKBLT record or with each other. |
| [getMaskBitmap()](#getMaskBitmap--) | Gets or sets a buffer containing the mask bitmaps, which are not required to be contiguous with the fixed portion of the EMR\_MASKBLT record or with each other. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets a buffer containing the mask bitmaps, which are not required to be contiguous with the fixed portion of the EMR\_MASKBLT record or with each other. |
### EmfMaskBlt(EmfRecord source) {#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMaskBlt(EmfRecord source)
```


Initializes a new instance of the `EmfMaskBlt` class.

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

### getRop4() {#getRop4--}
```
public EmfRop4 getRop4()
```


Gets or sets a quaternary raster operation, which specifies ternary raster operations for the foreground and background colors of a bitmap. These values define how the color data of the source rectangle is to be combined with the color data of the destination rectangle.

**Returns:**
[EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4)
### setRop4(EmfRop4 value) {#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-}
```
public void setRop4(EmfRop4 value)
```


Gets or sets a quaternary raster operation, which specifies ternary raster operations for the foreground and background colors of a bitmap. These values define how the color data of the source rectangle is to be combined with the color data of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4) |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the background color of the source bitmap.

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
```


Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the background color of the source bitmap.

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

### getXMask() {#getXMask--}
```
public int getXMask()
```


Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the mask bitmap.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the mask bitmap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the mask bitmap.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the mask bitmap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the mask bitmap header. This value MUST be in the DIBColors enumeration.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the mask bitmap header. This value MUST be in the DIBColors enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Gets or sets a buffer containing the source bitmaps, which are not required to be contiguous with the fixed portion of the EMR\_MASKBLT record or with each other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Gets or sets a buffer containing the source bitmaps, which are not required to be contiguous with the fixed portion of the EMR\_MASKBLT record or with each other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Gets or sets a buffer containing the mask bitmaps, which are not required to be contiguous with the fixed portion of the EMR\_MASKBLT record or with each other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Gets or sets a buffer containing the mask bitmaps, which are not required to be contiguous with the fixed portion of the EMR\_MASKBLT record or with each other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

