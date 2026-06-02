---
title: "WmfColorUsageEnum"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "ColorUsage 枚举指定在设备无关位图（DIB）中是否存在颜色表以及如何解释其值。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfcolorusageenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfColorUsageEnum extends System.Enum
```

该 ColorUsage 枚举指定设备无关位图（DIB）中是否存在颜色表以及如何解释其值。
## 字段

| 字段 | 描述 |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | 颜色表包含由 RGBQuad 对象指定的 RGB 值（第 2.2.2.20 节）。 |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | 颜色表包含指向播放设备上下文中当前逻辑调色板的 16 位索引。 |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | 不存在颜色表。 |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


颜色表包含由 RGBQuad 对象指定的 RGB 值（第 2.2.2.20 节）。

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


颜色表包含指向播放设备上下文中当前逻辑调色板的 16 位索引。

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


不存在颜色表。DIB 中的像素是指向播放设备上下文中当前逻辑调色板的索引。

