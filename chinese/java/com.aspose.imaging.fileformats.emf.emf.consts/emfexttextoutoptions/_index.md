---
title: "EmfExtTextOutOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "ExtTextOutOptions 枚举指定控制 EMR_SMALLTEXTOUT 第 2.3.5.37 节记录以及 EmrText 对象中文本输出各方面的参数。"
type: docs
weight: 19
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfExtTextOutOptions extends System.Enum
```

ExtTextOutOptions 枚举指定控制 EMR\\_SMALLTEXTOUT（第 2.3.5.37 节）记录以及 EmrText 对象中文本输出各方面的参数。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ETO_OPAQUE](#ETO-OPAQUE) | 此位指示应使用当前背景色填充矩形 |
| [ETO_CLIPPED](#ETO-CLIPPED) | 此位指示应将文本裁剪到矩形内。 |
| [ETO_GLYPH_INDEX](#ETO-GLYPH-INDEX) | 此位指示输出文本字符串中字符的代码实际上是 TrueType 字体中字符字形的索引。 |
| [ETO_RTLREADING](#ETO-RTLREADING) | 此位指示文本必须按从右到左的阅读顺序布局，而不是默认的从左到右顺序。 |
| [ETO_NO_RECT](#ETO-NO-RECT) | 此位指示记录未为文本输出指定边界矩形。 |
| [ETO_SMALL_CHARS](#ETO-SMALL-CHARS) | 此位指示输出文本字符串中字符的代码为 8 位，来源于 16 位 Unicode UTF16-LE 字符代码的低字节，假设高字节为 0。 |
| [ETO_NUMERICSLOCAL](#ETO-NUMERICSLOCAL) | 此位指示显示数字时应使用适合本地区域的数字。 |
| [ETO_NUMERICSLATIN](#ETO-NUMERICSLATIN) | 此位指示显示数字时应使用欧洲数字。 |
| [ETO_IGNORELANGUAGE](#ETO-IGNORELANGUAGE) | 此位指示不应对从右到左的字符串进行特殊的操作系统字形放置处理；即所有字形定位应由元文件中的绘图和状态记录负责。 |
| [ETO_PDY](#ETO-PDY) | 此位指示水平和垂直字符位移值 **SHOULD** 被提供 |
| [ETO_REVERSE_INDEX_MAP](#ETO-REVERSE-INDEX-MAP) | 此位为保留位，**SHOULD NOT** 被使用 |
### ETO_OPAQUE {#ETO-OPAQUE}
```
public static final int ETO_OPAQUE
```


此位指示应使用当前背景色填充矩形

### ETO_CLIPPED {#ETO-CLIPPED}
```
public static final int ETO_CLIPPED
```


此位指示应将文本裁剪到矩形内。

### ETO_GLYPH_INDEX {#ETO-GLYPH-INDEX}
```
public static final int ETO_GLYPH_INDEX
```


此位指示输出文本字符串中的字符代码实际上是 TrueType 字体中字符字形的索引。字形索引是特定于字体的，因此要在回放时显示正确的字符，使用的字体 **MUST** 与生成索引时使用的字体完全相同。

### ETO_RTLREADING {#ETO-RTLREADING}
```
public static final int ETO_RTLREADING
```


此位指示文本 **MUST** 以从右到左的阅读顺序布局，而非默认的从左到右顺序。仅当在回放设备上下文中选择的字体为希伯来语或阿拉伯语时，才 **SHOULD** 应用此设置。

### ETO_NO_RECT {#ETO-NO-RECT}
```
public static final int ETO_NO_RECT
```


此位指示记录未为文本输出指定边界矩形。

### ETO_SMALL_CHARS {#ETO-SMALL-CHARS}
```
public static final int ETO_SMALL_CHARS
```


此位指示输出文本字符串中字符的代码为 8 位，来源于 16 位 Unicode UTF16-LE 字符代码的低字节，假设高字节为 0。

### ETO_NUMERICSLOCAL {#ETO-NUMERICSLOCAL}
```
public static final int ETO_NUMERICSLOCAL
```


此位指示显示数字时应使用适合本地区域的数字。

### ETO_NUMERICSLATIN {#ETO-NUMERICSLATIN}
```
public static final int ETO_NUMERICSLATIN
```


此位指示显示数字时应使用欧洲数字。

### ETO_IGNORELANGUAGE {#ETO-IGNORELANGUAGE}
```
public static final int ETO_IGNORELANGUAGE
```


此位指示不应对从右到左的字符串进行特殊的操作系统字形放置处理；即所有字形定位应由元文件中的绘图和状态记录负责。

### ETO_PDY {#ETO-PDY}
```
public static final int ETO_PDY
```


此位指示水平和垂直字符位移值 **SHOULD** 被提供

### ETO_REVERSE_INDEX_MAP {#ETO-REVERSE-INDEX-MAP}
```
public static final int ETO_REVERSE_INDEX_MAP
```


此位为保留位，**SHOULD NOT** 被使用

