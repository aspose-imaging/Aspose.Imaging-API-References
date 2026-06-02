---
title: "EmfPlusLevelsEffect"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "LevelsEffect 对象指定对图像的高光、中间调和阴影的调整。"
type: docs
weight: 51
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

LevelsEffect 对象指定对图像高光、中间调和阴影的调整。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHighlight()](#getHighlight--) | 获取或设置，指定对图像高光的提亮程度。 |
| [setHighlight(int value)](#setHighlight-int-) | 获取或设置，指定对图像高光的提亮程度。 |
| [getMidTone()](#getMidTone--) | 获取或设置，指定对图像中间调的提亮或加暗程度。 |
| [setMidTone(int value)](#setMidTone-int-) | 获取或设置，指定对图像中间调的提亮或加暗程度。 |
| [getShadow()](#getShadow--) | 获取或设置，指定对图像阴影的加暗程度。 |
| [setShadow(int value)](#setShadow-int-) | 获取或设置，指定对图像阴影的加暗程度。 |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


获取或设置，指定对图像高光的提亮程度。强度范围高端的颜色通道值比中间或低端的值变化更大，这意味着可以在不失去图像暗部对比度的情况下提亮图像。0 \\u2264 value < 表示强度百分比高于此阈值的高光应增加。100 表示高光不得改变。

值：高光。

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


获取或设置，指定对图像高光的提亮程度。强度范围高端的颜色通道值比中间或低端的值变化更大，这意味着可以在不失去图像暗部对比度的情况下提亮图像。0 \\u2264 value < 表示强度百分比高于此阈值的高光应增加。100 表示高光不得改变。

值：高光。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


获取或设置，指定对图像中间调的提亮或加暗程度。强度范围中部的颜色通道值比高端或低端的值变化更大，这意味着可以在不失去图像最暗和最亮部分对比度的情况下对图像进行提亮或加暗。-100 \\u2264 value < 0 表示中间调被加暗。0 表示中间调不得改变。0 < value \\u2264 100 表示中间调被提亮。

值：中间调。

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


获取或设置，指定对图像中间调的提亮或加暗程度。强度范围中部的颜色通道值比高端或低端的值变化更大，这意味着可以在不失去图像最暗和最亮部分对比度的情况下对图像进行提亮或加暗。-100 \\u2264 value < 0 表示中间调被加暗。0 表示中间调不得改变。0 < value \\u2264 100 表示中间调被提亮。

值：中间调。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


获取或设置，指定对图像阴影的加暗程度。强度范围低端的颜色通道值比中间或高端的值变化更大，这意味着可以在不失去图像亮部对比度的情况下加暗图像。0 表示阴影不得改变。0 < value \\u2264 100 表示强度百分比低于此阈值的阴影被加暗。

值：阴影。

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


获取或设置，指定对图像阴影的加暗程度。强度范围低端的颜色通道值比中间或高端的值变化更大，这意味着可以在不失去图像亮部对比度的情况下加暗图像。0 表示阴影不得改变。0 < value \\u2264 100 表示强度百分比低于此阈值的阴影被加暗。

值：阴影。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

