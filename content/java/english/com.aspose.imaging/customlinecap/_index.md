---
title: CustomLineCap
second_title: Aspose.Imaging for Java API Reference
description: Encapsulates a custom user-defined line cap.
type: docs
weight: 35
url: /com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Encapsulates a custom user-defined line cap.
## Constructors

| Constructor | Description |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | Initializes a new instance of the `CustomLineCap` class with the specified outline and fill. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | Initializes a new instance of the `CustomLineCap` class from the specified existing `LineCap` enumeration with the specified outline and fill. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | Initializes a new instance of the `CustomLineCap` class from the specified existing `LineCap` enumeration with the specified outline, fill, and inset. |
## Methods

| Method | Description |
| --- | --- |
| [getFillPath()](#getFillPath--) | Gets the object that defines the fill for the custom cap. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | Sets the object that defines the fill for the custom cap. |
| [getStrokePath()](#getStrokePath--) | Gets the object that defines the outline of the custom cap. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | Sets the object that defines the outline of the custom cap. |
| [getStrokeJoin()](#getStrokeJoin--) | Gets the `LineJoin` enumeration that determines how lines that compose this `CustomLineCap` object are joined. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Sets the `LineJoin` enumeration that determines how lines that compose this `CustomLineCap` object are joined. |
| [getBaseCap()](#getBaseCap--) | Gets the `LineCap` enumeration on which this `CustomLineCap` is based. |
| [setBaseCap(int value)](#setBaseCap-int-) | Sets the `LineCap` enumeration on which this `CustomLineCap` is based. |
| [getBaseInset()](#getBaseInset--) | Gets the distance between the cap and the line. |
| [setBaseInset(float value)](#setBaseInset-float-) | Sets the distance between the cap and the line. |
| [getWidthScale()](#getWidthScale--) | Gets the amount by which to scale this `CustomLineCap` Class object with respect to the width of the `System.Drawing.Pen` object. |
| [setWidthScale(float value)](#setWidthScale-float-) | Sets the amount by which to scale this `CustomLineCap` Class object with respect to the width of the `System.Drawing.Pen` object. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Sets the caps used to start and end lines that make up this custom cap. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Gets the caps used to start and end lines that make up this custom cap. |
| [equals(Object o)](#equals-java.lang.Object-) | Check if objects are equal. |
| [hashCode()](#hashCode--) | Get hash code of the current object. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initializes a new instance of the `CustomLineCap` class with the specified outline and fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | A `GraphicsPath` object that defines the fill for the custom cap. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | A `GraphicsPath` object that defines the outline of the custom cap. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initializes a new instance of the `CustomLineCap` class from the specified existing `LineCap` enumeration with the specified outline and fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | A `GraphicsPath` object that defines the fill for the custom cap. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | A `GraphicsPath` object that defines the outline of the custom cap. |
| baseCap | int | The line cap from which to create the custom cap. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initializes a new instance of the `CustomLineCap` class from the specified existing `LineCap` enumeration with the specified outline, fill, and inset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | A `GraphicsPath` object that defines the fill for the custom cap. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | A `GraphicsPath` object that defines the outline of the custom cap. |
| baseCap | int | The line cap from which to create the custom cap. |
| baseInset | float | The distance between the cap and the line. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Gets the object that defines the fill for the custom cap.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Sets the object that defines the fill for the custom cap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The object that defines the fill for the custom cap. |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Gets the object that defines the outline of the custom cap.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Sets the object that defines the outline of the custom cap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The object that defines the outline of the custom cap. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Gets the `LineJoin` enumeration that determines how lines that compose this `CustomLineCap` object are joined.

**Returns:**
int - The `LineJoin` enumeration this `CustomLineCap` object uses to join lines.
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Sets the `LineJoin` enumeration that determines how lines that compose this `CustomLineCap` object are joined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The `LineJoin` enumeration this `CustomLineCap` object uses to join lines. |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Gets the `LineCap` enumeration on which this `CustomLineCap` is based.

**Returns:**
int - The `LineCap` enumeration on which this `CustomLineCap` is based.
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Sets the `LineCap` enumeration on which this `CustomLineCap` is based.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The `LineCap` enumeration on which this `CustomLineCap` is based. |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Gets the distance between the cap and the line.

**Returns:**
float - The distance between the beginning of the cap and the end of the line.
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Sets the distance between the cap and the line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The distance between the beginning of the cap and the end of the line. |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Gets the amount by which to scale this `CustomLineCap` Class object with respect to the width of the `System.Drawing.Pen` object.

**Returns:**
float - The amount by which to scale the cap.
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Sets the amount by which to scale this `CustomLineCap` Class object with respect to the width of the `System.Drawing.Pen` object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The amount by which to scale the cap. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Sets the caps used to start and end lines that make up this custom cap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startCap | int | The `LineCap` enumeration used at the beginning of a line within this cap. |
| endCap | int | The `LineCap` enumeration used at the end of a line within this cap. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Gets the caps used to start and end lines that make up this custom cap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startCap | int[] | The `LineCap` enumeration used at the beginning of a line within this cap. |
| endCap | int[] | The `LineCap` enumeration used at the end of a line within this cap. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Check if objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The other object. |

**Returns:**
boolean - The equality comparison result.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Get hash code of the current object.

**Returns:**
int - The hash code.
