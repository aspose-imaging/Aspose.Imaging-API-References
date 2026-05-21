---
title: "WmfPitchFont"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "PitchFont 枚举定义用于指定字体特性的值。"
type: docs
weight: 29
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfpitchfont/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPitchFont extends System.Enum
```

PitchFont 枚举定义了用于指定字体特性的值。这些值用于指示字体中的字符是固定宽度、可变宽度，还是等距。
## 字段

| 字段 | 描述 |
| --- | --- |
| [DEFAULT_PITCH](#DEFAULT-PITCH) | 默认等距，取决于实现。 |
| [FIXED_PITCH](#FIXED-PITCH) | 固定等距，意味着在字符串输出时字体中的所有字符占用相同的宽度。 |
| [VARIABLE_PITCH](#VARIABLE-PITCH) | 可变等距，意味着在字符串输出时字体中的字符占用的宽度与字形的实际宽度成比例。 |
### DEFAULT_PITCH {#DEFAULT-PITCH}
```
public static final byte DEFAULT_PITCH
```


默认等距，取决于实现。

### FIXED_PITCH {#FIXED-PITCH}
```
public static final byte FIXED_PITCH
```


固定等距，意味着在字符串输出时字体中的所有字符占用相同的宽度。

### VARIABLE_PITCH {#VARIABLE-PITCH}
```
public static final byte VARIABLE_PITCH
```


可变等距，意味着在字符串输出时字体中的字符占用的宽度与字形的实际宽度成比例。例如，"i" 和空格字符的宽度通常远小于 "W" 或 "O" 字符的宽度。

