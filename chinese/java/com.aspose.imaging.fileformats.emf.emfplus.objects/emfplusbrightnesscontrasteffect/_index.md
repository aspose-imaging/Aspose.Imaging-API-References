---
title: "EmfPlusBrightnessContrastEffect"
second_title: "Aspose.Imaging for Java API 参考"
description: "BrightnessContrastEffect 对象指定图像中最亮和最暗区域的扩展或收缩。"
type: docs
weight: 23
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

BrightnessContrastEffect 对象指定图像中最亮和最暗区域的扩展或收缩。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | 获取或设置一个 32 位有符号整数，指定亮度级别。 |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | 获取或设置一个 32 位有符号整数，指定亮度级别。 |
| [getContrastLevel()](#getContrastLevel--) | 获取或设置一个 32 位有符号整数，指定对比度级别。 |
| [setContrastLevel(int value)](#setContrastLevel-int-) | 获取或设置一个 32 位有符号整数，指定对比度级别。 |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


获取或设置一个 32 位有符号整数，指定亮度级别。该值必须在 -255 到 255 的范围内，效果如下：-255 \\u2264 value < 0 当值减小时，图像的亮度应降低。0 值为 0 表示亮度不得改变。0 < value \\u2264 255 当值增大时，图像的亮度应增加。

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


获取或设置一个 32 位有符号整数，指定亮度级别。该值必须在 -255 到 255 的范围内，效果如下：-255 \\u2264 value < 0 当值减小时，图像的亮度应降低。0 值为 0 表示亮度不得改变。0 < value \\u2264 255 当值增大时，图像的亮度应增加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


获取或设置一个 32 位有符号整数，指定对比度级别。该值必须在 -100 到 100 的范围内，效果如下：-100 \\u2264 value < 0 当值减小时，图像的对比度应降低。0 值为 0 表示对比度不得改变。0 < value \\u2264 100 当值增大时，图像的对比度应增加。

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


获取或设置一个 32 位有符号整数，指定对比度级别。该值必须在 -100 到 100 的范围内，效果如下：-100 \\u2264 value < 0 当值减小时，图像的对比度应降低。0 值为 0 表示对比度不得改变。0 < value \\u2264 100 当值增大时，图像的对比度应增加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

