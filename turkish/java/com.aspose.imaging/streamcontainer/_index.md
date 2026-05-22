---
title: "StreamContainer"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Akışı içeren ve akış işleme rutinleri sağlayan akış konteynerini temsil eder."
type: docs
weight: 109
url: /tr/java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Akışı içeren ve akış işleme rutinleri sağlayan akış konteynerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | Yeni bir `StreamContainer` sınıfı örneği başlatır. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | Yeni bir `StreamContainer` sınıfı örneği başlatır. |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | Yeni bir `StreamContainer` sınıfı örneği başlatır. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | Yeni bir `StreamContainer` sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Sıralı okuma sırasında okuma ve yazma bayt sayısını belirtir. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | `com.aspose.imaging.StreamContainer`'dan `System.IO.Stream`'e açık bir dönüşüm gerçekleştirir. |
| [getSyncRoot()](#getSyncRoot--) | Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [getPosition()](#getPosition--) | Akış içindeki geçerli konumu alır veya ayarlar. |
| [setPosition(long value)](#setPosition-long-) | Akış içindeki geçerli konumu alır veya ayarlar. |
| [getStream()](#getStream--) | Veri akışını alır. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren bir değer alır. |
| [getLength()](#getLength--) | Akış uzunluğunu bayt cinsinden alır veya ayarlar. |
| [setLength(long value)](#setLength-long-) | Akış uzunluğunu bayt cinsinden alır veya ayarlar. |
| [canRead()](#canRead--) | Akışın okuma desteği olup olmadığını gösteren bir değeri alır. |
| [canSeek()](#canSeek--) | Akışın konumlandırma desteği olup olmadığını gösteren bir değeri alır. |
| [canWrite()](#canWrite--) | Akışın yazma desteği olup olmadığını gösteren bir değeri alır. |
| [flush()](#flush--) | Bu akış için tüm tamponları temizler ve tamponlanmış verilerin temel cihaza yazılmasını sağlar. |
| [write(byte[] bytes)](#write-byte---) | Belirtilen tüm baytları akışa yazar. |
| [writeByte(byte value)](#writeByte-byte-) | Akıştaki geçerli konuma bir bayt yazar ve konumu bir bayt ilerletir. |
| [read(byte[] bytes)](#read-byte---) | Belirtilen bayt tamponunu doldurmak için baytları okur. |
| [toBytes()](#toBytes--) | Akış verilerini `byte` dizisine dönüştürür. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Akış verilerini `byte` dizisine dönüştürür. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Geçerli akıştan bir dizi bayt okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| [readByte()](#readByte--) | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir, ya da akışın sonunda ise -1 döndürür. |
| [seek(long offset, int origin)](#seek-long-int-) | Geçerli akış içindeki konumu ayarlar. |
| [seekBegin()](#seekBegin--) | Akış konumunu akışın başına ayarlar. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Geçerli akışa bir dizi bayt yazar ve bu akış içindeki geçerli konumu yazılan bayt sayısı kadar ilerletir. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(String filePath)](#save-java.lang.String-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | İçerilen verileri başka bir `StreamContainer`'a kopyalar. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | İçerilen verileri başka bir `StreamContainer`'a kopyalar. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


Yeni bir `StreamContainer` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


Yeni bir `StreamContainer` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | com.aspose.ms.System.IO.Stream | Akış. |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


Yeni bir `StreamContainer` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Veri akışı. |
| disposeStream | boolean | `true` olarak ayarlanırsa, kapsayıcı atıldığında akış da serbest bırakılır. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


Yeni bir `StreamContainer` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | com.aspose.ms.System.IO.Stream | Veri akışı. |
| disposeStream | boolean | `true` olarak ayarlanırsa, kapsayıcı atıldığında akış da serbest bırakılır. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Sıralı okuma sırasında okuma ve yazma bayt sayısını belirtir.

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


`com.aspose.imaging.StreamContainer`'dan `System.IO.Stream`'e açık bir dönüşüm gerçekleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |

**Returns:**
com.aspose.ms.System.IO.Stream - Dönüşümün sonucu.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

Değer: Eşzamanlı kaynağa erişimi senkronize etmek için kullanılabilecek nesne.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcı içinde verilen başlangıç akış konumundan ofseti temsil eder.

Değer: Geçerli akış konumu.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcı içinde verilen başlangıç akış konumundan ofseti temsil eder.

Değer: Geçerli akış konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


Veri akışını alır.

Değer: Veri akışı.

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren bir değer alır.

Değer: Akış kapatıldığında serbest bırakılıyorsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer, Stream\#getLength().getLength() değerinden, StreamContainer yapıcı içinde verilen başlangıç akış konumu kadar küçüktür.

Değer: Akış uzunluğu.

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer, Stream\#getLength().getLength() değerinden, StreamContainer yapıcı içinde verilen başlangıç akış konumu kadar küçüktür.

Değer: Akış uzunluğu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


Akışın okuma desteği olup olmadığını gösteren bir değeri alır.

Değer: Akış okuma destekliyorsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Akışın konumlandırma desteği olup olmadığını gösteren bir değeri alır.

Değer: Akış konumlandırma destekliyorsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Akışın yazma desteği olup olmadığını gösteren bir değeri alır.

Değer: `true` akış yazmayı destekliyorsa; aksi takdirde `false`.

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Bu akış için tüm tamponları temizler ve tamponlanmış verilerin temel cihaza yazılmasını sağlar.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Belirtilen tüm baytları akışa yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | byte[] | Yazılacak baytlar. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Akıştaki geçerli konuma bir bayt yazar ve konumu bir bayt ilerletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | Akışa yazılacak bayt. |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Belirtilen bayt tamponunu doldurmak için baytları okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | byte[] | Doldurulacak baytlar. |

**Returns:**
int - Okunan bayt sayısı. Bu değer, akışta yeterli bayt yoksa tampondaki bayt sayısından daha az olabilir.
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Akış verilerini `byte` dizisine dönüştürür.

**Returns:**
byte[] - Akış verisinin `byte` dizisine dönüştürülmüş hali.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Akış verilerini `byte` dizisine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Baytların okunmaya başlanacağı konum. |
| bytesCount | long | Okunacak bayt sayısı. |

**Returns:**
byte[] - Akış verisinin `byte` dizisine dönüştürülmüş hali.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Geçerli akıştan bir dizi bayt okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | byte[] | Bayt dizisi. Bu yöntem döndüğünde, tampon belirtilen bayt dizisini içerir ve `offset` ile (`offset` + `count` - 1) arasındaki değerler mevcut kaynaktan okunan baytlarla değiştirilir. |
| offset | int | `buffer` içinde, mevcut akıştan okunan verilerin depolanmaya başlanacağı sıfır tabanlı bayt ofseti. |
| count | int | Mevcut akıştan okunacak azami bayt sayısı. |

**Returns:**
int - Tampona okunan toplam bayt sayısı. Bu değer, istenen bayt sayısı mevcut değilse daha az olabilir veya akışın sonuna gelinmişse sıfır (0) olabilir.
### readByte() {#readByte--}
```
public int readByte()
```


Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir, ya da akışın sonunda ise -1 döndürür.

**Returns:**
int - Unsigned baytın Int32'ye dönüştürülmüş hali veya akışın sonunda ise -1.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Geçerli akış içindeki konumu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| offset | long | `origin` parametresine göre bir bayt ofseti. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| origin | int | `System.IO.SeekOrigin` türünde bir değer ve yeni konumu elde etmek için kullanılan referans noktasını gösterir. |

**Returns:**
long - Mevcut akış içindeki yeni konum.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Akış konumunu akışın başına ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder.

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Geçerli akışa bir dizi bayt yazar ve bu akış içindeki geçerli konumu yazılan bayt sayısı kadar ilerletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | byte[] | Bayt dizisi. Bu yöntem `buffer`'dan mevcut akışa `count` bayt kopyalar. |
| offset | int | `buffer` içinde, mevcut akışa bayt kopyalamaya başlanacak sıfır tabanlı bayt ofseti. |
| count | int | Mevcut akışa yazılacak bayt sayısı. |

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu `ReadWriteBytesCount` ve akış `Length` değeri kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Verilerin kaydedileceği akış. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Tüm akış verilerini belirtilen akışa kaydeder (kopyalar). Akış `Length` değeri kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Verilerin kaydedileceği akış. |
| bufferSize | int | Tampon. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Verilerin kaydedileceği akış. |
| bufferSize | int | Tampon boyutu. Varsayılan olarak `ReadWriteBytesCount` değeri kullanılır. |
| length | long | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk `Length` değerine ayarlanır. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu `ReadWriteBytesCount` ve akış `Length` değeri kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Akış verilerinin kaydedileceği dosya yolu. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akış `Length` değeri kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Akış verilerinin kaydedileceği dosya yolu. |
| bufferSize | int | Tampon boyutu. Varsayılan olarak `ReadWriteBytesCount` değeri kullanılır. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Akış verilerinin kaydedileceği dosya yolu. |
| bufferSize | int | Tampon boyutu. Varsayılan olarak `ReadWriteBytesCount` değeri kullanılır. |
| length | long | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk `Length` değerine ayarlanır. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


İçerilen verileri başka bir `StreamContainer`'a kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Kopyalanacak akış konteyneri. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


İçerilen verileri başka bir `StreamContainer`'a kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Kopyalanacak akış konteyneri. |
| length | long | Yazılacak bayt sayısı. |

