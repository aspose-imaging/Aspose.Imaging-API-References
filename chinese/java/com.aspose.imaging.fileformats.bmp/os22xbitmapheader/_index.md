---
title: "Os22XBitmapHeader"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "OS/2 2.x OS22XBITMAPHEADER，也称为 BITMAPCOREHEADER2。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

OS/2 2.x OS22XBITMAPHEADER，也称为 BITMAPCOREHEADER2。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getUnits()](#getUnits--) | 获取单位。 |
| [getReserved()](#getReserved--) | 获取保留。 |
| [getRecording()](#getRecording--) | 获取记录。 |
| [getRendering()](#getRendering--) | 获取渲染。 |
| [getSize1()](#getSize1--) | 获取 size1。 |
| [getSize2()](#getSize2--) | 获取 size2。 |
| [getColorEncoding()](#getColorEncoding--) | 获取颜色编码。 |
| [getIdentifier()](#getIdentifier--) | 获取标识符。 |
### getUnits() {#getUnits--}
```
public int getUnits()
```


获取单位。

**Returns:**
int - 用于测量分辨率的单位类型
### getReserved() {#getReserved--}
```
public int getReserved()
```


获取保留。

**Returns:**
int - 将结构填充至 4 字节边界
### getRecording() {#getRecording--}
```
public int getRecording()
```


获取记录。

**Returns:**
int - 记录算法
### getRendering() {#getRendering--}
```
public int getRendering()
```


获取渲染。

**Returns:**
int - 使用的半色调算法
### getSize1() {#getSize1--}
```
public int getSize1()
```


获取 size1。

**Returns:**
int - 为半色调算法保留
### getSize2() {#getSize2--}
```
public int getSize2()
```


获取 size2。

**Returns:**
int - 为半色调算法保留
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


获取颜色编码。

**Returns:**
int - 位图中使用的颜色模型
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


获取标识符。

**Returns:**
int - 为应用程序保留
