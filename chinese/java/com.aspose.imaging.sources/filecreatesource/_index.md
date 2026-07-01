---
title: "FileCreateSource"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示用于创建的文件源。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

表示用于创建的文件源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | 初始化 `FileCreateSource` 类的新实例。 |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | 初始化 `FileCreateSource` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFilePath()](#getFilePath--) | 获取要创建的文件路径。 |
| [isTemporal()](#isTemporal--) | 获取指示文件是否为临时文件的值。 |
| [getStreamContainer()](#getStreamContainer--) | 获取流容器。 |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
此示例演示了使用 Font 和 SolidBrush 类在 Image 表面绘制字符串。示例创建了一个新的 Image 并使用 Figures 和 GraphicsPath 绘制形状。
``` java
//创建一个 BmpOptions 实例并设置其各种属性
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
//第二个 Boolean 参数决定要创建的文件是否为 IsTemporal。
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//创建 Image 的实例
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //创建并初始化 Graphics 类的实例
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //清除 Graphics 表面
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //创建 Font 的实例
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //创建具有红色的 SolidBrush 实例
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //绘制字符串
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // 保存所有更改
    image.save();
} finally {
    image.dispose();
}
```

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


初始化 `FileCreateSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 要创建的文件路径。 |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


初始化 `FileCreateSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 要创建的文件路径。 |
| isTemporal | boolean | 如果设置为 `true`，创建的文件将为临时文件。 |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


获取要创建的文件路径。

值：要创建的文件路径。

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


获取指示文件是否为临时文件的值。

值：如果文件为临时文件则为 `true`；否则为 `false`。

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


获取流容器。

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

请谨慎使用。检索后您需要释放流容器。
