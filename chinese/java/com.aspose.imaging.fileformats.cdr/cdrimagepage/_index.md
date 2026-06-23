---
title: "CdrImagePage"
second_title: "Aspose.Imaging for Java API 参考"
description: "Cdr 图像页面。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

Cdr 图像页面。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParentImage()](#getParentImage--) | 获取父图像。 |
| [getPageNumber()](#getPageNumber--) | 获取页码。 |
| [isCached()](#isCached--) | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数计数。 |
| [getFileFormat()](#getFileFormat--) | 获取文件格式的值 |
| [getCdrDocument()](#getCdrDocument--) | 获取 CDR 文档。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 获取默认选项。 |
| [cacheData()](#cacheData--) | 缓存数据，并确保不会从底层 `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` 再次加载额外数据。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | 设置图像调色板。 |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


获取父图像。

值：父图像。

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


获取页码。

值：页码。

**Returns:**
int - 页码。
### isCached() {#isCached--}
```
public boolean isCached()
```


获取一个值，指示对象的数据当前是否已缓存且无需读取数据。

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数计数。

**Returns:**
int - 图像每像素位数。
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


获取文件格式的值

**Returns:**
long - 文件格式的值
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


获取 CDR 文档。

值：CDR 文档。

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


获取默认选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | java.lang.Object[] | 参数。 |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public synchronized void cacheData()
```


缓存数据，并确保不会从底层 `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` 再次加载额外数据。

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


设置图像调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

