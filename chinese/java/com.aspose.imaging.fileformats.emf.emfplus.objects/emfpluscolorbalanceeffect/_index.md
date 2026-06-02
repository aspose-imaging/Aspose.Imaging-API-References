---
title: "EmfPlusColorBalanceEffect"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "ColorBalanceEffect 对象指定对图像中红、绿、蓝相对量的调整。"
type: docs
weight: 26
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

ColorBalanceEffect 对象指定对图像中红、绿、蓝相对量的调整。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | 获取或设置一个 32 位有符号整数，指定图像中红色量的变化。 |
| [setCyanRed(int value)](#setCyanRed-int-) | 获取或设置一个 32 位有符号整数，指定图像中红色量的变化。 |
| [getMagentaGreen()](#getMagentaGreen--) | 获取或设置一个 32 位有符号整数，指定图像中绿色量的变化。 |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | 获取或设置一个 32 位有符号整数，指定图像中绿色量的变化。 |
| [getYellowBlue()](#getYellowBlue--) | 获取或设置一个 32 位有符号整数，指定图像中蓝色量的变化。 |
| [setYellowBlue(int value)](#setYellowBlue-int-) | 获取或设置一个 32 位有符号整数，指定图像中蓝色量的变化。 |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


获取或设置一个 32 位有符号整数，指定图像中红色量的变化。此值必须在 -100 到 100 的范围内，效果如下：-100 \\u2264 value < 0 当值减小时，图像中的红色量应减小，青色量应增大。0 值为 0 表示红色和青色的量不得改变。0 < value \\u2264 100 当值增大时，图像中的红色量应增大，青色量应减小。

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


获取或设置一个 32 位有符号整数，指定图像中红色量的变化。此值必须在 -100 到 100 的范围内，效果如下：-100 \\u2264 value < 0 当值减小时，图像中的红色量应减小，青色量应增大。0 值为 0 表示红色和青色的量不得改变。0 < value \\u2264 100 当值增大时，图像中的红色量应增大，青色量应减小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


获取或设置一个 32 位有符号整数，指定图像中绿色量的变化。此值必须在 -100 到 100 的范围内，效果如下：-100 \\u2264 value < 0 当值减小时，图像中的绿色量应减小，洋红量应增大。0 值为 0 表示绿色和洋红的量不得改变。0 < value \\u2264 100 当值增大时，图像中的绿色量应增大，洋红量应减小。

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


获取或设置一个 32 位有符号整数，指定图像中绿色量的变化。此值必须在 -100 到 100 的范围内，效果如下：-100 \\u2264 value < 0 当值减小时，图像中的绿色量应减小，洋红量应增大。0 值为 0 表示绿色和洋红的量不得改变。0 < value \\u2264 100 当值增大时，图像中的绿色量应增大，洋红量应减小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


获取或设置一个 32 位有符号整数，指定图像中蓝色量的变化。此值必须在 -100 到 100 的范围内，效果如下：-100 \\u2264 value < 0 当值减小时，图像中的蓝色量应减小，黄色量应增大。0 值为 0 表示蓝色和黄色的量不得改变。0 < value \\u2264 100 当值增大时，图像中的蓝色量应增大，黄色量应减小。

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


获取或设置一个 32 位有符号整数，指定图像中蓝色量的变化。此值必须在 -100 到 100 的范围内，效果如下：-100 \\u2264 value < 0 当值减小时，图像中的蓝色量应减小，黄色量应增大。0 值为 0 表示蓝色和黄色的量不得改变。0 < value \\u2264 100 当值增大时，图像中的蓝色量应增大，黄色量应减小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

