---
title: EmfFrameRgn
second_title: Aspose.Imaging for Java API Reference
description: The EMR_FRAMERGN record draws a border around the specified region using the specified brush.
type: docs
weight: 61
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

The EMR\_FRAMERGN record draws a border around the specified region using the specified brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfFrameRgn` class. |
| [EmfFrameRgn()](#EmfFrameRgn--) | Initializes a new instance of the [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle. |
| [getRgnDataSize()](#getRgnDataSize--) | Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| [getIhBrush()](#getIhBrush--) | Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index. |
| [setIhBrush(int value)](#setIhBrush-int-) | Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index. |
| [getWidth()](#getWidth--) | Gets or sets a 32-bit signed integer that specifies the width of the vertical brush stroke, in logical units. |
| [setWidth(int value)](#setWidth-int-) | Gets or sets a 32-bit signed integer that specifies the width of the vertical brush stroke, in logical units. |
| [getHeight()](#getHeight--) | Gets or sets a 32-bit signed integer that specifies the height of the horizontal brush stroke, in logical units. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets a 32-bit signed integer that specifies the height of the horizontal brush stroke, in logical units. |
| [getRgnData()](#getRgnData--) | Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object, in logical units |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object, in logical units |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


Initializes a new instance of the `EmfFrameRgn` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


Initializes a new instance of the [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn) class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets or sets a 32-bit signed integer that specifies the width of the vertical brush stroke, in logical units.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Gets or sets a 32-bit signed integer that specifies the width of the vertical brush stroke, in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets a 32-bit signed integer that specifies the height of the horizontal brush stroke, in logical units.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Gets or sets a 32-bit signed integer that specifies the height of the horizontal brush stroke, in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object, in logical units

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object, in logical units

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

