---
title: "StreamSource"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示流源。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

表示流源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource(byte[] data)](#StreamSource-byte---) | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource()](#StreamSource--) | 使用 Null 流初始化 `StreamSource` 类的新实例。 |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | 初始化 `StreamSource` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStream()](#getStream--) | 获取流。 |
| [getDisposeStream()](#getDisposeStream--) | 获取一个值，指示是否在容器被释放时应释放流。 |
| [getStreamContainer()](#getStreamContainer--) | 获取流容器。 |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//创建 JpegOptions 的实例并设置其各种属性
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//创建 System.IO.Stream 的实例
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// 为 JpegOptions 实例定义 source 属性
// 第二个布尔参数决定在超出作用域后是否释放 Stream
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// 创建 Image 的实例并调用 Create 方法，将 JpegOptions 作为参数以初始化 Image 对象
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // 进行一些图像处理。
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


初始化 `StreamSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.ms.System.IO.Stream | 要打开的流。 |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


初始化 `StreamSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 要打开的流。 |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


初始化 `StreamSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 存储图像的字节数组 |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


初始化 `StreamSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | 用于存储图像的 ByteBuffer 缓冲区 |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


使用 Null 流初始化 `StreamSource` 类的新实例。此构造函数允许在没有输入流的情况下创建新图像，图像仅存储在内存中。

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


初始化 `StreamSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件 | java.io.RandomAccessFile | 要打开的文件。 |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


初始化 `StreamSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件 | java.io.RandomAccessFile | 要打开的文件。 |
| disposeStream | boolean | 如果设置为 `true`，流将被释放。 |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


初始化 `StreamSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.ms.System.IO.Stream | 流 |
| disposeStream | boolean | 如果设置为 `true`，流将被释放。 |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


初始化 `StreamSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 要打开的流。 |
| disposeStream | boolean | 如果设置为 `true`，流将被释放。 |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


获取流。

**Returns:**
com.aspose.ms.System.IO.Stream - 流。
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


获取一个值，指示是否在容器被释放时应释放流。

**Returns:**
boolean - 如果应释放流则为 `true`；否则为 `false`。
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


获取流容器。

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

请谨慎使用。检索后需要释放流容器。
