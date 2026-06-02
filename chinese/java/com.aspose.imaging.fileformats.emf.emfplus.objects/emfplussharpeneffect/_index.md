---
title: "EmfPlusSharpenEffect"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "SharpenEffect 对象指定图像中像素强度差异的增强。"
type: docs
weight: 72
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

SharpenEffect 对象指定图像中像素强度差异的增强。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 获取或设置 一个 32 位浮点数，指定以像素为单位的锐化半径，该半径决定在计算给定像素的新值时涉及的像素数量。 |
| [setRadius(float value)](#setRadius-float-) | 获取或设置 一个 32 位浮点数，指定以像素为单位的锐化半径，该半径决定在计算给定像素的新值时涉及的像素数量。 |
| [getAmount()](#getAmount--) | 获取或设置 一个 32 位浮点数，指定给定像素与周围像素之间的强度差异。 |
| [setAmount(float value)](#setAmount-float-) | 获取或设置 一个 32 位浮点数，指定给定像素与周围像素之间的强度差异。 |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


获取或设置 一个 32 位浮点数，指定以像素为单位的锐化半径，该半径决定在计算给定像素的新值时涉及的像素数量。随着该值的增大，参与计算的像素数量增加，生成的位图 SHOULD 变得更锐利。

值：半径。

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


获取或设置 一个 32 位浮点数，指定以像素为单位的锐化半径，该半径决定在计算给定像素的新值时涉及的像素数量。随着该值的增大，参与计算的像素数量增加，生成的位图 SHOULD 变得更锐利。

值：半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


获取或设置 一个 32 位浮点数，指定给定像素与周围像素之间的强度差异。0 指定锐化 MUST NOT 被执行。0 < value \u2264 100 随着该值的增大，像素之间的强度差异 SHOULD 增加。

值：量。

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


获取或设置 一个 32 位浮点数，指定给定像素与周围像素之间的强度差异。0 指定锐化 MUST NOT 被执行。0 < value \u2264 100 随着该值的增大，像素之间的强度差异 SHOULD 增加。

值：量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

