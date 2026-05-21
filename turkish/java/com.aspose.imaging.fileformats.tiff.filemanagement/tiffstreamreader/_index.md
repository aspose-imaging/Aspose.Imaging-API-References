---
title: "TiffStreamReader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Küçük endian tiff dosya formatını işlemek için tiff akışı."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

Küçük endian tiff dosya formatını işlemek için tiff akışı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Yeni bir `TiffStreamReader` sınıfı örneği başlatır. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Yeni bir `TiffStreamReader` sınıfı örneği başlatır. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Yeni bir `TiffStreamReader` sınıfı örneği başlatır. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | Yeni bir `TiffStreamReader` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLength()](#getLength--) | Okuyucu uzunluğunu alır. |
| [getThrowExceptions()](#getThrowExceptions--) | Yanlış veri işleme (akışa okuma veya yazma) sırasında istisnaların atılıp atılmayacağını belirten bir değeri alır veya ayarlar. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Yanlış veri işleme (akışa okuma veya yazma) sırasında istisnaların atılıp atılmayacağını belirten bir değeri alır veya ayarlar. |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Akıştan bayt değerleri dizisini okur. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Akıştan işaretsiz bayt değerleri dizisini okur. |
| [readDouble(long position)](#readDouble-long-) | Akıştan tek bir double değer okur. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Akıştan double değerleri dizisini okur. |
| [readFloat(long position)](#readFloat-long-) | Akıştan tek bir float değer okur. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Akıştan float değerleri dizisini okur. |
| [readRational(long position)](#readRational-long-) | Akıştan tek bir rasyonel sayı değeri okur. |
| [readSRational(long position)](#readSRational-long-) | Akıştan tek bir işaretli rasyonel sayı değeri okur. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Akıştan rasyonel değerler dizisini okur. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Akıştan işaretli rasyonel değerler dizisini okur. |
| [readSByte(long position)](#readSByte-long-) | Akıştan işaretli bayt verisini okur. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Akıştan işaretli bayt değerleri dizisini okur. |
| [readSInt(long position)](#readSInt-long-) | Akıştan işaretli tam sayı değerini okur. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | Akıştan işaretli tam sayı değerleri dizisini okur. |
| [readSShort(long position)](#readSShort-long-) | Akıştan işaretli short değer okur. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Akıştan işaretli short değerleri dizisini okur. |
| [readUInt(long position)](#readUInt-long-) | Akıştan işaretsiz tam sayı değerini okur. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | Akıştan işaretsiz tam sayı değerleri dizisini okur. |
| [readUShort(long position)](#readUShort-long-) | Akıştan işaretsiz short değer okur. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Akıştan işaretsiz tam sayı değerleri dizisini okur. |
| [readLong(long position)](#readLong-long-) | Akıştan işaretsiz long değer okur. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | Akıştan long değerleri dizisini okur. |
| [readULong(long position)](#readULong-long-) | Akıştan işaretsiz long değer okur. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Akıştan ulong değerleri dizisini okur. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Alttaki verileri akış konteynerine dönüştürür. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Yeni bir `TiffStreamReader` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Bayt dizisi verisi. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Yeni bir `TiffStreamReader` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Bayt dizisi verisi. |
| startIndex | int | `data` içindeki başlangıç indeksi. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Yeni bir `TiffStreamReader` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Bayt dizisi verisi. |
| startIndex | int | `data` içindeki başlangıç indeksi. |
| dataLength | int | Verinin uzunluğu. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Yeni bir `TiffStreamReader` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |

### getLength() {#getLength--}
```
public long getLength()
```


Okuyucu uzunluğunu alır.

Değer: Okuyucu uzunluğu.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Yanlış veri işleme (akışa okuma veya yazma) sırasında istisnaların atılıp atılmayacağını belirten bir değeri alır veya ayarlar.

Değer: Yanlış veri işleme sırasında istisnalar atılıyorsa `true`; aksi takdirde hata koşulları sessizce yok sayılır.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Yanlış veri işleme (akışa okuma veya yazma) sırasında istisnaların atılıp atılmayacağını belirten bir değeri alır veya ayarlar.

Değer: Yanlış veri işleme sırasında istisnalar atılıyorsa `true`; aksi takdirde hata koşulları sessizce yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Akıştan bayt değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizi | byte[] | Doldurulacak dizi. |
| arrayIndex | int | Değerlerin yerleştirilmeye başlanacağı dizi indeksi. |
| konum | long | Okunacak akış konumu. |
| count | long | Okunacak öğe sayısı. |

**Returns:**
long - Bayt değerlerinin dizisi.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Akıştan işaretsiz bayt değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
byte[] - İşaretsiz bayt değerlerinin dizisi.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Akıştan tek bir double değer okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
double - Tek çift hassasiyetli değer.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Akıştan double değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
double[] - Çift hassasiyetli değerlerin dizisi.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Akıştan tek bir float değer okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
float - Tek kayan nokta değeri.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Akıştan float değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
float[] - Kayan nokta değerlerinin dizisi.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Akıştan tek bir rasyonel sayı değeri okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Akıştan tek bir işaretli rasyonel sayı değeri okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Akıştan rasyonel değerler dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - Rasyonel değerlerin dizisi.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Akıştan işaretli rasyonel değerler dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - İşaretli rasyonel değerlerin dizisi.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Akıştan işaretli bayt verisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
byte - İşaretli bayt değeri.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Akıştan işaretli bayt değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
byte[] - İşaretli bayt değerlerinin dizisi.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


Akıştan işaretli tam sayı değerini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
int - İşaretli tam sayı değeri.
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


Akıştan işaretli tam sayı değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
int[] - İşaretli tam sayı değerlerinin dizisi.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Akıştan işaretli short değer okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
short - İşaretli kısa değer.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Akıştan işaretli short değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
short[] - İşaretli kısa değerlerin dizisi.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


Akıştan işaretsiz tam sayı değerini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
long - İşaretsiz tam sayı değeri.
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


Akıştan işaretsiz tam sayı değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
long[] - İşaretsiz tam sayı değerlerinin dizisi.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Akıştan işaretsiz short değer okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
int - İşaretsiz kısa bir değer.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Akıştan işaretsiz tam sayı değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
int[] - İşaretsiz tamsayı değerlerinin dizisi.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


Akıştan işaretsiz long değer okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
long - İşaretsiz kısa bir değer.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


Akıştan long değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
long[] - ulong dizisi.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


Akıştan işaretsiz long değer okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |

**Returns:**
long - İşaretsiz kısa bir değer.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


Akıştan ulong değerleri dizisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
long[] - ulong dizisi.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Alttaki verileri akış konteynerine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startPosition | long | Dönüştürmeye başlanacak başlangıç konumu. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
