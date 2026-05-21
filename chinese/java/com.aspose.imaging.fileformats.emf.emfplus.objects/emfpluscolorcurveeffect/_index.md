---
title: "EmfPlusColorCurveEffect"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "ColorCurveEffect 对象指定图像颜色曲线的八种调整之一。"
type: docs
weight: 27
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

ColorCurveEffect 对象指定图像颜色曲线的八种调整之一。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | 获取或设置 32 位无符号整数，指定要应用于位图颜色的曲线调整。 |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | 获取或设置 32 位无符号整数，指定要应用于位图颜色的曲线调整。 |
| [getCurveChannel()](#getCurveChannel--) | 获取或设置 32 位无符号整数，指定曲线调整所作用的颜色通道。 |
| [setCurveChannel(int value)](#setCurveChannel-int-) | 获取或设置 32 位无符号整数，指定曲线调整所作用的颜色通道。 |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | 获取或设置 32 位有符号整数，指定对 CurveChannel 指定的颜色通道的曲线调整强度。 |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | 获取或设置 32 位有符号整数，指定对 CurveChannel 指定的颜色通道的曲线调整强度。 |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


获取或设置 32 位无符号整数，指定要应用于位图颜色的曲线调整。此值必须在 CurveAdjustments 枚举（第 2.1.1.7 节）中定义。

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


获取或设置 32 位无符号整数，指定要应用于位图颜色的曲线调整。此值必须在 CurveAdjustments 枚举（第 2.1.1.7 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


获取或设置 32 位无符号整数，指定曲线调整所作用的颜色通道。此值必须在 CurveChannel 枚举（第 2.1.1.8 节）中定义。

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


获取或设置 32 位无符号整数，指定曲线调整所作用的颜色通道。此值必须在 CurveChannel 枚举（第 2.1.1.8 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


获取或设置 32 位有符号整数，指定对 CurveChannel 指定的颜色通道的曲线调整强度。此字段的有效取值范围根据 CurveAdjustment 的值而变化，具体如下：曝光调整范围：-255 \\u2264 value < 0 时，随着值减小，图像的曝光应减小。0 表示值为 0 时曝光不得改变。0 < value \\u2264 255 时，随着值增大，图像的曝光应增大。密度调整范围：-255 \\u2264 value < 0 时，随着值减小，图像的密度应减小，导致图像更暗。0 表示密度不得改变。0 < value \\u2264 255 时，随着值增大，图像的密度应增大。对比度调整范围：-100 \\u2264 value < 0 时，随着值减小，图像的对比度应减小。0 表示对比度不得改变。0 < value \\u2264 100 时，随着值增大，图像的对比度应增大。高光调整范围：-100 \\u2264 value < 0 时，随着值减小，图像的亮部应显得更暗。0 表示高光不得改变。0 < value \\u2264 100 时，随着值增大，图像的亮部应显得更亮。阴影调整范围：-100 \\u2264 value < 0 时，随着值减小，图像的暗部应显得更暗。0 表示阴影不得改变。0 < value \\u2264 100 时，随着值增大，图像的暗部应显得更亮。白色饱和度调整范围：0 \\u2014 255 时，随着值增大，颜色通道强度范围的上限增加。黑色饱和度调整范围：0 \\u2014 255 时，随着值增大，颜色通道强度范围的下限增加。

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


获取或设置 32 位有符号整数，指定对 CurveChannel 指定的颜色通道的曲线调整强度。此字段的有效取值范围根据 CurveAdjustment 的值而变化，具体如下：曝光调整范围：-255 \\u2264 value < 0 时，随着值减小，图像的曝光应减小。0 表示值为 0 时曝光不得改变。0 < value \\u2264 255 时，随着值增大，图像的曝光应增大。密度调整范围：-255 \\u2264 value < 0 时，随着值减小，图像的密度应减小，导致图像更暗。0 表示密度不得改变。0 < value \\u2264 255 时，随着值增大，图像的密度应增大。对比度调整范围：-100 \\u2264 value < 0 时，随着值减小，图像的对比度应减小。0 表示对比度不得改变。0 < value \\u2264 100 时，随着值增大，图像的对比度应增大。高光调整范围：-100 \\u2264 value < 0 时，随着值减小，图像的亮部应显得更暗。0 表示高光不得改变。0 < value \\u2264 100 时，随着值增大，图像的亮部应显得更亮。阴影调整范围：-100 \\u2264 value < 0 时，随着值减小，图像的暗部应显得更暗。0 表示阴影不得改变。0 < value \\u2264 100 时，随着值增大，图像的暗部应显得更亮。白色饱和度调整范围：0 \\u2014 255 时，随着值增大，颜色通道强度范围的上限增加。黑色饱和度调整范围：0 \\u2014 255 时，随着值增大，颜色通道强度范围的下限增加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

