---
title: "EmfPlusHueSaturationLightnessEffect"
second_title: "Aspose.Imaging for Java API 参考"
description: "HueSaturationLightnessEffect 对象指定对图像的色相、饱和度和亮度的调整。"
type: docs
weight: 46
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushuesaturationlightnesseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusHueSaturationLightnessEffect extends EmfPlusImageEffectsObjectType
```

HueSaturationLightnessEffect 对象指定对图像的色相、饱和度和亮度的调整。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusHueSaturationLightnessEffect()](#EmfPlusHueSaturationLightnessEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHueLevel()](#getHueLevel--) | 获取或设置 指定对色相的调整。 |
| [setHueLevel(int value)](#setHueLevel-int-) | 获取或设置 指定对色相的调整。 |
| [getSaturationLevel()](#getSaturationLevel--) | 获取或设置 指定对饱和度的调整。 |
| [setSaturationLevel(int value)](#setSaturationLevel-int-) | 获取或设置 指定对饱和度的调整。 |
| [getLightnessLevel()](#getLightnessLevel--) | 获取或设置指定对亮度的调整。 |
| [setLightnessLevel(int value)](#setLightnessLevel-int-) | 获取或设置指定对亮度的调整。 |
### EmfPlusHueSaturationLightnessEffect() {#EmfPlusHueSaturationLightnessEffect--}
```
public EmfPlusHueSaturationLightnessEffect()
```


### getHueLevel() {#getHueLevel--}
```
public int getHueLevel()
```


获取或设置指定对色相的调整。-180 \u2264 value < 0 负值表示在色轮上顺时针旋转。0 值为 0 表示色相必须不改变。0 < value \u2264 180 正值表示在色轮上逆时针旋转。

值：色相级别。

**Returns:**
int
### setHueLevel(int value) {#setHueLevel-int-}
```
public void setHueLevel(int value)
```


获取或设置指定对色相的调整。-180 \u2264 value < 0 负值表示在色轮上顺时针旋转。0 值为 0 表示色相必须不改变。0 < value \u2264 180 正值表示在色轮上逆时针旋转。

值：色相级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSaturationLevel() {#getSaturationLevel--}
```
public int getSaturationLevel()
```


获取或设置指定对饱和度的调整。-100 \u2264 value < 0 负值表示降低饱和度。0 值为 0 表示饱和度必须不改变。0 < value \u2264 100 正值表示提高饱和度。

值：饱和度级别。

**Returns:**
int
### setSaturationLevel(int value) {#setSaturationLevel-int-}
```
public void setSaturationLevel(int value)
```


获取或设置指定对饱和度的调整。-100 \u2264 value < 0 负值表示降低饱和度。0 值为 0 表示饱和度必须不改变。0 < value \u2264 100 正值表示提高饱和度。

值：饱和度级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLightnessLevel() {#getLightnessLevel--}
```
public int getLightnessLevel()
```


获取或设置指定对亮度的调整。-100 \u2264 value < 0 负值表示降低亮度。0 值为 0 表示亮度必须不改变。0 < value \u2264 100 正值表示提高亮度。

值：亮度级别。

**Returns:**
int
### setLightnessLevel(int value) {#setLightnessLevel-int-}
```
public void setLightnessLevel(int value)
```


获取或设置指定对亮度的调整。-100 \u2264 value < 0 负值表示降低亮度。0 值为 0 表示亮度必须不改变。0 < value \u2264 100 正值表示提高亮度。

值：亮度级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

