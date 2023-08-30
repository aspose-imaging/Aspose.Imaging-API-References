---
title: ColorComparisonMode
second_title: Aspose.Imaging for Java API Reference
description: Specifies how colors are compared during the Magic Wand algorithm.
type: docs
weight: 10
url: /java/com.aspose.imaging.magicwand/colorcomparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorComparisonMode extends System.Enum
```

Specifies how colors are compared during the Magic Wand algorithm.
## Fields

| Field | Description |
| --- | --- |
| [RgbDefault](#RgbDefault) | Colors are compared in the RGB color space. |
| [YuvDefault](#YuvDefault) | Colors are compared in the YUV color space. |
| [YuvLessLumaSensitive](#YuvLessLumaSensitive) | Colors are compared in the YUV color space. |
| [Custom](#Custom) | Color comparison algorithm is defined by user. |
### RgbDefault {#RgbDefault}
```
public static final int RgbDefault
```


Colors are compared in the RGB color space. Every color difference must satisfy the threshold.

### YuvDefault {#YuvDefault}
```
public static final int YuvDefault
```


Colors are compared in the YUV color space. Every color difference must satisfy the threshold.

### YuvLessLumaSensitive {#YuvLessLumaSensitive}
```
public static final int YuvLessLumaSensitive
```


Colors are compared in the YUV color space. Color information differences must satisfy the threshold, the threshold for luminance component is doubled.

### Custom {#Custom}
```
public static final int Custom
```


Color comparison algorithm is defined by user.

