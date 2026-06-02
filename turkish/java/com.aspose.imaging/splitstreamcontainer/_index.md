---
title: "SplitStreamContainer"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Akışı içeren ve akış işleme rutinleri sağlayan bölünmüş akış konteynerini temsil eder."
type: docs
weight: 108
url: /tr/java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Akışı içeren ve akış işleme rutinleri sağlayan bölünmüş akış konteynerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Yeni bir `SplitStreamContainer` sınıfı örneği başlatır. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Yeni bir `SplitStreamContainer` sınıfı örneği başlatır. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | Yeni bir `SplitStreamContainer` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [getPosition()](#getPosition--) | Akış içindeki geçerli konumu alır. |
| [setPosition(long value)](#setPosition-long-) | Akış içindeki geçerli konumu ayarlar. |
| [getLength()](#getLength--) | Akış uzunluğunu bayt cinsinden alır. |
| [setLength(long value)](#setLength-long-) | Akış uzunluğunu bayt cinsinden ayarlar. |
| [canRead()](#canRead--) | Akışın okuma desteği olup olmadığını gösteren bir değeri alır. |
| [canSeek()](#canSeek--) | Akışın konumlandırma desteği olup olmadığını gösteren bir değeri alır. |
| [canWrite()](#canWrite--) | Akışın yazma desteği olup olmadığını gösteren bir değeri alır. |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | Akış konteynerini belirtilen konuma ekler. |
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
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Yeni bir `SplitStreamContainer` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Yeni bir `SplitStreamContainer` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Veri akışı. |
| disposeStream | boolean | `true` olarak ayarlanırsa, kapsayıcı atıldığında akış da serbest bırakılır. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Yeni bir `SplitStreamContainer` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |
| disposeStream | boolean | `true` olarak ayarlanırsa akışı serbest bırakır. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

**Returns:**
java.lang.Object - Eşzamanlı kaynağa erişimi senkronize etmek için kullanılabilecek nesne.
### getPosition() {#getPosition--}
```
public long getPosition()
```


Akış içindeki geçerli konumu alır. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder.

**Returns:**
long - Geçerli akış konumu.
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Akış içindeki geçerli konumu ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Geçerli akış konumu. |

### getLength() {#getLength--}
```
public long getLength()
```


Akış uzunluğunu bayt cinsinden alır. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumu kadar `System.IO.Stream.Length` değerinden küçüktür.

**Returns:**
long - Akış uzunluğu.
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Akış uzunluğunu bayt cinsinden ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumu kadar `System.IO.Stream.Length` değerinden küçüktür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Akış uzunluğu. |

### canRead() {#canRead--}
```
public boolean canRead()
```


Akışın okuma desteği olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - Akış okuma destekliyorsa `true`; aksi takdirde `false`.
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Akışın konumlandırma desteği olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - Akış arama destekliyorsa `true`; aksi takdirde `false`.
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Akışın yazma desteği olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - Akış yazma destekliyorsa `true`; aksi takdirde `false`.
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


Akış konteynerini belirtilen konuma ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | int | Eklenecek konum. |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Eklenecek akış kapsayıcısı. |
| disposeStream | boolean | `true` olarak ayarlanırsa akışı serbest bırakır. |

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

