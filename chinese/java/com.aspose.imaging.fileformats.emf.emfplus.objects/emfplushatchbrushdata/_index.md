---
title: "EmfPlusHatchBrushData"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusHatchBrushData 对象指定图形画刷的交叉图案。"
type: docs
weight: 45
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

EmfPlusHatchBrushData 对象指定图形画刷的交叉图案。

Graphics 画刷由 `EmfPlusBrush` 对象（第 2.2.1.1 节）指定。交叉线画刷在背景上绘制背景并绘制线条、点、短划线、方块和交叉线图案。该画刷定义了两种颜色：一种用于背景，另一种用于背景上的图案。背景的颜色称为背景色，图案的颜色称为前景色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | 获取或设置一个 32 位 EmfPlusArgb 对象，用于指定用于绘制交叉线图案背景的颜色。 |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | 获取或设置一个 32 位 EmfPlusArgb 对象，用于指定用于绘制交叉线图案背景的颜色。 |
| [getForeArgb32Color()](#getForeArgb32Color--) | 获取或设置一个 32 位 EmfPlusArgb 对象，用于指定用于绘制交叉线图案线条的颜色。 |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | 获取或设置一个 32 位 EmfPlusArgb 对象，用于指定用于绘制交叉线图案线条的颜色。 |
| [getHatchStyle()](#getHatchStyle--) | 获取或设置一个 32 位无符号整数，用于指定画刷的交叉线样式。 |
| [setHatchStyle(int value)](#setHatchStyle-int-) | 获取或设置一个 32 位无符号整数，用于指定画刷的交叉线样式。 |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


获取或设置一个 32 位 EmfPlusArgb 对象，用于指定用于绘制交叉线图案背景的颜色。

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


获取或设置一个 32 位 EmfPlusArgb 对象，用于指定用于绘制交叉线图案背景的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


获取或设置一个 32 位 EmfPlusArgb 对象，用于指定用于绘制交叉线图案线条的颜色。

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


获取或设置一个 32 位 EmfPlusArgb 对象，用于指定用于绘制交叉线图案线条的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


获取或设置一个 32 位无符号整数，用于指定画刷的交叉线样式。它必须在 `EmfPlusHatchStyle` 枚举中定义。

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


获取或设置一个 32 位无符号整数，用于指定画刷的交叉线样式。它必须在 `EmfPlusHatchStyle` 枚举中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

