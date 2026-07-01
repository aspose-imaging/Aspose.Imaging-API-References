---
title: "ColorComparisonMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "指定在 Magic Wand 算法期间颜色的比较方式。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.magicwand/colorcomparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorComparisonMode extends System.Enum
```

指定在 Magic Wand 算法期间颜色的比较方式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [RgbDefault](#RgbDefault) | 颜色在 RGB 颜色空间中进行比较。 |
| [YuvDefault](#YuvDefault) | 颜色在 YUV 颜色空间中进行比较。 |
| [YuvLessLumaSensitive](#YuvLessLumaSensitive) | 颜色在 YUV 颜色空间中进行比较。 |
| [Custom](#Custom) | 颜色比较算法由用户定义。 |
### RgbDefault {#RgbDefault}
```
public static final int RgbDefault
```


颜色在 RGB 颜色空间中进行比较。每个颜色差异必须满足阈值。

### YuvDefault {#YuvDefault}
```
public static final int YuvDefault
```


颜色在 YUV 颜色空间中进行比较。每个颜色差异必须满足阈值。

### YuvLessLumaSensitive {#YuvLessLumaSensitive}
```
public static final int YuvLessLumaSensitive
```


颜色在 YUV 颜色空间中进行比较。颜色信息差异必须满足阈值，亮度分量的阈值加倍。

### Custom {#Custom}
```
public static final int Custom
```


颜色比较算法由用户定义。

