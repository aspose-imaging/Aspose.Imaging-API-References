---
title: CmxEllipseSpec
second_title: Aspose.Imaging for Java API Reference
description: Represents geometric info specified for an ellipse.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxEllipseSpec implements ICmxObjectSpec
```

Represents geometric info specified for an ellipse.
## Constructors

| Constructor | Description |
| --- | --- |
| [CmxEllipseSpec()](#CmxEllipseSpec--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAngle1()](#getAngle1--) | Gets the first angle used for defining of pie sector. |
| [setAngle1(float value)](#setAngle1-float-) | Sets the first angle used for defining of pie sector. |
| [getAngle2()](#getAngle2--) | Gets the second angle used for defining of pie sector. |
| [setAngle2(float value)](#setAngle2-float-) | Sets the second angle used for defining of pie sector. |
| [getRotation()](#getRotation--) | Gets the angle of rotation of the ellipse. |
| [setRotation(float value)](#setRotation-float-) | Sets the angle of rotation of the ellipse. |
| [getPie()](#getPie--) | Gets a value indicating whether this [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) is a pie. |
| [setPie(boolean value)](#setPie-boolean-) | Sets a value indicating whether this [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) is a pie. |
| [getCenterX()](#getCenterX--) | Gets the X coordinate for the center of the rectangle. |
| [setCenterX(float value)](#setCenterX-float-) | Sets the X coordinate for the center of the rectangle. |
| [getCenterY()](#getCenterY--) | Gets the Y coordinate for the center of the rectangle. |
| [setCenterY(float value)](#setCenterY-float-) | Sets the Y coordinate for the center of the rectangle. |
| [getDiameterX()](#getDiameterX--) | Gets the diameter for X dimension of the rectangle. |
| [setDiameterX(float value)](#setDiameterX-float-) | Sets the diameter for X dimension of the rectangle. |
| [getDiameterY()](#getDiameterY--) | Gets the diameter for Y dimension of the rectangle. |
| [setDiameterY(float value)](#setDiameterY-float-) | Sets the diameter for Y dimension of the rectangle. |
| [getBoundingBox()](#getBoundingBox--) | Gets the bounding box. |
| [setBoundingBox(RectangleF value)](#setBoundingBox-com.aspose.imaging.RectangleF-) | Sets the bounding box. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [equals(Object o)](#equals-java.lang.Object-) | Check if objects are equal. |
| [hashCode()](#hashCode--) | Get hash code of the current object. |
### CmxEllipseSpec() {#CmxEllipseSpec--}
```
public CmxEllipseSpec()
```


### getAngle1() {#getAngle1--}
```
public final float getAngle1()
```


Gets the first angle used for defining of pie sector. Does no affect if `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) is `false`. Measures in radians.

**Returns:**
float - the first angle used for defining of pie sector.
### setAngle1(float value) {#setAngle1-float-}
```
public final void setAngle1(float value)
```


Sets the first angle used for defining of pie sector. Does no affect if `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) is `false`. Measures in radians.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the first angle used for defining of pie sector. |

### getAngle2() {#getAngle2--}
```
public final float getAngle2()
```


Gets the second angle used for defining of pie sector. Does no affect if `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) is `false`. Measures in radians.

**Returns:**
float - the second angle used for defining of pie sector.
### setAngle2(float value) {#setAngle2-float-}
```
public final void setAngle2(float value)
```


Sets the second angle used for defining of pie sector. Does no affect if `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) is `false`. Measures in radians.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the second angle used for defining of pie sector. |

### getRotation() {#getRotation--}
```
public final float getRotation()
```


Gets the angle of rotation of the ellipse. Measures in radians.

**Returns:**
float - the angle of rotation of the ellipse.
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


Sets the angle of rotation of the ellipse. Measures in radians.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the angle of rotation of the ellipse. |

### getPie() {#getPie--}
```
public final boolean getPie()
```


Gets a value indicating whether this [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) is a pie.

**Returns:**
boolean - a value indicating whether this [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) is a pie.
### setPie(boolean value) {#setPie-boolean-}
```
public final void setPie(boolean value)
```


Sets a value indicating whether this [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) is a pie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether this [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) is a pie. |

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Gets the X coordinate for the center of the rectangle. Measures in common document distance units.

**Returns:**
float - the X coordinate for the center of the rectangle.
### setCenterX(float value) {#setCenterX-float-}
```
public final void setCenterX(float value)
```


Sets the X coordinate for the center of the rectangle. Measures in common document distance units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the X coordinate for the center of the rectangle. |

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Gets the Y coordinate for the center of the rectangle. Measures in common document distance units.

**Returns:**
float - the Y coordinate for the center of the rectangle.
### setCenterY(float value) {#setCenterY-float-}
```
public final void setCenterY(float value)
```


Sets the Y coordinate for the center of the rectangle. Measures in common document distance units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the Y coordinate for the center of the rectangle. |

### getDiameterX() {#getDiameterX--}
```
public final float getDiameterX()
```


Gets the diameter for X dimension of the rectangle. Measures in common document distance units.

**Returns:**
float - the diameter for X dimension of the rectangle.
### setDiameterX(float value) {#setDiameterX-float-}
```
public final void setDiameterX(float value)
```


Sets the diameter for X dimension of the rectangle. Measures in common document distance units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the diameter for X dimension of the rectangle. |

### getDiameterY() {#getDiameterY--}
```
public final float getDiameterY()
```


Gets the diameter for Y dimension of the rectangle. Measures in common document distance units.

**Returns:**
float - the diameter for Y dimension of the rectangle.
### setDiameterY(float value) {#setDiameterY-float-}
```
public final void setDiameterY(float value)
```


Sets the diameter for Y dimension of the rectangle. Measures in common document distance units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the diameter for Y dimension of the rectangle. |

### getBoundingBox() {#getBoundingBox--}
```
public final RectangleF getBoundingBox()
```


Gets the bounding box.

Value: The bounding box.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding box.
### setBoundingBox(RectangleF value) {#setBoundingBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundingBox(RectangleF value)
```


Sets the bounding box.

Value: The bounding box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | the bounding box. |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
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
