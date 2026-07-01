---
title: "EmfPlusDrawDriverString"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusDrawDriverString 记录指定带字符位置的文本输出。"
type: docs
weight: 20
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

EmfPlusDrawDriverString 记录指定带字符位置的文本输出。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawDriverString` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getObjectId()](#getObjectId--) | 获取对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 设置对象标识符。 |
| [getBrushId()](#getBrushId--) | 获取画笔标识符 一个 32 位无符号整数，指定文本的前景颜色或图形画笔，取决于 Flags 中的 S 标志的值。 |
| [setBrushId(int value)](#setBrushId-int-) | 设置画笔标识符 一个 32 位无符号整数，指定文本的前景颜色或图形画笔，取决于 Flags 中的 S 标志的值。 |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | 获取驱动字符串选项标志 一个 32 位无符号整数，指定字符串的间距、方向和渲染质量。 |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | 设置驱动字符串选项标志 一个 32 位无符号整数，指定字符串的间距、方向和渲染质量。 |
| [getGlyphCount()](#getGlyphCount--) | 获取字形计数 一个 32 位无符号整数，指定字符串中的字形数量。 |
| [setGlyphCount(int value)](#setGlyphCount-int-) | 设置字形计数 一个 32 位无符号整数，指定字符串中的字形数量。 |
| [getGlyphPos()](#getGlyphPos--) | 获取字形位置数组 一个 EmfPlusPointF 对象数组（第 2.2.2.36 节），指定每个字符字形的输出位置。 |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | 设置字形位置数组 一个 EmpPlusPointF 对象数组（第 2.2.2.36 节），指定每个字符字形的输出位置。 |
| [getGlyphs()](#getGlyphs--) | 获取字形数组 一个 16 位值的数组，定义要绘制的文本字符串。 |
| [setGlyphs(short[] value)](#setGlyphs-short---) | 设置字形数组 一个 16 位值的数组，定义要绘制的文本字符串。 |
| [isColor()](#isColor--) | 获取或设置一个值，指示此实例是否为颜色。 |
| [setColor(boolean value)](#setColor-boolean-) | 设置一个值，指示此实例是否为彩色。 |
| [getMatrixPresent()](#getMatrixPresent--) | 获取矩阵存在标志 一个 32 位无符号整数，指定 TransformMatrix 字段中是否存在变换矩阵，0 - 未存在矩阵。 |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | 设置矩阵存在标志 一个 32 位无符号整数，指定 TransformMatrix 字段中是否存在变换矩阵，0 - 未存在矩阵。 |
| [getTransformMatrix()](#getTransformMatrix--) | 获取变换矩阵 一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定要应用于文本数组中每个值的变换。 |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | 设置变换矩阵 一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定要应用于文本数组中每个值的变换。 |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


初始化 `EmfPlusDrawDriverString` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取对象标识符。用于渲染文本的 EMF+ 对象表中 `` 对象的索引（第 2.2.1.3 节）。该值必须在 0 到 63（含）之间。

**Returns:**
byte - 对象标识符。
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


设置对象标识符。用于渲染文本的 EMF+ 对象表中 `` 对象的索引（第 2.2.1.3 节）。该值必须在 0 到 63（含）之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte | 对象标识符。 |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


获取画笔标识符 一个 32 位无符号整数，指定文本的前景颜色或图形画笔，取决于 Flags 中的 S 标志的值。

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


设置画笔标识符 一个 32 位无符号整数，指定文本的前景颜色或图形画笔，取决于 Flags 中的 S 标志的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


获取驱动字符串选项标志 一个 32 位无符号整数，指定字符串的间距、方向和渲染质量。

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


设置驱动字符串选项标志 一个 32 位无符号整数，指定字符串的间距、方向和渲染质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


获取字形计数 一个 32 位无符号整数，指定字符串中的字形数量。

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


设置字形计数 一个 32 位无符号整数，指定字符串中的字形数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


获取字形位置数组 一个 EmfPlusPointF 对象数组（第 2.2.2.36 节），用于指定每个字符字形的输出位置。 必须有 GlyphCount 个元素，这些元素与 Glyphs 数组中的元素一一对应。 如果在 DriverStringOptions 标志中设置了 DriverStringOptionsRealizedAdvance 标志，则字形位置从第一个字形的位置计算。 在这种情况下，GlyphPos 仅指定第一个字形的位置。

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


设置字形位置数组 一个 EmfPlusPointF 对象数组（第 2.2.2.36 节），用于指定每个字符字形的输出位置。 必须有 GlyphCount 个元素，这些元素与 Glyphs 数组中的元素一一对应。 如果在 DriverStringOptions 标志中设置了 DriverStringOptionsRealizedAdvance 标志，则字形位置从第一个字形的位置计算。 在这种情况下，GlyphPos 仅指定第一个字形的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


获取字形数组 一个 16 位值数组，用于定义要绘制的文本字符串。如果在 DriverStringOptionsFlags 字段中设置了 DriverStringOptionsCmapLookup 标志，则此数组中的每个值指定一个 Unicode 字符。否则，每个值指定一个指向由 Flags 字段中的 ObjectId 值指定的 EmfPlusFont 对象中的字符字形的索引。

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


设置字形数组 一个 16 位值数组，用于定义要绘制的文本字符串。如果在 DriverStringOptionsFlags 字段中设置了 DriverStringOptionsCmapLookup 标志，则此数组中的每个值指定一个 Unicode 字符。否则，每个值指定一个指向由 Flags 字段中的 ObjectId 值指定的 EmfPlusFont 对象中的字符字形的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


获取或设置一个值，指示此实例是否为颜色。此位指示 BrushId 字段中数据的类型。如果设置，则 BrushId 指定 EmfPlusARGB 对象（第 2.2.2.1 节）中的颜色值。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。

**Returns:**
布尔值 - 如果此实例是颜色，则为 `true`；否则为 `false`。
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


设置一个值，指示此实例是否为颜色。此位指示 BrushId 字段中数据的类型。如果设置，则 BrushId 指定 EmfPlusARGB 对象（第 2.2.2.1 节）中的颜色值。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `true` 如果此实例是颜色；否则为 `false`。 |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


获取矩阵存在标志 一个 32 位无符号整数，指定 TransformMatrix 字段中是否存在变换矩阵。0 - 未存在矩阵。1 - 变换矩阵位于 TransformMatrix 字段中。

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


设置矩阵存在标志 一个 32 位无符号整数，指定 TransformMatrix 字段中是否存在变换矩阵。0 - 未存在矩阵。1 - 变换矩阵位于 TransformMatrix 字段中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


获取变换矩阵 一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定对文本数组中每个值应用的变换。此数据的存在性由 MatrixPresent 字段决定。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


设置变换矩阵 一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定对文本数组中每个值应用的变换。此数据的存在性由 MatrixPresent 字段决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

