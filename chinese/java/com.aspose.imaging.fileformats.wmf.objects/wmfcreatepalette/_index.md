---
title: "WmfCreatePalette"
second_title: "Aspose.Imaging for Java API 参考"
description: "META_CREATEPALETTE 记录创建一个调色板对象（章节 2.2.1.3）。"
type: docs
weight: 22
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePalette extends WmfGraphicObject
```

META\_CREATEPALETTE 记录创建调色板对象（第 2.2.1.3 节）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfCreatePalette()](#WmfCreatePalette--) | WMFs 记录。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [PALETTE_START](#PALETTE-START) | 调色板起始标签 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLogPalette()](#getLogPalette--) | 获取逻辑调色板。 |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | 设置逻辑调色板。 |
### WmfCreatePalette() {#WmfCreatePalette--}
```
public WmfCreatePalette()
```


WMFs 记录。

### PALETTE_START {#PALETTE-START}
```
public static final int PALETTE_START
```


调色板起始标签

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


获取逻辑调色板。

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) - The logical palette.
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


设置逻辑调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) | 逻辑调色板。 |

