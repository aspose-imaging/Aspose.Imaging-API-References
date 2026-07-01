---
title: "EmfColorAdjustment"
second_title: "Aspose.Imaging for Java API 参考"
description: "ColorAdjustment 对象定义了用于在位块传输中调整源位图颜色的值。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfColorAdjustment extends EmfObject
```

ColorAdjustment 对象定义了用于在位块传输中调整源位图颜色的值。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfColorAdjustment()](#EmfColorAdjustment--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSize()](#getSize--) | 获取或设置一个 16 位无符号整数，指定此对象的字节大小。 |
| [setSize(short value)](#setSize-short-) | 获取或设置一个 16 位无符号整数，指定此对象的字节大小。 |
| [getValues()](#getValues--) | 获取或设置一个 16 位无符号整数，用于指定如何准备输出图像。 |
| [setValues(int value)](#setValues-int-) | 获取或设置一个 16 位无符号整数，用于指定如何准备输出图像。 |
| [getIlluminantIndex()](#getIlluminantIndex--) | 获取或设置一个 16 位无符号整数，用于指定图像观看时所使用的标准光源类型，取自 Illuminant 枚举（第 2.1.19 节）。 |
| [setIlluminantIndex(int value)](#setIlluminantIndex-int-) | 获取或设置一个 16 位无符号整数，用于指定图像观看时所使用的标准光源类型，取自 Illuminant 枚举（第 2.1.19 节）。 |
| [getRedGamma()](#getRedGamma--) | 获取或设置一个 16 位无符号整数，用于指定源颜色中红色基色的 n 次幂伽马校正值。 |
| [setRedGamma(short value)](#setRedGamma-short-) | 获取或设置一个 16 位无符号整数，用于指定源颜色中红色基色的 n 次幂伽马校正值。 |
| [getGreenGamma()](#getGreenGamma--) | 获取或设置一个 16 位无符号整数，用于指定源颜色中绿色基色的 n 次幂伽马校正值。 |
| [setGreenGamma(short value)](#setGreenGamma-short-) | 获取或设置一个 16 位无符号整数，用于指定源颜色中绿色基色的 n 次幂伽马校正值。 |
| [getBlueGamma()](#getBlueGamma--) | 获取或设置一个 16 位无符号整数，用于指定源颜色中蓝色基色的 n 次幂伽马校正值。 |
| [setBlueGamma(short value)](#setBlueGamma-short-) | 获取或设置一个 16 位无符号整数，用于指定源颜色中蓝色基色的 n 次幂伽马校正值。 |
| [getReferenceBlack()](#getReferenceBlack--) | 获取或设置一个 16 位无符号整数，用于指定源颜色的黑色参考值。 |
| [setReferenceBlack(short value)](#setReferenceBlack-short-) | 获取或设置一个 16 位无符号整数，用于指定源颜色的黑色参考值。 |
| [getReferenceWhite()](#getReferenceWhite--) | 获取或设置一个 16 位无符号整数，用于指定源颜色的白色参考值。 |
| [setReferenceWhite(short value)](#setReferenceWhite-short-) | 获取或设置一个 16 位无符号整数，用于指定源颜色的白色参考值。 |
| [getContrast()](#getContrast--) | 获取或设置一个 16 位有符号整数，用于指定对源对象应用的对比度量。 |
| [setContrast(short value)](#setContrast-short-) | 获取或设置一个 16 位有符号整数，用于指定对源对象应用的对比度量。 |
| [getBrightness()](#getBrightness--) | 获取或设置一个 16 位有符号整数，用于指定对源对象应用的亮度量。 |
| [setBrightness(short value)](#setBrightness-short-) | 获取或设置一个 16 位有符号整数，用于指定对源对象应用的亮度量。 |
| [getColorfullness()](#getColorfullness--) | 获取或设置一个 16 位有符号整数，用于指定对源对象应用的色彩丰富度。 |
| [setColorfullness(short value)](#setColorfullness-short-) | 获取或设置一个 16 位有符号整数，用于指定对源对象应用的色彩丰富度。 |
| [getRedGreenTint()](#getRedGreenTint--) | 获取或设置一个 16 位有符号整数，用于指定对源对象应用的红色或绿色色调调整量。 |
| [setRedGreenTint(short value)](#setRedGreenTint-short-) | 获取或设置一个 16 位有符号整数，用于指定对源对象应用的红色或绿色色调调整量。 |
### EmfColorAdjustment() {#EmfColorAdjustment--}
```
public EmfColorAdjustment()
```


### getSize() {#getSize--}
```
public short getSize()
```


获取或设置一个 16 位无符号整数，用于指定此对象的字节大小。此值必须为 0x0018。

**Returns:**
短
### setSize(short value) {#setSize-short-}
```
public void setSize(short value)
```


获取或设置一个 16 位无符号整数，用于指定此对象的字节大小。此值必须为 0x0018。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getValues() {#getValues--}
```
public int getValues()
```


获取或设置一个 16 位无符号整数，用于指定如何准备输出图像。此字段可以设置为 NULL 或 ColorAdjustment 枚举中的任意组合值（第 2.1.5 节）。

**Returns:**
int
### setValues(int value) {#setValues-int-}
```
public void setValues(int value)
```


获取或设置一个 16 位无符号整数，用于指定如何准备输出图像。此字段可以设置为 NULL 或 ColorAdjustment 枚举中的任意组合值（第 2.1.5 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getIlluminantIndex() {#getIlluminantIndex--}
```
public int getIlluminantIndex()
```


获取或设置一个 16 位无符号整数，用于指定图像观看时所使用的标准光源类型，取自 Illuminant 枚举（第 2.1.19 节）。

**Returns:**
int
### setIlluminantIndex(int value) {#setIlluminantIndex-int-}
```
public void setIlluminantIndex(int value)
```


获取或设置一个 16 位无符号整数，用于指定图像观看时所使用的标准光源类型，取自 Illuminant 枚举（第 2.1.19 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRedGamma() {#getRedGamma--}
```
public short getRedGamma()
```


获取或设置一个 16 位无符号整数，用于指定源颜色中红色基色的 n 次幂伽马校正值。此值应在 2,500 到 65,000 的范围内。值为 10,000 表示不得执行伽马校正。

**Returns:**
短
### setRedGamma(short value) {#setRedGamma-short-}
```
public void setRedGamma(short value)
```


获取或设置一个 16 位无符号整数，用于指定源颜色中红色基色的 n 次幂伽马校正值。此值应在 2,500 到 65,000 的范围内。值为 10,000 表示不得执行伽马校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getGreenGamma() {#getGreenGamma--}
```
public short getGreenGamma()
```


获取或设置一个 16 位无符号整数，用于指定源颜色中绿色基色的 n 次幂伽马校正值。此值应在 2,500 到 65,000 的范围内。值为 10,000 表示不得执行伽马校正。

**Returns:**
短
### setGreenGamma(short value) {#setGreenGamma-short-}
```
public void setGreenGamma(short value)
```


获取或设置一个 16 位无符号整数，用于指定源颜色中绿色基色的 n 次幂伽马校正值。此值应在 2,500 到 65,000 的范围内。值为 10,000 表示不得执行伽马校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getBlueGamma() {#getBlueGamma--}
```
public short getBlueGamma()
```


获取或设置一个 16 位无符号整数，用于指定源颜色中蓝色基色的 n 次幂伽马校正值。此值应在 2,500 到 65,000 的范围内。值为 10,000 表示不得执行伽马校正。

**Returns:**
短
### setBlueGamma(short value) {#setBlueGamma-short-}
```
public void setBlueGamma(short value)
```


获取或设置一个 16 位无符号整数，用于指定源颜色中蓝色基色的 n 次幂伽马校正值。此值应在 2,500 到 65,000 的范围内。值为 10,000 表示不得执行伽马校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getReferenceBlack() {#getReferenceBlack--}
```
public short getReferenceBlack()
```


获取或设置一个 16 位无符号整数，用于指定源颜色的黑色参考值。任何比此更暗的颜色将被视为黑色。此值应在 0 到 4,000 的范围内。

**Returns:**
短
### setReferenceBlack(short value) {#setReferenceBlack-short-}
```
public void setReferenceBlack(short value)
```


获取或设置一个 16 位无符号整数，用于指定源颜色的黑色参考值。任何比此更暗的颜色将被视为黑色。此值应在 0 到 4,000 的范围内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getReferenceWhite() {#getReferenceWhite--}
```
public short getReferenceWhite()
```


获取或设置一个 16 位无符号整数，用于指定源颜色的白色参考值。任何比此更亮的颜色将被视为白色。此值应在 6,000 到 10,000 的范围内。

**Returns:**
短
### setReferenceWhite(short value) {#setReferenceWhite-short-}
```
public void setReferenceWhite(short value)
```


获取或设置一个 16 位无符号整数，用于指定源颜色的白色参考值。任何比此更亮的颜色将被视为白色。此值应在 6,000 到 10,000 的范围内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getContrast() {#getContrast--}
```
public short getContrast()
```


获取或设置一个 16 位有符号整数，用于指定对源对象应用的对比度量。此值应在 \u2013100 到 100 的范围内。值为零表示不得进行对比度调整。

**Returns:**
短
### setContrast(short value) {#setContrast-short-}
```
public void setContrast(short value)
```


获取或设置一个 16 位有符号整数，用于指定对源对象应用的对比度量。此值应在 \u2013100 到 100 的范围内。值为零表示不得进行对比度调整。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getBrightness() {#getBrightness--}
```
public short getBrightness()
```


获取或设置一个 16 位有符号整数，用于指定对源对象应用的亮度量。此值应在 \u2013100 到 100 的范围内。值为零表示不得进行亮度调整。

**Returns:**
短
### setBrightness(short value) {#setBrightness-short-}
```
public void setBrightness(short value)
```


获取或设置一个 16 位有符号整数，用于指定对源对象应用的亮度量。此值应在 \u2013100 到 100 的范围内。值为零表示不得进行亮度调整。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getColorfullness() {#getColorfullness--}
```
public short getColorfullness()
```


获取或设置一个 16 位有符号整数，用于指定对源对象应用的色彩丰富度。此值应在 \u2013100 到 100 的范围内。值为零表示不得进行色彩丰富度调整。

**Returns:**
短
### setColorfullness(short value) {#setColorfullness-short-}
```
public void setColorfullness(short value)
```


获取或设置一个 16 位有符号整数，用于指定对源对象应用的色彩丰富度。此值应在 \u2013100 到 100 的范围内。值为零表示不得进行色彩丰富度调整。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getRedGreenTint() {#getRedGreenTint--}
```
public short getRedGreenTint()
```


获取或设置一个 16 位有符号整数，用于指定对源对象应用的红色或绿色色调调整量。此值应在 \u2013100 到 100 的范围内。正数向红色调整，负数向绿色调整。值为零表示不得进行色调调整。

**Returns:**
短
### setRedGreenTint(short value) {#setRedGreenTint-short-}
```
public void setRedGreenTint(short value)
```


获取或设置一个 16 位有符号整数，用于指定对源对象应用的红色或绿色色调调整量。此值应在 \u2013100 到 100 的范围内。正数向红色调整，负数向绿色调整。值为零表示不得进行色调调整。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

