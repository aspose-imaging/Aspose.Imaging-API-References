---
title: "StreamSource"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir akış kaynağını temsil eder."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

Bir akış kaynağını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | Yeni bir `StreamSource` sınıfı örneği başlatır. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Yeni bir `StreamSource` sınıfı örneği başlatır. |
| [StreamSource(byte[] data)](#StreamSource-byte---) | Yeni bir `StreamSource` sınıfı örneği başlatır. |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | Yeni bir `StreamSource` sınıfı örneği başlatır. |
| [StreamSource()](#StreamSource--) | Null akışıyla yeni bir `StreamSource` sınıfı örneği başlatır. |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | Yeni bir `StreamSource` sınıfı örneği başlatır. |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | Yeni bir `StreamSource` sınıfı örneği başlatır. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | Yeni bir `StreamSource` sınıfı örneği başlatır. |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Yeni bir `StreamSource` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStream()](#getStream--) | Akışı alır. |
| [getDisposeStream()](#getDisposeStream--) | Konteyner atıldığında akışın atılıp atılmayacağını gösteren bir değeri alır. |
| [getStreamContainer()](#getStreamContainer--) | Akış konteynerini alır. |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//JpegOptions bir örnek oluşturur ve çeşitli özelliklerini ayarlar
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//System.IO.Stream bir örnek oluştur
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// JpegOptions örneği için source özelliğini tanımla
// İkinci bool parametre, akışın kapsam dışına çıktığında atılıp atılmayacağını belirler
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// Image bir örnek oluşturur ve Image nesnesini başlatmak için JpegOptions parametresiyle Create metodunu çağırır
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // Biraz görüntü işleme yapın
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


Yeni bir `StreamSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | com.aspose.ms.System.IO.Stream | Açılacak akış. |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Yeni bir `StreamSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Açılacak akış. |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


Yeni bir `StreamSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Görüntünün depolandığı bayt dizisi |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


Yeni bir `StreamSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | Görüntüyü depolamak için ByteBuffer tamponu |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Null akışıyla yeni bir `StreamSource` sınıfı örneği başlatır. Bu yapıcı, giriş akışı olmadan yeni görüntüler oluşturmayı sağlar; görüntüler yalnızca bellekte depolanır.

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


Yeni bir `StreamSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Açılacak dosya. |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


Yeni bir `StreamSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Açılacak dosya. |
| disposeStream | boolean | `true` olarak ayarlanırsa akış atılacaktır. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


Yeni bir `StreamSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | com.aspose.ms.System.IO.Stream | Akış |
| disposeStream | boolean | `true` olarak ayarlanırsa akış atılacaktır. |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Yeni bir `StreamSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Açılacak akış. |
| disposeStream | boolean | `true` olarak ayarlanırsa akış atılacaktır. |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


Akışı alır.

**Returns:**
com.aspose.ms.System.IO.Stream - Akış.
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


Konteyner atıldığında akışın atılıp atılmayacağını gösteren bir değeri alır.

**Returns:**
boolean - akış atılacaksa `true`; aksi takdirde `false`.
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Akış konteynerini alır.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Dikkatli kullanın. Alımdan sonra akış konteynerini serbest bırakmanız gerekir.
