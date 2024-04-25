---
title: DataStreamSupporter
second_title: Aspose.Imaging for Java API Reference
description: The data stream container.
type: docs
weight: 39
url: /com.aspose.imaging/datastreamsupporter/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

The data stream container.
## Methods

| Method | Description |
| --- | --- |
| [getDataStreamContainer()](#getDataStreamContainer--) | Gets the object's data stream. |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [cacheData()](#cacheData--) | Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`. |
| [save()](#save--) | Saves the object's data to the current `DataStreamSupporter`. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the object's data to the specified stream. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Saves the object's data to the specified stream. |
| [save(String filePath)](#save-java.lang.String-) | Saves the object's data to the specified file location. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Saves the object's data to the specified file location. |
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Gets the object's data stream.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The object's data stream.
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Gets a value indicating whether object's data is cached currently and no data reading is required.

**Returns:**
boolean - a value indicating whether object's data is cached currently and no data reading is required.
### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`.


**Example: The following example shows how image caching affects performance.**
The following example shows how image caching affects performance. In general case, reading cached data is performed faster than reading non-cached data.
``` java
String dir = "c:\\temp\\";

// Load an image from a PNG file.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Cache all pixel data so that no additional data loading will be performed from the underlying data stream
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Reading all pixels is pretty fast.
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

// Load an image from a PNG file
image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Reading all pixels is not as fast as when caching
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

// The output may look like this:
//Reading all cached pixels took 2954 ms.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//at com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:58)
```

### save() {#save--}
```
public void save()
```


Saves the object's data to the current `DataStreamSupporter`.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves the object's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to save the object's data to. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Saves the object's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.RandomAccessFile | The stream to save the object's data to. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Saves the object's data to the specified file location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the object's data to. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Saves the object's data to the specified file location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the object's data to. |
| overWrite | boolean | if set to `true` overwrite the file contents, otherwise append will occur. |

