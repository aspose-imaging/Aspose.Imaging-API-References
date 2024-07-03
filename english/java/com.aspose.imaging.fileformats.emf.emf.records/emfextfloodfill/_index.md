---
title: EmfExtFloodFill
second_title: Aspose.Imaging for Java API Reference
description: The EMR_EXTFLOODFILL record fills an area of the display surface with the current brush
type: docs
weight: 54
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

The EMR\_EXTFLOODFILL record fills an area of the display surface with the current brush
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfExtFloodFill` class. |
## Methods

| Method | Description |
| --- | --- |
| [getStart()](#getStart--) | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15), which specifies the coordinates, in logical units, where filling begins. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15), which specifies the coordinates, in logical units, where filling begins. |
| [getArgb32Color()](#getArgb32Color--) | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8), which is used with the FloodFillMode to determine the area to fill. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8), which is used with the FloodFillMode to determine the area to fill. |
| [getFloodFillMode()](#getFloodFillMode--) | Gets or sets a 32-bit unsigned integer that specifies how to use the Color value to determine the area for the flood fill operation. |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | Gets or sets a 32-bit unsigned integer that specifies how to use the Color value to determine the area for the flood fill operation. |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


Initializes a new instance of the `EmfExtFloodFill` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getStart() {#getStart--}
```
public Point getStart()
```


Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15), which specifies the coordinates, in logical units, where filling begins.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15), which specifies the coordinates, in logical units, where filling begins.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8), which is used with the FloodFillMode to determine the area to fill.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8), which is used with the FloodFillMode to determine the area to fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


Gets or sets a 32-bit unsigned integer that specifies how to use the Color value to determine the area for the flood fill operation. The value MUST be in the FloodFill enumeration (section 2.1.13).

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to use the Color value to determine the area for the flood fill operation. The value MUST be in the FloodFill enumeration (section 2.1.13).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

