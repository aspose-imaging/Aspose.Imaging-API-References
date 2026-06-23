---
title: "WmfFontQuality"
second_title: "Aspose.Imaging for Java API 参考"
description: "FontQuality 枚举指定在渲染文本时，逻辑字体的属性应与物理字体的属性匹配的程度。"
type: docs
weight: 19
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFontQuality extends System.Enum
```

FontQuality 枚举指定在渲染文本时，逻辑字体的属性应与物理字体的属性匹配的程度。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Default](#Default) | 指定字体的字符质量不重要，因此可以使用 DRAFT。 |
| [Draft](#Draft) | 指定字体的字符质量不如逻辑属性的匹配重要。 |
| [Proof](#Proof) | 指定字体的字符质量比逻辑属性的匹配更重要。 |
| [Nonantialiased](#Nonantialiased) | 指定在渲染文本时不应使用抗锯齿。 |
| [Antialiased](#Antialiased) | 指定在渲染文本时应使用抗锯齿（如果字体支持）。 |
| [Cleartype](#Cleartype) | 指定在渲染文本时应使用 ClearType 抗锯齿（如果字体支持）。 |
### Default {#Default}
```
public static final byte Default
```


指定字体的字符质量不重要，因此可以使用 DRAFT。

### Draft {#Draft}
```
public static final byte Draft
```


指定字体的字符质量不如逻辑属性的匹配重要。对于光栅化字体，应启用缩放，这意味着可用的字体大小更多。

### Proof {#Proof}
```
public static final byte Proof
```


指定字体的字符质量比逻辑属性的匹配更重要。对于光栅化字体，应禁用缩放，并应选择最接近的字体大小。

### Nonantialiased {#Nonantialiased}
```
public static final byte Nonantialiased
```


指定在渲染文本时不应使用抗锯齿。

### Antialiased {#Antialiased}
```
public static final byte Antialiased
```


指定在渲染文本时应使用抗锯齿（如果字体支持）。

### Cleartype {#Cleartype}
```
public static final byte Cleartype
```


指定在渲染文本时应使用 ClearType 抗锯齿（如果字体支持）。

