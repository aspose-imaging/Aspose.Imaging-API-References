---
title: "EmfDibColors"
second_title: "Aspose.Imaging for Java API 参考"
description: "DIBColors 枚举定义了如何解释 DIB 颜色表中的值。"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfDibColors extends System.Enum
```

DIBColors 枚举定义了如何解释 DIB 颜色表中的值。
## 字段

| 字段 | 描述 |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | 颜色表包含字面 RGB 值 |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | 颜色表由一个指向 LogPalette 对象（第 2.2.17 节）的 16 位索引数组组成，该对象当前在回放设备上下文中定义。 |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | 不存在颜色表。 |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


颜色表包含字面 RGB 值

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


颜色表由一个指向 LogPalette 对象（第 2.2.17 节）的 16 位索引数组组成，该对象当前在回放设备上下文中定义。

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


不存在颜色表。DIB 中的像素是指向回放设备上下文中当前逻辑调色板的索引。

