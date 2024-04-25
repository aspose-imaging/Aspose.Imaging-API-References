---
title: WmfRegion
second_title: Aspose.Imaging for Java API Reference
description: The Region Object defines a potentially non-rectilinear shape defined by     an array of scanlines.
type: docs
weight: 62
url: /com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

The Region Object defines a potentially non-rectilinear shape defined by an array of scanlines.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | Gets or sets the next in chain. |
| [setNextInChain(short value)](#setNextInChain-short-) | Gets or sets the next in chain. |
| [getObjectType()](#getObjectType--) | Gets or sets the type of the object. |
| [setObjectType(short value)](#setObjectType-short-) | Gets or sets the type of the object. |
| [getObjectCount()](#getObjectCount--) | Gets or sets the object count. |
| [setObjectCount(int value)](#setObjectCount-int-) | Gets or sets the object count. |
| [getRegionSize()](#getRegionSize--) | Gets or sets the size of the region. |
| [setRegionSize(short value)](#setRegionSize-short-) | Gets or sets the size of the region. |
| [getScanCount()](#getScanCount--) | Gets or sets the scan count. |
| [setScanCount(short value)](#setScanCount-short-) | Gets or sets the scan count. |
| [getMaxScan()](#getMaxScan--) | Gets or sets the maximum scan. |
| [setMaxScan(short value)](#setMaxScan-short-) | Gets or sets the maximum scan. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Gets or sets the bounding rectangle. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | Gets or sets the bounding rectangle. |
| [getAScans()](#getAScans--) | Gets or sets a scans. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | Gets or sets a scans. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


Gets or sets the next in chain.

Value: A value that MUST be ignored.

**Returns:**
short
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


Gets or sets the next in chain.

Value: A value that MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


Gets or sets the type of the object.

Value: The region identifier. It MUST be 0x0006.

**Returns:**
short
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


Gets or sets the type of the object.

Value: The region identifier. It MUST be 0x0006.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


Gets or sets the object count.

Value: A value that MUST be ignored.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


Gets or sets the object count.

Value: A value that MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


Gets or sets the size of the region.

Value: The size of the region in bytes plus the size of aScans in bytes.

**Returns:**
short
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


Gets or sets the size of the region.

Value: The size of the region in bytes plus the size of aScans in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


Gets or sets the scan count.

Value: The number of scanlines composing the region.

**Returns:**
short
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


Gets or sets the scan count.

Value: The number of scanlines composing the region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


Gets or sets the maximum scan.

Value: The maximum number of points in any one scan in this region.

**Returns:**
short
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


Gets or sets the maximum scan.

Value: The maximum number of points in any one scan in this region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Gets or sets the bounding rectangle.

Value: A Rect object (section 2.2.2.18) that defines the bounding rectangle.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


Gets or sets the bounding rectangle.

Value: A Rect object (section 2.2.2.18) that defines the bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


Gets or sets a scans.

Value: An array of Scan objects (section 2.2.2.21) that define the scanlines in the region.

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


Gets or sets a scans.

Value: An array of Scan objects (section 2.2.2.21) that define the scanlines in the region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

