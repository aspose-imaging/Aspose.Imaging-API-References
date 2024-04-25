---
title: EmfLogPen
second_title: Aspose.Imaging for Java API Reference
description: The LogPen object defines the style width and color of a logical pen.
type: docs
weight: 27
url: /com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

The LogPen object defines the style, width, and color of a logical pen.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Gets or sets a 32-bit unsigned integer that specifies the PenStyle. |
| [setPenStyle(int value)](#setPenStyle-int-) | Gets or sets a 32-bit unsigned integer that specifies the PenStyle. |
| [getWidth()](#getWidth--) | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the width of the pen by the value of its x field. |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the width of the pen by the value of its x field. |
| [getAffectWidth()](#getAffectWidth--) | Gets or sets the width of the affect. |
| [setAffectWidth(int value)](#setAffectWidth-int-) | Gets or sets the width of the affect. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pen color value. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pen color value. |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Gets or sets a 32-bit unsigned integer that specifies the PenStyle. The value MUST be defined from the PenStyle enumeration table, specified in section 2.1.25.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the PenStyle. The value MUST be defined from the PenStyle enumeration table, specified in section 2.1.25.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the width of the pen by the value of its x field. The value of its y field MUST be ignored.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the width of the pen by the value of its x field. The value of its y field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


Gets or sets the width of the affect.

Value: The width of the affect.

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


Gets or sets the width of the affect.

Value: The width of the affect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pen color value.

Value: The 32-bit ARGB color

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pen color value.

Value: The 32-bit ARGB color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

