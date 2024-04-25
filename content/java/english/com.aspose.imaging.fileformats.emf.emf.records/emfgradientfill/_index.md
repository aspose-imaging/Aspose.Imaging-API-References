---
title: EmfGradientFill
second_title: Aspose.Imaging for Java API Reference
description: The EMR_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color.
type: docs
weight: 64
url: /com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

The EMR\_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color.

An EMR\_GRADIENTFILL record that specifies that the three vertexes of a triangle SHOULD fill the figure with smooth gradients of colors.[85] An EMR\_GRADIENTFILL record that specifies that the upper-left and lower-right vertexes of a rectangle SHOULD fill the figure with smooth gradients of color. There are two gradient fill modes in the GradientFill enumeration that can be used when drawing a rectangle. In GRADIENT\_FILL\_RECT\_H mode, the rectangle is filled from left to right. In GRADIENT\_FILL\_RECT\_V mode, the rectangle is filled from top to bottom. Note An EMR\_GRADIENTFILL record MUST ignore the Alpha fields in the TriVertex objects. An EMR\_ALPHABLEND record (section 2.3.1.1) that immediately follows the EMR\_GRADIENTFILL record can be used to apply an alpha transparency gradient to the filled area.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfGradientFill` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies a bounding rectangle, in inclusive-inclusive device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies a bounding rectangle, in inclusive-inclusive device units. |
| [getNVer()](#getNVer--) | Gets or sets a 32-bit unsigned integer that specifies the number of vertexes. |
| [setNVer(int value)](#setNVer-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of vertexes. |
| [getNTri()](#getNTri--) | Gets or sets a 32-bit unsigned integer that specifies the number of rectangles or triangles to fill. |
| [setNTri(int value)](#setNTri-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of rectangles or triangles to fill. |
| [getUlMode()](#getUlMode--) | Gets or sets a 32-bit unsigned integer that specifies the gradient fill mode. |
| [setUlMode(int value)](#setUlMode-int-) | Gets or sets a 32-bit unsigned integer that specifies the gradient fill mode. |
| [getVertexData()](#getVertexData--) | Gets or sets objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them. |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | Gets or sets objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them. |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


Initializes a new instance of the `EmfGradientFill` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies a bounding rectangle, in inclusive-inclusive device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies a bounding rectangle, in inclusive-inclusive device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


Gets or sets a 32-bit unsigned integer that specifies the number of vertexes.

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of vertexes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


Gets or sets a 32-bit unsigned integer that specifies the number of rectangles or triangles to fill.

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of rectangles or triangles to fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


Gets or sets a 32-bit unsigned integer that specifies the gradient fill mode. The value MUST be in the GradientFill enumeration (section 2.1.15).

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the gradient fill mode. The value MUST be in the GradientFill enumeration (section 2.1.15).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


Gets or sets objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them.

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


Gets or sets objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

