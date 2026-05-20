---
title: "PdfCoreOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "转换为 PDF 的常用选项"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.pdf/pdfcoreoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

转换为 PDF 的常用选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | 指定在文档大纲中包含多少级大纲项。 |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | 指定在文档大纲中包含多少级大纲项。 |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | 指定在查看 PDF 文件时文档大纲中展开显示的级别数。 |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | 指定在查看 PDF 文件时文档大纲中展开显示的级别数。 |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | 指定在文档大纲的哪个级别显示书签对象。 |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | 指定在文档大纲的哪个级别显示书签对象。 |
| [getJpegQuality()](#getJpegQuality--) | 指定图像的 JPEG 压缩质量（如果使用 JPEG 压缩）。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 指定图像的 JPEG 压缩质量（如果使用 JPEG 压缩）。 |
| [getPdfCompliance()](#getPdfCompliance--) | 获取 PDF 合规性。 |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | 设置 PDF 合规性。 |
| [getCompression()](#getCompression--) | 获取压缩方式。 |
| [setCompression(int value)](#setCompression-int-) | 设置压缩方式。 |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


指定在文档大纲中包含多少级大纲项。0 - 无大纲，1 - 一个大纲级别，依此类推。默认值为 0。

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


指定在文档大纲中包含多少级大纲项。0 - 无大纲，1 - 一个大纲级别，依此类推。默认值为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


指定在查看 PDF 文件时文档大纲中展开显示的级别数。0 - 文档大纲不展开。1 - 文档的第一层级项展开，依此类推。默认值为 0。

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


指定在查看 PDF 文件时文档大纲中展开显示的级别数。0 - 文档大纲不展开。1 - 文档的第一层级项展开，依此类推。默认值为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


指定在文档大纲的哪个级别显示书签对象。0 - 不显示。1 - 在第一层级显示，依此类推。默认值为 0。

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


指定在文档大纲的哪个级别显示书签对象。0 - 不显示。1 - 在第一层级显示，依此类推。默认值为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


指定图像的 JPEG 压缩质量（如果使用 JPEG 压缩）。默认值为 95。

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


指定图像的 JPEG 压缩质量（如果使用 JPEG 压缩）。默认值为 95。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


获取 PDF 合规性。

**Returns:**
int - PDF 合规性。
### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


设置 PDF 合规性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PDF 合规性。 |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


获取压缩方式。

值：压缩。

**Returns:**
int - 压缩。
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


设置压缩方式。

值：压缩。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 压缩。 |

