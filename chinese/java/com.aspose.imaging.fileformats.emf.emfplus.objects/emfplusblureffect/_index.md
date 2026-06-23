---
title: "EmfPlusBlurEffect"
second_title: "Aspose.Imaging for Java API 参考"
description: "BlurEffect 对象指定图像中像素强度差异的降低。"
type: docs
weight: 19
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

BlurEffect 对象指定图像中像素强度差异的降低。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 获取或设置一个 32 位浮点数，指定以像素为单位的模糊半径，该半径决定在计算给定像素的新值时涉及的像素数量。 |
| [setBlurRadius(float value)](#setBlurRadius-float-) | 获取或设置一个 32 位浮点数，指定以像素为单位的模糊半径，该半径决定在计算给定像素的新值时涉及的像素数量。 |
| [getExpandEdge()](#getExpandEdge--) | 获取或设置一个 32 位布尔值，指定位图是否按等于 BlurRadius 值的量扩展以产生柔和边缘。 |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | 获取或设置一个 32 位布尔值，指定位图是否按等于 BlurRadius 值的量扩展以产生柔和边缘。 |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


获取或设置一个 32 位浮点数，指定以像素为单位的模糊半径，该半径决定在计算给定像素的新值时涉及的像素数量。此值必须在 0.0 到 255.0 的范围内。

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


获取或设置一个 32 位浮点数，指定以像素为单位的模糊半径，该半径决定在计算给定像素的新值时涉及的像素数量。此值必须在 0.0 到 255.0 的范围内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


获取或设置一个 32 位布尔值，指定位图是否按等于 BlurRadius 值的量扩展以产生柔和边缘。此值必须是以下之一：FALSE 0x00000000 位图的大小必须不改变，其柔和边缘应被裁剪至 BlurRadius 的大小。TRUE 0x00000001 位图的大小应按等于 BlurRadius 的量扩展以产生柔和边缘。

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


获取或设置一个 32 位布尔值，指定位图是否按等于 BlurRadius 值的量扩展以产生柔和边缘。此值必须是以下之一：FALSE 0x00000000 位图的大小必须不改变，其柔和边缘应被裁剪至 BlurRadius 的大小。TRUE 0x00000001 位图的大小应按等于 BlurRadius 的量扩展以产生柔和边缘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

