---
title: "SvgResourceKeeperCallback"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "资源保持器回调"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

资源保持器回调
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | 当图像资源准备好导出时调用。 |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | 当字体资源准备好导出时调用。 |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | 当 SVG 文档准备好导出时调用。 |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


当图像资源准备好导出时调用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageData | byte[] | 资源数据。 |
| imageType | int | 图像类型。 |
| suggestedFileName | java.lang.String | 建议文件的名称。 |
| useEmbeddedImage | boolean[] | 如果设置为 `true`，必须使用嵌入的图像。 |

**Returns:**
java.lang.String - 返回已保存资源的路径。路径应相对于目标 SVG 文档。
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


当字体资源准备好导出时调用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | com.aspose.svg.options.FontStoringArgs | 字体存储选项。 |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


当 SVG 文档准备好导出时调用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlData | byte[] | SVG 数据。 |
| suggestedFileName | java.lang.String | 建议文件的名称。 |

**Returns:**
java.lang.String - 返回已保存的 SVG 文档的路径。
