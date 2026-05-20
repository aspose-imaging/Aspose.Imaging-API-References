---
title: "EmfSmallTextOut"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_SMALLTEXTOUT 记录输出一个字符串。"
type: docs
weight: 147
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

EMR\_SMALLTEXTOUT 记录输出字符串。

如果在 fuOptions 字段中设置了 ETO\_SMALL\_CHARS，则 TextString 包含字符的 8 位代码，这些代码来源于 16 位 Unicode UTF16-LE 字符代码的低字节，其中高字节假定为 0。如果在 fuOptions 字段中设置了 ETO\_NO\_RECT，则记录中不包含 Bounds 字段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSmallTextOut` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getX()](#getX--) | 获取或设置一个 32 位有符号整数，指定放置字符串的 x 坐标。 |
| [setX(int value)](#setX-int-) | 获取或设置一个 32 位有符号整数，指定放置字符串的 x 坐标。 |
| [getY()](#getY--) | 获取或设置一个 32 位有符号整数，指定放置字符串的 y 坐标。 |
| [setY(int value)](#setY-int-) | 获取或设置一个 32 位有符号整数，指定放置字符串的 y 坐标。 |
| [getCChars()](#getCChars--) | 获取或设置一个 32 位无符号整数，指定字符串中 16 位字符的数量。 |
| [setCChars(int value)](#setCChars-int-) | 获取或设置一个 32 位无符号整数，指定字符串中 16 位字符的数量。 |
| [getFuOptions()](#getFuOptions--) | 获取或设置一个 32 位无符号整数，指定要使用的文本输出选项。 |
| [setFuOptions(int value)](#setFuOptions-int-) | 获取或设置一个 32 位无符号整数，指定要使用的文本输出选项。 |
| [getIGraphicsMode()](#getIGraphicsMode--) | 获取或设置一个 32 位无符号整数，指定图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。 |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | 获取或设置一个 32 位无符号整数，指定图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。 |
| [getExScale()](#getExScale--) | 获取或设置一个 32 位浮点值，指定文本在 x 方向的缩放比例。 |
| [setExScale(float value)](#setExScale-float-) | 获取或设置一个 32 位浮点值，指定文本在 x 方向的缩放比例。 |
| [getEyScale()](#getEyScale--) | 获取或设置一个 32 位浮点值，指定文本在 y 方向的缩放比例。 |
| [setEyScale(float value)](#setEyScale-float-) | 获取或设置一个 32 位浮点值，指定文本在 y 方向的缩放比例。 |
| [getBounds()](#getBounds--) | 获取或设置一个可选的 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定设备单位中的边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置一个可选的 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定设备单位中的边界矩形。 |
| [getTextString()](#getTextString--) | 获取或设置一个可变长度字符串，包含要绘制的文本字符串，使用 8 位或 16 位字符代码，取决于 fuOptions 字段的值。 |
| [setTextString(String value)](#setTextString-java.lang.String-) | 获取或设置一个可变长度字符串，包含要绘制的文本字符串，使用 8 位或 16 位字符代码，取决于 fuOptions 字段的值。 |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


初始化 `EmfSmallTextOut` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getX() {#getX--}
```
public int getX()
```


获取或设置一个 32 位有符号整数，指定放置字符串的 x 坐标。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


获取或设置一个 32 位有符号整数，指定放置字符串的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public int getY()
```


获取或设置一个 32 位有符号整数，指定放置字符串的 y 坐标。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


获取或设置一个 32 位有符号整数，指定放置字符串的 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


获取或设置一个 32 位无符号整数，指定字符串中 16 位字符的数量。该字符串 NOT 以 null 结尾。

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


获取或设置一个 32 位无符号整数，指定字符串中 16 位字符的数量。该字符串 NOT 以 null 结尾。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


获取或设置一个 32 位无符号整数，指定要使用的文本输出选项。这些选项由 ExtTextOutOptions 枚举（第 2.1.11 节）中的一个或多个值组合指定。

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


获取或设置一个 32 位无符号整数，指定要使用的文本输出选项。这些选项由 ExtTextOutOptions 枚举（第 2.1.11 节）中的一个或多个值组合指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


获取或设置一个 32 位无符号整数，指定图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


获取或设置一个 32 位无符号整数，指定图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


获取或设置一个 32 位浮点值，指定文本在 x 方向的缩放比例。

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


获取或设置一个 32 位浮点值，指定文本在 x 方向的缩放比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


获取或设置一个 32 位浮点值，指定文本在 y 方向的缩放比例。

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


获取或设置一个 32 位浮点值，指定文本在 y 方向的缩放比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置一个可选的 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定设备单位中的边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置一个可选的 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定设备单位中的边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


获取或设置一个可变长度字符串，包含要绘制的文本字符串，使用 8 位或 16 位字符代码，取决于 fuOptions 字段的值。

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


获取或设置一个可变长度字符串，包含要绘制的文本字符串，使用 8 位或 16 位字符代码，取决于 fuOptions 字段的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

