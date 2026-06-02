---
title: "DisposableObject"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示可释放的对象。"
type: docs
weight: 40
url: /zh/java/com.aspose.imaging/disposableobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class DisposableObject implements System.IDisposable, Closeable
```

表示可释放的对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DisposableObject()](#DisposableObject--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDisposed()](#getDisposed--) | 获取一个值，指示此实例是否已释放。 |
| [close()](#close--) | 实现 Closable 接口，并且自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [dispose()](#dispose--) | 释放当前实例。 |
### DisposableObject() {#DisposableObject--}
```
public DisposableObject()
```


### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


获取一个值，指示此实例是否已释放。

**Returns:**
boolean - 如果已释放则为 `true`；否则为 `false`。
### close() {#close--}
```
public void close()
```


实现 Closable 接口，并且自 JDK 1.7 起可在 try-with-resources 语句中使用。此方法仅调用 dispose 方法。

### dispose() {#dispose--}
```
public void dispose()
```


释放当前实例。


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // 这是用于在各帧上绘制文本的 Font 和 Brush。
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // 创建 5 帧
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // 创建 PNG 图像并在其上绘制页码。
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // 基于 PNG 图像创建帧。
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // 将帧添加到 TIFF 图像中。
        tiffImage.addFrame(frame);
    }

    // 该图像使用单个默认帧创建。让我们将其移除。
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // 如果不将帧添加到其他 TiffImage，请别忘记释放该帧。
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

