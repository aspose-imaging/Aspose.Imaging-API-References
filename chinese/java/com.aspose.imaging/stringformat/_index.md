---
title: "StringFormat"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "封装文本布局信息，例如对齐、方向和制表位，以及显示操作，如插入省略号、数字本地化替换和 OpenType 功能。"
type: docs
weight: 112
url: /zh/java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

封装文本布局信息（例如对齐、方向和制表位）、显示操作（例如插入省略号和数字本地化替换）以及 OpenType 功能。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StringFormat()](#StringFormat--) | 初始化一个新的 `com.aspose.imaging.StringFormat` 对象。 |
| [StringFormat(int options)](#StringFormat-int-) | 使用指定的 `com.aspose.imaging.StringFormatFlags` 枚举和语言初始化一个新的 `com.aspose.imaging.StringFormat` 对象。 |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | 从指定的现有 `com.aspose.imaging.StringFormat` 对象初始化一个新的 `com.aspose.imaging.StringFormat` 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | 获取通用默认的 `com.aspose.imaging.StringFormat` 对象。 |
| [getGenericTypographic()](#getGenericTypographic--) | 获取一个通用排版 `com.aspose.imaging.StringFormat` 对象。 |
| [getFormatFlags()](#getFormatFlags--) | 获取一个包含格式信息的 `com.aspose.imaging.StringFormatFlags` 枚举。 |
| [setFormatFlags(int value)](#setFormatFlags-int-) | 设置一个包含格式信息的 `com.aspose.imaging.StringFormatFlags` 枚举。 |
| [getAlignment()](#getAlignment--) | 获取垂直方向的文本对齐信息。 |
| [setAlignment(int value)](#setAlignment-int-) | 设置垂直方向的文本对齐信息。 |
| [getLineAlignment()](#getLineAlignment--) | 获取水平方向的行对齐方式。 |
| [setLineAlignment(int value)](#setLineAlignment-int-) | 设置水平方向的行对齐方式。 |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | 获取此 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.HotkeyPrefix` 对象。 |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | 设置此 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.HotkeyPrefix` 对象。 |
| [getTrimming()](#getTrimming--) | 获取此 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.StringTrimming` 枚举。 |
| [setTrimming(int value)](#setTrimming-int-) | 设置此 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.StringTrimming` 枚举。 |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | 获取用于数字替换的方法。 |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | 设置用于数字替换的方法。 |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | 获取在本地数字替换为西方数字时使用的语言。 |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | 设置在本地数字替换为西方数字时使用的语言。 |
| [getFirstTabOffset()](#getFirstTabOffset--) | 获取文本行起始与第一个制表位之间的空格数。 |
| [getTabStops()](#getTabStops--) | 获取一个数组，表示制表位之间的距离，单位由 `P:Aspose.Imaging.getGraphics().PageUnit` 属性指定。 |
| [getCustomCharIdent()](#getCustomCharIdent--) | 获取自定义字符标识。 |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | 设置自定义字符标识。 |
| [deepClone()](#deepClone--) | 创建此 `com.aspose.imaging.StringFormat` 对象的深度克隆。 |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | 为此 `com.aspose.imaging.StringFormat` 对象设置制表位。 |
| [toString()](#toString--) | 将此 `com.aspose.imaging.StringFormat` 对象转换为可读的字符串。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


初始化一个新的 `com.aspose.imaging.StringFormat` 对象。

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


使用指定的 `com.aspose.imaging.StringFormatFlags` 枚举和语言初始化一个新的 `com.aspose.imaging.StringFormat` 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 选项 | int | 新 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.StringFormatFlags` 枚举。 |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


从指定的现有 `com.aspose.imaging.StringFormat` 对象初始化一个新的 `com.aspose.imaging.StringFormat` 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | 用于初始化新 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.StringFormat` 对象。 |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


获取通用默认的 `com.aspose.imaging.StringFormat` 对象。

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


获取一个通用排版 `com.aspose.imaging.StringFormat` 对象。

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


获取一个包含格式信息的 `com.aspose.imaging.StringFormatFlags` 枚举。

**Returns:**
int - 一个 `com.aspose.imaging.StringFormatFlags` 枚举，包含格式信息。
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


设置一个包含格式信息的 `com.aspose.imaging.StringFormatFlags` 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 一个 `com.aspose.imaging.StringFormatFlags` 枚举，包含格式信息。 |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


获取垂直方向的文本对齐信息。

**Returns:**
int - 一个 `com.aspose.imaging.StringAlignment` 枚举，指定文本对齐信息。
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


设置垂直方向的文本对齐信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 一个 `com.aspose.imaging.StringAlignment` 枚举，指定文本对齐信息。 |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


获取水平方向的行对齐方式。

**Returns:**
int - 一个 `com.aspose.imaging.StringAlignment` 枚举，表示行对齐方式。
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


设置水平方向的行对齐方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 一个 `com.aspose.imaging.StringAlignment` 枚举，表示行对齐方式。 |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


获取此 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.HotkeyPrefix` 对象。

**Returns:**
int - 此 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.HotkeyPrefix` 对象，默认值为 `F:Aspose.Imaging.HotkeyPrefix.None`。
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


设置此 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.HotkeyPrefix` 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.HotkeyPrefix` 对象，默认值为 `F:Aspose.Imaging.HotkeyPrefix.None`。 |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


获取此 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.StringTrimming` 枚举。

**Returns:**
int - 一个 `com.aspose.imaging.StringTrimming` 枚举，指示使用此 `com.aspose.imaging.StringFormat` 对象绘制的文本在超出布局矩形边界时如何修剪。
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


设置此 `com.aspose.imaging.StringFormat` 对象的 `com.aspose.imaging.StringTrimming` 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 一个 `com.aspose.imaging.StringTrimming` 枚举，指示使用此 `com.aspose.imaging.StringFormat` 对象绘制的文本在超出布局矩形边界时如何修剪。 |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


获取用于数字替换的方法。

**Returns:**
int - 一个 `com.aspose.imaging.StringDigitSubstitute` 枚举值，指定如何替换因当前字体不支持而无法显示的字符串字符。

为已废弃的方法 SetDigitSubstitution 引入了 setter。
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


设置用于数字替换的方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 一个 `com.aspose.imaging.StringDigitSubstitute` 枚举值，指定如何替换因当前字体不支持而无法显示的字符串字符。 |

为已废弃的方法 SetDigitSubstitution 引入了 setter。 |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


获取在本地数字替换为西方数字时使用的语言。

**Returns:**
int - 一个国家语言支持 (NLS) 语言标识符，用于标识在本地数字替换为西方数字时将使用的语言。您可以将 `System.Globalization.CultureInfo` 对象的 `P:System.Globalization.CultureInfo.LCID` 属性作为 NLS 语言标识符传递。例如，假设您创建并设置了区域设置 "ar-EG"。如果将 `com.aspose.imaging.StringDigitSubstitute.Traditional` 传递给 `com.aspose.imaging.StringFormat.setDigitSubstitution(int)` 方法，则在显示时会将阿拉伯-印度数字替换为西方数字。
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


设置在本地数字替换为西方数字时使用的语言。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 一个国家语言支持 (NLS) 语言标识符，用于标识在本地数字替换为西方数字时将使用的语言。您可以将 `System.Globalization.CultureInfo` 对象的 `P:System.Globalization.CultureInfo.LCID` 属性作为 NLS 语言标识符传递。例如，假设您创建并设置了区域设置 "ar-EG"。如果将 `com.aspose.imaging.StringDigitSubstitute.Traditional` 传递给 `com.aspose.imaging.StringFormat.setDigitSubstitution(int)` 方法，则在显示时会将阿拉伯-印度数字替换为西方数字。 |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


获取文本行起始与第一个制表位之间的空格数。

**Returns:**
float - 第一个制表位偏移量。

为已移除的方法 GetTabStops 引入了该属性。
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


获取一个数组，表示制表位之间的距离，单位由 `P:Aspose.Imaging.getGraphics().PageUnit` 属性指定。

**Returns:**
float[] - 制表位。

为已移除的方法 GetTabStops 引入了该属性。
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


获取自定义字符标识。

值：自定义字符标识。

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


设置自定义字符标识。

值：自定义字符标识。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | 自定义字符标识。 |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


创建此 `com.aspose.imaging.StringFormat` 对象的深度克隆。

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


为此 `com.aspose.imaging.StringFormat` 对象设置制表位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstTabOffset | float | 文本行起始与第一个制表位之间的空格数。 |
| tabStops | float[] | 一个数组，表示制表位之间的距离，单位由 `com.aspose.imaging.Graphics.PageUnit` 属性指定。 |

### toString() {#toString--}
```
public String toString()
```


将此 `com.aspose.imaging.StringFormat` 对象转换为可读的字符串。

**Returns:**
java.lang.String - 此 `com.aspose.imaging.StringFormat` 对象的字符串表示形式。
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
