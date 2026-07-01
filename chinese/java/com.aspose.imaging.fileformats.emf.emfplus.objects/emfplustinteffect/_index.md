---
title: "EmfPlusTintEffect"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 TintEffect 对象指定在图像中对指定色相添加黑色或白色。"
type: docs
weight: 79
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

该 TintEffect 对象指定在图像中对指定色相添加黑色或白色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHue()](#getHue--) | 获取或设置一个 32 位有符号整数，指定色调（hue），即色调效果将应用于的颜色。 |
| [setHue(int value)](#setHue-int-) | 获取或设置一个 32 位有符号整数，指定色调（hue），即色调效果将应用于的颜色。 |
| [getAmount()](#getAmount--) | 获取或设置一个 32 位有符号整数，指定色调的增强或减弱程度。 |
| [setAmount(int value)](#setAmount-int-) | 获取或设置一个 32 位有符号整数，指定色调的增强或减弱程度。 |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


获取或设置一个 32 位有符号整数，指定色调（hue），即色调效果将应用于的颜色。-180 \\u2264 value < 0 表示从蓝色起逆时针旋转色轮至指定角度的颜色。0 值 0 表示色轮上的蓝色。0 < value \\u2264 180 表示从蓝色起顺时针旋转色轮至指定角度的颜色。

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


获取或设置一个 32 位有符号整数，指定色调（hue），即色调效果将应用于的颜色。-180 \\u2264 value < 0 表示从蓝色起逆时针旋转色轮至指定角度的颜色。0 值 0 表示色轮上的蓝色。0 < value \\u2264 180 表示从蓝色起顺时针旋转色轮至指定角度的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


获取或设置一个 32 位有符号整数，指定色调的增强或减弱程度。-100 \\u2264 value < 0 负值表示色调的减弱程度，相当于添加黑色。0 值 0 表示色调必须保持不变。0 < value \\u2264 100 正值表示色调的增强程度，相当于添加白色。

值：量。

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


获取或设置一个 32 位有符号整数，指定色调的增强或减弱程度。-100 \\u2264 value < 0 负值表示色调的减弱程度，相当于添加黑色。0 值 0 表示色调必须保持不变。0 < value \\u2264 100 正值表示色调的增强程度，相当于添加白色。

值：量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

