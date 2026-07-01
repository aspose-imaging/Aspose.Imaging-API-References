---
title: "EmfText"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmrText 对象包含用于文本输出的值。"
type: docs
weight: 35
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfText extends EmfObject
```

EmrText 对象包含用于文本输出的值。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfText()](#EmfText--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getReference()](#getReference--) | 获取或设置 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定用于定位字符串的参考点坐标。 |
| [setReference(Point value)](#setReference-com.aspose.imaging.Point-) | 获取或设置 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定用于定位字符串的参考点坐标。 |
| [getChars()](#getChars--) | 获取或设置一个 32 位无符号整数，指定字符串中的字符数。 |
| [setChars(int value)](#setChars-int-) | 获取或设置一个 32 位无符号整数，指定字符串中的字符数。 |
| [getOptions()](#getOptions--) | 获取或设置一个 32 位无符号整数，指定如何使用 Rectangle 字段中指定的矩形。 |
| [setOptions(int value)](#setOptions-int-) | 获取或设置一个 32 位无符号整数，指定如何使用 Rectangle 字段中指定的矩形。 |
| [getRectangle()](#getRectangle--) | 获取或设置可选的 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），在逻辑单位中定义裁剪和/或不透明矩形。 |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | 获取或设置可选的 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），在逻辑单位中定义裁剪和/或不透明矩形。 |
| [getStringBuffer()](#getStringBuffer--) | 获取或设置字符字符串缓冲区 UndefinedSpace1（可变）：可选的未使用字节数。 |
| [setStringBuffer(String value)](#setStringBuffer-java.lang.String-) | 获取或设置字符字符串缓冲区 UndefinedSpace1（可变）：可选的未使用字节数。 |
| [getGlyphIndexBuffer()](#getGlyphIndexBuffer--) | 获取可选的字形索引缓冲区。 |
| [setGlyphIndexBuffer(int[] value)](#setGlyphIndexBuffer-int---) | 设置可选的字形索引缓冲区。 |
| [getDxBuffer()](#getDxBuffer--) | 获取或设置可选的字符间距缓冲区 UndefinedSpace2（可变）：可选的未使用字节数。 |
| [setDxBuffer(int[] value)](#setDxBuffer-int---) | 获取或设置可选的字符间距缓冲区 UndefinedSpace2（可变）：可选的未使用字节数。 |
### EmfText() {#EmfText--}
```
public EmfText()
```


### getReference() {#getReference--}
```
public Point getReference()
```


获取或设置 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定用于定位字符串的参考点坐标。参考点由最后一个 EMR\_SETTEXTALIGN 记录（第 2.3.11.25 节）定义。如果未设置此类记录，默认对齐方式为 TA\_LEFT,TA\_TOP。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setReference(Point value) {#setReference-com.aspose.imaging.Point-}
```
public void setReference(Point value)
```


获取或设置 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定用于定位字符串的参考点坐标。参考点由最后一个 EMR\_SETTEXTALIGN 记录（第 2.3.11.25 节）定义。如果未设置此类记录，默认对齐方式为 TA\_LEFT,TA\_TOP。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getChars() {#getChars--}
```
public int getChars()
```


获取或设置一个 32 位无符号整数，指定字符串中的字符数。

**Returns:**
int
### setChars(int value) {#setChars-int-}
```
public void setChars(int value)
```


获取或设置一个 32 位无符号整数，指定字符串中的字符数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getOptions() {#getOptions--}
```
public int getOptions()
```


获取或设置一个 32 位无符号整数，指定如何使用 Rectangle 字段中指定的矩形。此字段可以是多个 ExtTextOutOptions 枚举（第 2.1.11 节）值的组合。

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


获取或设置一个 32 位无符号整数，指定如何使用 Rectangle 字段中指定的矩形。此字段可以是多个 ExtTextOutOptions 枚举（第 2.1.11 节）值的组合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取或设置一个可选的 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位定义裁剪和/或遮蔽矩形。此矩形应用于包含记录执行的文本输出。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


获取或设置一个可选的 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位定义裁剪和/或遮蔽矩形。此矩形应用于包含记录执行的文本输出。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStringBuffer() {#getStringBuffer--}
```
public String getStringBuffer()
```


获取或设置字符字符串缓冲区 UndefinedSpace1（变量）：可选的未使用字节数。OutputString 字段不需要紧跟在此结构的前一部分之后。OutputString（变量）：指定要输出的字符串的字符数组。该字段的位置由 offString 相对于此记录起始位置的字节值指定。字符数由 Chars 的值指定。

**Returns:**
java.lang.String
### setStringBuffer(String value) {#setStringBuffer-java.lang.String-}
```
public void setStringBuffer(String value)
```


获取或设置字符字符串缓冲区 UndefinedSpace1（变量）：可选的未使用字节数。OutputString 字段不需要紧跟在此结构的前一部分之后。OutputString（变量）：指定要输出的字符串的字符数组。该字段的位置由 offString 相对于此记录起始位置的字节值指定。字符数由 Chars 的值指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getGlyphIndexBuffer() {#getGlyphIndexBuffer--}
```
public int[] getGlyphIndexBuffer()
```


获取可选的字形索引缓冲区。如果 options 包含 ETO\_GLYPH\_INDEX 标志，则输出文本字符串中字符的代码实际上是 TrueType 字体中字符字形的索引（2.1.11 ExtTextOutOptions 枚举）。字形索引是特定于字体的，因此要在回放时显示正确的字符，所使用的字体必须与生成索引时使用的字体完全相同。

**Returns:**
int[] - 可选的字形索引缓冲区。
### setGlyphIndexBuffer(int[] value) {#setGlyphIndexBuffer-int---}
```
public void setGlyphIndexBuffer(int[] value)
```


设置可选的字形索引缓冲区。如果 options 包含 ETO\_GLYPH\_INDEX 标志，则输出文本字符串中字符的代码实际上是 TrueType 字体中字符字形的索引（2.1.11 ExtTextOutOptions 枚举）。字形索引是特定于字体的，因此要在回放时显示正确的字符，所使用的字体必须与生成索引时使用的字体完全相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 可选的字形索引缓冲区。 |

### getDxBuffer() {#getDxBuffer--}
```
public int[] getDxBuffer()
```


获取或设置可选的字符间距缓冲区 UndefinedSpace2（变量）：可选的未使用字节数。OutputDx 字段不需要紧跟在此结构的前一部分之后。OutputDx（变量）：一个 32 位无符号整数数组，指定逻辑单位中相邻字符单元原点之间的输出间距。该字段的位置由 offDx 相对于此记录起始位置的字节值指定。如果已定义间距，则此字段包含与输出字符串中字符数量相同的值。如果 EmrText 对象的 Options 字段包含 ETO\_PDY 标志，则此缓冲区包含的值是字符数的两倍，每个字符都有一个水平和一个垂直偏移，按此顺序。如果指定了 ETO\_RTLREADING，则字符从右向左排列，而不是从左向右。没有其他选项会影响此字段的解释。

**Returns:**
int[]
### setDxBuffer(int[] value) {#setDxBuffer-int---}
```
public void setDxBuffer(int[] value)
```


获取或设置可选的字符间距缓冲区 UndefinedSpace2（变量）：可选的未使用字节数。OutputDx 字段不需要紧跟在此结构的前一部分之后。OutputDx（变量）：一个 32 位无符号整数数组，指定逻辑单位中相邻字符单元原点之间的输出间距。该字段的位置由 offDx 相对于此记录起始位置的字节值指定。如果已定义间距，则此字段包含与输出字符串中字符数量相同的值。如果 EmrText 对象的 Options 字段包含 ETO\_PDY 标志，则此缓冲区包含的值是字符数的两倍，每个字符都有一个水平和一个垂直偏移，按此顺序。如果指定了 ETO\_RTLREADING，则字符从右向左排列，而不是从左向右。没有其他选项会影响此字段的解释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

