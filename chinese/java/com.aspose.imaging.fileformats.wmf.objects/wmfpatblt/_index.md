---
title: "WmfPatBlt"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 META_PATBLT 记录使用在回放设备上下文中定义的刷子绘制指定的矩形。"
type: docs
weight: 52
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfpatblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfPointObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfpointobject)
```
public class WmfPatBlt extends WmfPointObject
```

该 META\_PATBLT 记录使用在回放设备上下文中定义的刷子绘制指定的矩形。刷子的颜色与表面颜色或颜色通过指定的光栅操作进行合成。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfPatBlt()](#WmfPatBlt--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | 获取或设置光栅操作。 |
| [setRasterOperation(int value)](#setRasterOperation-int-) | 获取或设置光栅操作。 |
| [getHeight()](#getHeight--) | 获取或设置高度。 |
| [setHeight(short value)](#setHeight-short-) | 获取或设置高度。 |
| [getWidth()](#getWidth--) | 获取或设置宽度。 |
| [setWidth(short value)](#setWidth-short-) | 获取或设置宽度。 |
### WmfPatBlt() {#WmfPatBlt--}
```
public WmfPatBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


获取或设置光栅操作。

值：光栅操作代码。此代码必须是三元光栅操作枚举表中的一个值。

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


获取或设置光栅操作。

值：光栅操作代码。此代码必须是三元光栅操作枚举表中的一个值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


获取或设置高度。

值：矩形的高度（逻辑单位）。

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


获取或设置高度。

值：矩形的高度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


获取或设置宽度。

值：矩形的宽度（逻辑单位）。

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


获取或设置宽度。

值：矩形的宽度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

