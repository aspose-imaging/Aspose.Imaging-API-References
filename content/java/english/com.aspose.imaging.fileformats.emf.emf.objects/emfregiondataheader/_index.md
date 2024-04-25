---
title: EmfRegionDataHeader
second_title: Aspose.Imaging for Java API Reference
description: The RegionDataHeader object describes the properties of a RegionData object.
type: docs
weight: 34
url: /com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

The RegionDataHeader object describes the properties of a RegionData object.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Gets a 32-bit unsigned integer that specifies the size of this object in bytes. |
| [setSize(int value)](#setSize-int-) | Sets a 32-bit unsigned integer that specifies the size of this object in bytes. |
| [getType()](#getType--) | Gets a 32-bit unsigned integer that specifies the region type. |
| [setType(int value)](#setType-int-) | Sets a 32-bit unsigned integer that specifies the region type. |
| [getCountRects()](#getCountRects--) | Gets a 32-bit unsigned integer that specifies the number of rectangles in this region. |
| [setCountRects(int value)](#setCountRects-int-) | Sets a 32-bit unsigned integer that specifies the number of rectangles in this region. |
| [getRgnSize()](#getRgnSize--) | Gets a 32-bit unsigned integer that specifies the size of the buffer of rectangles in bytes. |
| [setRgnSize(int value)](#setRgnSize-int-) | Sets a 32-bit unsigned integer that specifies the size of the buffer of rectangles in bytes. |
| [getBounds()](#getBounds--) | Gets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounds of the region. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounds of the region. |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


Gets a 32-bit unsigned integer that specifies the size of this object in bytes. This MUST be 0x00000020.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Sets a 32-bit unsigned integer that specifies the size of this object in bytes. This MUST be 0x00000020.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public int getType()
```


Gets a 32-bit unsigned integer that specifies the region type. This SHOULD be RDH\_RECTANGLES (0x00000001).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Sets a 32-bit unsigned integer that specifies the region type. This SHOULD be RDH\_RECTANGLES (0x00000001).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


Gets a 32-bit unsigned integer that specifies the number of rectangles in this region.

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


Sets a 32-bit unsigned integer that specifies the number of rectangles in this region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


Gets a 32-bit unsigned integer that specifies the size of the buffer of rectangles in bytes.

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


Sets a 32-bit unsigned integer that specifies the size of the buffer of rectangles in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounds of the region.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounds of the region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

