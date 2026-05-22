---
title: "TiffStreamWriter"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Tiff akış yazıcısı."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter extends TiffStreamSeeker implements ISynchronizable
```

Tiff akış yazıcısı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.imaging.StreamContainer-) | Yeni bir `TiffStreamWriter` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [getPosition()](#getPosition--) | Akış konumunu alır veya ayarlar. |
| [setPosition(long value)](#setPosition-long-) | Akış konumunu alır veya ayarlar. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Belirtilen veriyi yazar. |
| [write(byte[] data)](#write-byte---) | Belirtilen veriyi yazar. |
| [writeDouble(double data)](#writeDouble-double-) | Akışa tek bir double değer yazar. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Akışa bir dizi double değer yazar. |
| [writeFloat(float data)](#writeFloat-float-) | Akışa tek bir float değer yazar. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Akışa bir dizi float değer yazar. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-) | Akıma tek bir rasyonel sayı değeri yazar. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Akıma tek bir işaretli rasyonel sayı değeri yazar. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---) | Akıma işaretsiz rasyonel değerlerden oluşan bir dizi yazar. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Akıma işaretli rasyonel değerlerden oluşan bir dizi yazar. |
| [writeSByte(byte data)](#writeSByte-byte-) | Akıma tek bir işaretli bayt değeri yazar. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Akıma işaretli bayt değerlerinden oluşan bir dizi yazar. |
| [writeIntArray(int[] data)](#writeIntArray-int---) | Akıma tam sayı değerlerinden oluşan bir dizi yazar. |
| [writeSShort(short data)](#writeSShort-short-) | Akıma tek bir kısa değer yazar. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Akıma kısa değerlerden oluşan bir dizi yazar. |
| [writeSInt(int data)](#writeSInt-int-) | Akıma tek bir tam sayı değeri yazar. |
| [writeUByte(byte data)](#writeUByte-byte-) | Akıma tek bir bayt değeri yazar. |
| [writeUInt(long data)](#writeUInt-long-) | Akıma tek bir işaretsiz tam sayı değeri yazar. |
| [writeUIntArray(long[] data)](#writeUIntArray-long---) | Akıma işaretsiz tam sayı değerlerinden oluşan bir dizi yazar. |
| [writeUShort(int data)](#writeUShort-int-) | Akıma tek bir işaretsiz kısa değer yazar. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Akıma işaretsiz kısa değerlerden oluşan bir dizi yazar. |
| [writeSLong(long data)](#writeSLong-long-) | Akıma işaretli uzun değerlerden oluşan bir dizi yazar. |
| [writeSLongArray(long[] data)](#writeSLongArray-long---) | Akıma işaretli uzun değerlerden oluşan bir dizi yazar. |
| [writeULong(long data)](#writeULong-long-) | Akıma işaretsiz uzun değerlerden oluşan bir dizi yazar. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Akıma işaretsiz uzun değerlerden oluşan bir dizi yazar. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.imaging.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Yeni bir `TiffStreamWriter` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış yazıcı. |

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


Akış konumunu alır veya ayarlar.

Değer: Akım konumu.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Akış konumunu alır veya ayarlar.

Değer: Akım konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Belirtilen veriyi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Yazılacak veri. |
| offset | int | Veri ofseti. |
| dataLength | int | Yazılacak verinin uzunluğu. |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Belirtilen veriyi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Yazılacak veri. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Akışa tek bir double değer yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | double | Yazılacak değer. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Akışa bir dizi double değer yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | double[] | Yazılacak dizi. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Akışa tek bir float değer yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | float | Yazılacak değer. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Akışa bir dizi float değer yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | float[] | Yazılacak dizi. |

### writeRational(TiffRational data) {#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Akıma tek bir rasyonel sayı değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Yazılacak değer. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Akıma tek bir işaretli rasyonel sayı değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Yazılacak değer. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Akıma işaretsiz rasyonel değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Yazılacak dizi. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Akıma işaretli rasyonel değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Yazılacak dizi. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Akıma tek bir işaretli bayt değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte | Yazılacak değer. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Akıma işaretli bayt değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Yazılacak dizi. |

### writeIntArray(int[] data) {#writeIntArray-int---}
```
public void writeIntArray(int[] data)
```


Akıma tam sayı değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | int[] | Yazılacak dizi. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Akıma tek bir kısa değer yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | short | Yazılacak değer. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Akıma kısa değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | short[] | Yazılacak dizi. |

### writeSInt(int data) {#writeSInt-int-}
```
public void writeSInt(int data)
```


Akıma tek bir tam sayı değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | int | Yazılacak değer. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Akıma tek bir bayt değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte | Yazılacak değer. |

### writeUInt(long data) {#writeUInt-long-}
```
public void writeUInt(long data)
```


Akıma tek bir işaretsiz tam sayı değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | long | Yazılacak değer. |

### writeUIntArray(long[] data) {#writeUIntArray-long---}
```
public void writeUIntArray(long[] data)
```


Akıma işaretsiz tam sayı değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | long[] | Yazılacak dizi. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Akıma tek bir işaretsiz kısa değer yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | int | Yazılacak değer. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Akıma işaretsiz kısa değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | int[] | Yazılacak dizi. |

### writeSLong(long data) {#writeSLong-long-}
```
public final void writeSLong(long data)
```


Akıma işaretli uzun değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | long | Yazılacak dizi. |

### writeSLongArray(long[] data) {#writeSLongArray-long---}
```
public final void writeSLongArray(long[] data)
```


Akıma işaretli uzun değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | long[] | Yazılacak dizi. |

### writeULong(long data) {#writeULong-long-}
```
public final void writeULong(long data)
```


Akıma işaretsiz uzun değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | long | Yazılacak dizi. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public final void writeULongArray(long[] data)
```


Akıma işaretsiz uzun değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | long[] | Yazılacak dizi. |

