---
title: "TextShape"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示文本形状。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.shapes/textshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

表示文本形状。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextShape()](#TextShape--) | 初始化 `TextShape` 类的新实例。 |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-) | 初始化 `TextShape` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) | 获取或设置绘制的文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置绘制的文本。 |
| [getFont()](#getFont--) | 获取或设置用于绘制文本的字体。 |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | 获取或设置用于绘制文本的字体。 |
| [getTextFormat()](#getTextFormat--) | 获取或设置文本格式。 |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.imaging.StringFormat-) | 获取或设置文本格式。 |
| [getCenter()](#getCenter--) | 获取形状的中心。 |
| [getBounds()](#getBounds--) | 获取对象的边界。 |
| [getSegments()](#getSegments--) | 获取形状的段。 |
| [hasSegments()](#hasSegments--) | 获取指示形状是否具有段的值。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | 获取对象的边界。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | 获取对象的边界。 |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | 对形状应用指定的变换。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### TextShape() {#TextShape--}
```
public TextShape()
```


初始化 `TextShape` 类的新实例。

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


初始化 `TextShape` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要绘制的文本。 |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 文本矩形。 |
| font | [Font](../../com.aspose.imaging/font) | 要使用的字体。 |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | 字符串格式。 |

### getText() {#getText--}
```
public String getText()
```


获取或设置绘制的文本。

值：绘制的文本。

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


获取或设置绘制的文本。

值：绘制的文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


获取或设置用于绘制文本的字体。

值：用于绘制文本的字体。

**Returns:**
[Font](../../com.aspose.imaging/font)
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public void setFont(Font value)
```


获取或设置用于绘制文本的字体。

值：用于绘制文本的字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) |  |

### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


获取或设置文本格式。

值：文本格式。

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat)
### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.imaging.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


获取或设置文本格式。

值：文本格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.imaging/stringformat) |  |

### getCenter() {#getCenter--}
```
public PointF getCenter()
```


获取形状的中心。

值：形状的中心。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


获取对象的边界。

值：对象的边界。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


获取形状的段。

值：形状段。

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


获取指示形状是否具有段的值。

值：如果形状有段，则为 `True`；否则为 `false`。

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


获取对象的边界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 在计算边界之前要应用的矩阵。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


获取对象的边界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 在计算边界之前要应用的矩阵。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于对象的笔。它可能影响对象的边界尺寸。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


对形状应用指定的变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | 要应用的转换。 |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 其他对象。 |

**Returns:**
boolean - 相等比较结果。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int - 哈希码。
