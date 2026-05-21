---
title: "DataStreamSupporter"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Veri akışı konteyneri."
type: docs
weight: 39
url: /tr/java/com.aspose.imaging/datastreamsupporter/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Veri akışı konteyneri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDataStreamContainer()](#getDataStreamContainer--) | Nesnenin veri akışını alır. |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değeri alır. |
| [cacheData()](#cacheData--) | Verileri önbelleğe alır ve temel `DataStreamSupporter.DataStreamContainer`'dan ek veri yüklemesinin yapılmayacağını garanti eder. |
| [save()](#save--) | Nesnenin verisini mevcut `DataStreamSupporter`'a kaydeder. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(String filePath)](#save-java.lang.String-) | Nesnenin verisini belirtilen dosya konumuna kaydeder. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Nesnenin verisini belirtilen dosya konumuna kaydeder. |
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Nesnenin veri akışını alır.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The object's data stream.
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değeri alır.

**Returns:**
boolean - nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değer.
### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Verileri önbelleğe alır ve temel `DataStreamSupporter.DataStreamContainer`'dan ek veri yüklemesinin yapılmayacağını garanti eder.


**Example: The following example shows how image caching affects performance.**
Aşağıdaki örnek, görüntü önbelleğe almanın performansı nasıl etkilediğini gösterir. Genel durumda, önbelleğe alınmış veriyi okumak, önbelleğe alınmamış veriyi okumaktan daha hızlı gerçekleşir.
``` java
String dir = "c:\\temp\\";

// Bir PNG dosyasından görüntü yükle.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Tüm piksel verilerini önbelleğe al ki temel veri akışından ek veri yüklemesi yapılmasın
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Tüm pikselleri okumak oldukça hızlıdır.
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

// Bir PNG dosyasından bir görüntü yükle
image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Tüm pikselleri okumak, önbelleğe alındığında olduğu kadar hızlı değil
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

// Çıktı şöyle görünebilir:
//Tüm önbelleğe alınmış pikselleri okumak 2954 ms sürdü.
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


Nesnenin verisini mevcut `DataStreamSupporter`'a kaydeder.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Nesnenin verisinin kaydedileceği akış. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Nesnenin verisinin kaydedileceği akış. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Nesnenin verisini belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Nesnenin verisinin kaydedileceği dosya yolu. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Nesnenin verisini belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Nesnenin verisinin kaydedileceği dosya yolu. |
| overWrite | boolean | `true` olarak ayarlanırsa dosya içeriğini üzerine yazar, aksi takdirde ekleme gerçekleşir. |

