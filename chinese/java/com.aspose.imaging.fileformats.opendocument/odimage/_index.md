---
title: "OdImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "打开文档"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

打开文档
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | 检索与图像关联的默认页面，提供对图像集合中主页面的关键访问。 |
| [isCached()](#isCached--) | 获取一个布尔值，指示对象的数据当前是否已缓存，从而消除读取数据的需求。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 检索图像的每像素位数。 |
| [getPageCount()](#getPageCount--) | 检索图像中的页面总数。 |
| [getOdMetadata()](#getOdMetadata--) | 检索特定于 OpenDocument 文件的元数据。 |
| [getRecords()](#getRecords--) | 检索存储在图像中的 OpenDocument 记录。 |
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


检索与图像关联的默认页面，提供对图像集合中主页面的必要访问。此属性简化了图像数据的导航和操作，提升软件开发工作流的效率。

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


获取一个布尔值，指示对象的数据是否已被缓存，从而消除读取数据的需求。此属性作为优化指示器，通过最小化冗余的数据访问操作来提升性能。

**Returns:**
boolean - 一个值，指示对象的数据当前是否已缓存且无需读取数据。
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


检索图像的每像素位数。此属性提供对图像细节层次和颜色深度的了解，有助于各种图像处理任务和优化。

**Returns:**
int - 图像每像素位数。
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


检索图像中的页面总数。此属性对管理多页图像的应用程序至关重要，使其能够准确确定可用于处理或显示的页面数量。

**Returns:**
int - 页数。
### getOdMetadata() {#getOdMetadata--}
```
public final OdMetadata getOdMetadata()
```


检索特定于 OpenDocument 文件的元数据。此属性允许访问嵌入在 OD 文件中的关键信息，促进诸如提取、修改或分析元数据等各种操作。

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


检索存储在图像中的 OpenDocument 记录。此属性授予对嵌入在 OpenDocument 文件中的特定结构化数据元素的访问，便于检索或操作相关信息以进行进一步处理或分析。

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - 记录。
