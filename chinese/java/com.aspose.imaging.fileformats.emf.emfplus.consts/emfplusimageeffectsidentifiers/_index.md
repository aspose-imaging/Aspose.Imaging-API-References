---
title: "EmfPlusImageEffectsIdentifiers"
second_title: "Aspose.Imaging for Java API 参考"
description: "ImageEffects 标识符定义了用于指定图形图像效果的标准 GUID。"
type: docs
weight: 28
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusimageeffectsidentifiers/
---
**Inheritance:**
java.lang.Object
```
public final class EmfPlusImageEffectsIdentifiers
```

ImageEffects 标识符定义了用于指定图形图像效果的标准 GUID。这些标识符由设备驱动程序用于公布它们对这些效果的支持级别。标识符常量使用 GUID 大括号字符串表示法（[MS-DTYP] 第 2.3.4.3 节）进行定义。

--------------------

图像效果标识符和图像效果参数块由 [EmfPlusSerializableObject](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject) 记录为 [EmfPlusDrawImagePoints](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints) 记录指定。
## 字段

| 字段 | 描述 |
| --- | --- |
| [BLUR_EFFECT_GUID](#BLUR-EFFECT-GUID) | 指定模糊效果。 |
| [BRIGHTNESS_CONTRAST_EFFECT_GUID](#BRIGHTNESS-CONTRAST-EFFECT-GUID) | 指定亮度对比度效果。 |
| [COLOR_BALANCE_EFFECT_GUID](#COLOR-BALANCE-EFFECT-GUID) | 指定颜色平衡效果。 |
| [COLOR_CURVE_EFFECT_GUID](#COLOR-CURVE-EFFECT-GUID) | 指定颜色曲线效果。 |
| [COLOR_LOOKUP_TABLE_EFFECT_GUID](#COLOR-LOOKUP-TABLE-EFFECT-GUID) | 指定颜色查找表效果。 |
| [COLOR_MATRIX_EFFECT_GUID](#COLOR-MATRIX-EFFECT-GUID) | 指定颜色矩阵效果。 |
| [HUE_SATURATION_LIGHTNESS_EFFECT_GUID](#HUE-SATURATION-LIGHTNESS-EFFECT-GUID) | 指定色相、饱和度、亮度效果。 |
| [LEVELS_EFFECT_GUID](#LEVELS-EFFECT-GUID) | 指定色阶效果。 |
| [RED_EYE_CORRECTION_EFFECT_GUID](#RED-EYE-CORRECTION-EFFECT-GUID) | 指定红眼校正效果。 |
| [SHARPEN_EFFECT_GUID](#SHARPEN-EFFECT-GUID) | 指定锐化效果。 |
| [TINT_EFFECT_GUID](#TINT-EFFECT-GUID) | 指定色调效果。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [contain(String objectGuid)](#contain-java.lang.String-) | 包含指定对象的唯一标识符。 |
### BLUR_EFFECT_GUID {#BLUR-EFFECT-GUID}
```
public static final String BLUR_EFFECT_GUID
```


指定模糊效果。

### BRIGHTNESS_CONTRAST_EFFECT_GUID {#BRIGHTNESS-CONTRAST-EFFECT-GUID}
```
public static final String BRIGHTNESS_CONTRAST_EFFECT_GUID
```


指定亮度对比度效果。

### COLOR_BALANCE_EFFECT_GUID {#COLOR-BALANCE-EFFECT-GUID}
```
public static final String COLOR_BALANCE_EFFECT_GUID
```


指定颜色平衡效果。

### COLOR_CURVE_EFFECT_GUID {#COLOR-CURVE-EFFECT-GUID}
```
public static final String COLOR_CURVE_EFFECT_GUID
```


指定颜色曲线效果。

### COLOR_LOOKUP_TABLE_EFFECT_GUID {#COLOR-LOOKUP-TABLE-EFFECT-GUID}
```
public static final String COLOR_LOOKUP_TABLE_EFFECT_GUID
```


指定颜色查找表效果。

### COLOR_MATRIX_EFFECT_GUID {#COLOR-MATRIX-EFFECT-GUID}
```
public static final String COLOR_MATRIX_EFFECT_GUID
```


指定颜色矩阵效果。

### HUE_SATURATION_LIGHTNESS_EFFECT_GUID {#HUE-SATURATION-LIGHTNESS-EFFECT-GUID}
```
public static final String HUE_SATURATION_LIGHTNESS_EFFECT_GUID
```


指定色相、饱和度、亮度效果。

### LEVELS_EFFECT_GUID {#LEVELS-EFFECT-GUID}
```
public static final String LEVELS_EFFECT_GUID
```


指定色阶效果。

### RED_EYE_CORRECTION_EFFECT_GUID {#RED-EYE-CORRECTION-EFFECT-GUID}
```
public static final String RED_EYE_CORRECTION_EFFECT_GUID
```


指定红眼校正效果。

### SHARPEN_EFFECT_GUID {#SHARPEN-EFFECT-GUID}
```
public static final String SHARPEN_EFFECT_GUID
```


指定锐化效果。

### TINT_EFFECT_GUID {#TINT-EFFECT-GUID}
```
public static final String TINT_EFFECT_GUID
```


指定色调效果。

### contain(String objectGuid) {#contain-java.lang.String-}
```
public static boolean contain(String objectGuid)
```


包含指定对象的唯一标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objectGuid | java.lang.String | 对象的唯一标识符。 |

**Returns:**
布尔值 - 如果包含则为 True。
