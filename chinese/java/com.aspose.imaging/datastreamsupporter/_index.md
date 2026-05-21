---
title: "DataStreamSupporter"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "数据流容器。"
type: docs
weight: 39
url: /zh/java/com.aspose.imaging/datastreamsupporter/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

数据流容器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDataStreamContainer()](#getDataStreamContainer--) | 获取对象的数据流。 |
| [isCached()](#isCached--) | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [cacheData()](#cacheData--) | 缓存数据，并确保不会从底层 `DataStreamSupporter.DataStreamContainer` 再进行额外的数据加载。 |
| [save()](#save--) | 将对象的数据保存到当前的 `DataStreamSupporter`。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将对象的数据保存到指定的流。 |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | 将对象的数据保存到指定的流。 |
| [save(String filePath)](#save-java.lang.String-) | 将对象的数据保存到指定的文件位置。 |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | 将对象的数据保存到指定的文件位置。 |
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


获取对象的数据流。

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The object's data stream.
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


获取一个值，指示对象的数据当前是否已缓存且无需读取数据。

**Returns:**
boolean - 一个值，指示对象的数据当前是否已缓存且无需读取数据。
### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


缓存数据，并确保不会从底层 `DataStreamSupporter.DataStreamContainer` 再进行额外的数据加载。


**Example: The following example shows how image caching affects performance.**
以下示例展示了图像缓存如何影响性能。一般情况下，读取缓存数据的速度快于读取非缓存数据。
``` java
String dir = "c:\\temp\\";

// 从 PNG 文件加载图像。
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // 缓存所有像素数据，以便不再从底层数据流进行额外的数据加载
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // 读取所有像素相当快。
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = rasterImage.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedTime = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedTime + " ms.");
} finally {
    image.dispose();
}

// 从 PNG 文件加载图像
image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // 读取所有像素的速度不如缓存时快
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = rasterImage.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedTime = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedTime + " ms.");
} finally {
    image.dispose();
}

// 输出可能如下所示：
//读取所有缓存像素耗时 2954 毫秒。
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//位于 com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:58)
```

### save() {#save--}
```
public void save()
```


将对象的数据保存到当前的 `DataStreamSupporter`。

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


将对象的数据保存到指定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | 用于保存对象数据的流。 |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


将对象的数据保存到指定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件 | java.io.RandomAccessFile | 用于保存对象数据的流。 |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


将对象的数据保存到指定的文件位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于保存对象数据的文件路径。 |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


将对象的数据保存到指定的文件位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于保存对象数据的文件路径。 |
| overWrite | boolean | 如果设置为 `true` 则覆盖文件内容，否则将追加。 |

