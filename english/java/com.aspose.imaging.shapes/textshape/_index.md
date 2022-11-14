---
title: TextShape
second_title: Aspose.Imaging for Java API Reference
description: Represents a text shape.
type: docs
weight: 18
url: /java/com.aspose.imaging.shapes/textshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Represents a text shape.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextShape()](#TextShape--) | Initializes a new instance of the `TextShape` class. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-) | Initializes a new instance of the `TextShape` class. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets or sets the drawn text. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the drawn text. |
| [getFont()](#getFont--) | Gets or sets the font used to draw the text. |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | Gets or sets the font used to draw the text. |
| [getTextFormat()](#getTextFormat--) | Gets or sets the text format. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.imaging.StringFormat-) | Gets or sets the text format. |
| [getCenter()](#getCenter--) | Gets the shape's center. |
| [getBounds()](#getBounds--) | Gets the object's bounds. |
| [getSegments()](#getSegments--) | Gets the shape segments. |
| [hasSegments()](#hasSegments--) | Gets a value indicating whether shape has segments. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Gets the object's bounds. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applies the specified transformation to the shape. |
### TextShape() {#TextShape--}
```
public TextShape()
```


Initializes a new instance of the `TextShape` class.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Initializes a new instance of the `TextShape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to draw. |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | The text rectangle. |
| font | [Font](../../com.aspose.imaging/font) | The font to use. |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | The string format. |

### getText() {#getText--}
```
public String getText()
```


Gets or sets the drawn text.

Value: The drawn text.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Gets or sets the drawn text.

Value: The drawn text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Gets or sets the font used to draw the text.

Value: The font used to draw the text.

**Returns:**
[Font](../../com.aspose.imaging/font)
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public void setFont(Font value)
```


Gets or sets the font used to draw the text.

Value: The font used to draw the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) |  |

### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Gets or sets the text format.

Value: The text format.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat)
### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.imaging.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Gets or sets the text format.

Value: The text format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.imaging/stringformat) |  |

### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Gets the shape's center.

Value: The shape's center.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Gets the object's bounds.

Value: The object's bounds.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the shape segments.

Value: The shape segments.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Gets a value indicating whether shape has segments.

Value: `True` if shape has segments; otherwise, `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen to use for object. This can influence the object's bounds size. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applies the specified transformation to the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | The transformation to apply. |

