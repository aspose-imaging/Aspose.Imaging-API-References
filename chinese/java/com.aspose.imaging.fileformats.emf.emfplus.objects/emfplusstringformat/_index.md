---
title: "EmfPlusStringFormat"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusStringFormat 对象指定文本布局显示操作和语言标识。"
type: docs
weight: 74
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

EmfPlusStringFormat 对象指定文本布局、显示操作和语言标识。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | 获取或设置一个 EmfPlusLanguageIdentifier 对象，指定字符串中数字使用的语言。 |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | 获取或设置一个 EmfPlusLanguageIdentifier 对象，指定字符串中数字使用的语言。 |
| [getDigitSubstitution()](#getDigitSubstitution--) | 获取或设置一个 32 位无符号整数，指定如何根据区域设置或语言替换字符串中的数字。 |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | 获取或设置一个 32 位无符号整数，指定如何根据区域设置或语言替换字符串中的数字。 |
| [getFirstTabOffset()](#getFirstTabOffset--) | 获取或设置一个 32 位浮点值，指定文本行起始位置与第一个制表位之间的空格数。 |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | 获取或设置一个 32 位浮点值，指定文本行起始位置与第一个制表位之间的空格数。 |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | 获取或设置一个 32 位有符号整数，指定在遇到键盘快捷键前缀（即 & 符号）时对字符串执行的处理类型。 |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | 获取或设置一个 32 位有符号整数，指定在遇到键盘快捷键前缀（即 & 符号）时对字符串执行的处理类型。 |
| [getLanguage()](#getLanguage--) | 获取或设置一个 EmfPlusLanguageIdentifier 对象（第 2.2.2.23 节），指定字符串使用的语言。 |
| [setLanguage(short value)](#setLanguage-short-) | 获取或设置一个 EmfPlusLanguageIdentifier 对象（第 2.2.2.23 节），指定字符串使用的语言。 |
| [getLeadingMargin()](#getLeadingMargin--) | 获取或设置一个 32 位浮点值，指定要添加到字符串起始位置的空格长度。 |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | 获取或设置一个 32 位浮点值，指定要添加到字符串起始位置的空格长度。 |
| [getLineAlign()](#getLineAlign--) | 获取或设置一个 32 位无符号整数，指定字符串在布局矩形中的垂直对齐方式。 |
| [setLineAlign(int value)](#setLineAlign-int-) | 获取或设置一个 32 位无符号整数，指定字符串在布局矩形中的垂直对齐方式。 |
| [getRangeCount()](#getRangeCount--) | 获取或设置一个 32 位有符号整数，指定在 StringFormatData 字段中定义的 EmfPlusCharacterRange 对象的数量（第 2.2.2.8 节）。 |
| [setRangeCount(int value)](#setRangeCount-int-) | 获取或设置一个 32 位有符号整数，指定在 StringFormatData 字段中定义的 EmfPlusCharacterRange 对象的数量（第 2.2.2.8 节）。 |
| [getStringAlignment()](#getStringAlignment--) | 获取或设置一个 32 位无符号整数，指定字符串在布局矩形中的水平对齐方式。 |
| [setStringAlignment(int value)](#setStringAlignment-int-) | 获取或设置一个 32 位无符号整数，指定字符串在布局矩形中的水平对齐方式。 |
| [getStringFormatData()](#getStringFormatData--) | 获取或设置一个 EmfPlusStringFormatData 对象（第 2.2.2.44 节），指定可选的文本布局数据。 |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | 获取或设置一个 EmfPlusStringFormatData 对象（第 2.2.2.44 节），指定可选的文本布局数据。 |
| [getStringFormatFlags()](#getStringFormatFlags--) | 获取或设置一个 32 位无符号整数，指定用于格式化、裁剪和字体处理的文本布局选项。 |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | 获取或设置一个 32 位无符号整数，指定用于格式化、裁剪和字体处理的文本布局选项。 |
| [getTabstopCount()](#getTabstopCount--) | 获取或设置一个 32 位有符号整数，指定在 StringFormatData 字段中定义的制表位数量。 |
| [setTabstopCount(int value)](#setTabstopCount-int-) | 获取或设置一个 32 位有符号整数，指定在 StringFormatData 字段中定义的制表位数量。 |
| [getTracking()](#getTracking--) | 获取或设置一个 32 位浮点值，指定指定字符串中每个字符分配的水平空间与字体定义的字符宽度的比例。 |
| [setTracking(float value)](#setTracking-float-) | 获取或设置一个 32 位浮点值，指定指定字符串中每个字符分配的水平空间与字体定义的字符宽度的比例。 |
| [getTrailingMargin()](#getTrailingMargin--) | 获取或设置一个 32 位浮点值，指定字符串后应保留的空格长度。 |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | 获取或设置一个 32 位浮点值，指定字符串后应保留的空格长度。 |
| [getTrimming()](#getTrimming--) | 获取或设置，指定如何修剪过大而无法适应布局矩形的字符串中的字符。 |
| [setTrimming(int value)](#setTrimming-int-) | 获取或设置，指定如何修剪过大而无法适应布局矩形的字符串中的字符。 |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


获取或设置一个 EmfPlusLanguageIdentifier 对象，指定字符串中数字使用的语言。例如，如果该字符串包含阿拉伯数字，则此字段必须包含指定阿拉伯语言的语言标识符。

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


获取或设置一个 EmfPlusLanguageIdentifier 对象，指定字符串中数字使用的语言。例如，如果该字符串包含阿拉伯数字，则此字段必须包含指定阿拉伯语言的语言标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


获取或设置一个 32 位无符号整数，指定如何根据区域设置或语言替换字符串中的数字。该值必须在 StringDigitSubstitution 枚举中定义（第 2.1.1.30 节）。

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


获取或设置一个 32 位无符号整数，指定如何根据区域设置或语言替换字符串中的数字。该值必须在 StringDigitSubstitution 枚举中定义（第 2.1.1.30 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


获取或设置一个 32 位浮点值，指定文本行起始位置与第一个制表位之间的空格数。

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


获取或设置一个 32 位浮点值，指定文本行起始位置与第一个制表位之间的空格数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


获取或设置一个 32 位有符号整数，指定在遇到键盘快捷键前缀（即 & 符号）时对字符串执行的处理类型。基本上，此字段指定是否显示与文本相关的键盘快捷键前缀。该值必须在 HotkeyPrefix 枚举中定义（第 2.1.1.14 节）。

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


获取或设置一个 32 位有符号整数，指定在遇到键盘快捷键前缀（即 & 符号）时对字符串执行的处理类型。基本上，此字段指定是否显示与文本相关的键盘快捷键前缀。该值必须在 HotkeyPrefix 枚举中定义（第 2.1.1.14 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


获取或设置一个 EmfPlusLanguageIdentifier 对象（第 2.2.2.23 节），指定字符串使用的语言。

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


获取或设置一个 EmfPlusLanguageIdentifier 对象（第 2.2.2.23 节），指定字符串使用的语言。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


获取或设置一个 32 位浮点值，指定要添加到字符串起始位置的空格长度。默认值为 1/6 英寸；对于排版字体，默认值为 0。

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


获取或设置一个 32 位浮点值，指定要添加到字符串起始位置的空格长度。默认值为 1/6 英寸；对于排版字体，默认值为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


获取或设置一个 32 位无符号整数，指定字符串在布局矩形中的垂直对齐方式。该值必须在 StringAlignment 枚举中定义。

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


获取或设置一个 32 位无符号整数，指定字符串在布局矩形中的垂直对齐方式。该值必须在 StringAlignment 枚举中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


获取或设置一个 32 位有符号整数，指定在 StringFormatData 字段中定义的 EmfPlusCharacterRange 对象的数量（第 2.2.2.8 节）。

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


获取或设置一个 32 位有符号整数，指定在 StringFormatData 字段中定义的 EmfPlusCharacterRange 对象的数量（第 2.2.2.8 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


获取或设置一个 32 位无符号整数，指定如何在布局矩形中水平对齐字符串。此值必须在 StringAlignment 枚举中定义（第 2.1.1.29 节）。

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


获取或设置一个 32 位无符号整数，指定如何在布局矩形中水平对齐字符串。此值必须在 StringAlignment 枚举中定义（第 2.1.1.29 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


获取或设置一个 EmfPlusStringFormatData 对象（第 2.2.2.44 节），指定可选的文本布局数据。

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


获取或设置一个 EmfPlusStringFormatData 对象（第 2.2.2.44 节），指定可选的文本布局数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


获取或设置一个 32 位无符号整数，指定用于格式化、裁剪和字体处理的文本布局选项。此值必须由 StringFormat 标志组成（第 2.1.2.8 节）。

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


获取或设置一个 32 位无符号整数，指定用于格式化、裁剪和字体处理的文本布局选项。此值必须由 StringFormat 标志组成（第 2.1.2.8 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


获取或设置一个 32 位有符号整数，指定在 StringFormatData 字段中定义的制表位数量。

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


获取或设置一个 32 位有符号整数，指定在 StringFormatData 字段中定义的制表位数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


获取或设置一个 32 位浮点值，指定在指定字符串中分配给每个字符的水平空间与字符的字体定义宽度的比例。该属性的较大值表示字符之间有充足的间距；小于 1 的值可能导致字符重叠。默认值为 1.03；对于排版字体，默认值为 1.00。

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


获取或设置一个 32 位浮点值，指定在指定字符串中分配给每个字符的水平空间与字符的字体定义宽度的比例。该属性的较大值表示字符之间有充足的间距；小于 1 的值可能导致字符重叠。默认值为 1.03；对于排版字体，默认值为 1.00。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


获取或设置一个 32 位浮点值，指定字符串后保留的空格长度。默认值为 1/6 英寸；对于排版字体，默认值为 0。

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


获取或设置一个 32 位浮点值，指定字符串后保留的空格长度。默认值为 1/6 英寸；对于排版字体，默认值为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


获取或设置指定如何修剪过大而无法容纳在布局矩形中的字符串的字符。此值必须在 StringTrimming 枚举中定义（第 2.1.1.31 节）。

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


获取或设置指定如何修剪过大而无法容纳在布局矩形中的字符串的字符。此值必须在 StringTrimming 枚举中定义（第 2.1.1.31 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

