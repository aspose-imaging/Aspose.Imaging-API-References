---
title: "WmfGamutMappingIntent"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 GamutMappingIntent 枚举指定逻辑颜色与物理颜色之间的关系。"
type: docs
weight: 20
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

该 GamutMappingIntent 枚举指定逻辑颜色与物理颜色之间的关系。
## 字段

| 字段 | 描述 |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | 指定应保持白点。 |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | 指定应保持饱和度。 |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | 指定应保持颜色计量匹配。 |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | 指定应保持对比度。 |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


指定应保持白点。通常在需要将逻辑颜色匹配到目标色域中最近的物理颜色时使用。Intent: Match ICC name: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


指定应保持饱和度。通常用于商业图表及其他不需要抖动的情况。Intent: Graphic ICC name: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


指定应保持颜色计量匹配。通常用于图形设计和命名颜色。Intent: Proof ICC name: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


指定应保持对比度。通常用于照片和自然图像。Intent: Picture ICC name: Perceptual

