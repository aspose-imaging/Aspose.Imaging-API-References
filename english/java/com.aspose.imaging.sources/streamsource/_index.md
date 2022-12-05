---
title: StreamSource
second_title: Aspose.Imaging for Java API Reference
description: Represents a stream source.
type: docs
weight: 13
url: /java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

Represents a stream source.
## Constructors

| Constructor | Description |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | Initializes a new instance of the `StreamSource` class. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Initializes a new instance of the `StreamSource` class. |
| [StreamSource(byte[] data)](#StreamSource-byte---) | Initializes a new instance of the `StreamSource` class. |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | Initializes a new instance of the `StreamSource` class. |
| [StreamSource()](#StreamSource--) | Initializes a new instance of the `StreamSource` class with Null stream. |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | Initializes a new instance of the `StreamSource` class. |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | Initializes a new instance of the `StreamSource` class. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | Initializes a new instance of the `StreamSource` class. |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Initializes a new instance of the `StreamSource` class. |
## Methods

| Method | Description |
| --- | --- |
| [getStream()](#getStream--) | Gets the stream. |
| [getDisposeStream()](#getDisposeStream--) | Gets a value indicating whether stream should be disposed whenever container gets disposed. |
| [getStreamContainer()](#getStreamContainer--) | Gets the stream container. |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//Creates an instance of JpegOptions and set its various properties
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//Create an instance of System.IO.Stream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// Define the source property for the instance of JpegOptions
// Second boolean parameter determines if the Stream is disposed once get out of scope
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// Creates an instance of Image and call Create method with JpegOptions as parameter to initialize the Image object
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // Do some image processing
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


Initializes a new instance of the `StreamSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to open. |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Initializes a new instance of the `StreamSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to open. |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


Initializes a new instance of the `StreamSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | byte array which is stored the image |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


Initializes a new instance of the `StreamSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | ByteBuffer buffer for storing the image |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Initializes a new instance of the `StreamSource` class with Null stream. This constructor allows to create new images without input stream, images stored only in memory.

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


Initializes a new instance of the `StreamSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.RandomAccessFile | The file to open. |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


Initializes a new instance of the `StreamSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.RandomAccessFile | The file to open. |
| disposeStream | boolean | if set to `true` the stream will be disposed. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


Initializes a new instance of the `StreamSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream |
| disposeStream | boolean | if set to `true` the stream will be disposed. |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Initializes a new instance of the `StreamSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to open. |
| disposeStream | boolean | if set to `true` the stream will be disposed. |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


Gets the stream.

**Returns:**
com.aspose.ms.System.IO.Stream - The stream.
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


Gets a value indicating whether stream should be disposed whenever container gets disposed.

**Returns:**
boolean - `true` if stream should be disposed; otherwise, `false`.
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Gets the stream container.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Use with caution. You will need to dispose the stream container after retrieval.
