---
title: "TiffDataType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "TIFF veri tipi."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

TIFF veri tipi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getElementSize()](#getElementSize--) | Elemanın bayt cinsinden boyutunu alır. |
| [getDataSize()](#getDataSize--) | Etiket değerinin boyutunu alır. |
| [getCount()](#getCount--) | Eleman sayısını alır. |
| [getId()](#getId--) | Etiket kimliğini sayı olarak alır. |
| [getTagId()](#getTagId--) | Etiket kimliğini alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getAlignedDataSize(byte sizeOfTagValue)](#getAlignedDataSize-byte-) | Veri boyutunu 4 bayt (int) veya 8 bayt (long) sınırına hizalanmış olarak alır. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Etiket değeri tamamen sığmazsa ek etiket değerinin bayt cinsinden boyutunu alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri ayarlar. |
| [isValid()](#isValid--) | Etiket verisinin geçerli olup olmadığını gösteren bir değer alır. |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Etiket verisini okur. |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Mevcut örneği aynı tipteki başka bir nesneyle karşılaştırır ve mevcut örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu gösteren bir tam sayı döndürür. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | Bu örneğin derin bir kopyasını oluşturur. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Etiket verisini yazar. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
| [toString()](#toString--) | Bu örneği temsil eden bir `System.String` döndürür. |
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Elemanın bayt cinsinden boyutunu alır.

**Returns:**
byte - öğenin bayt cinsinden boyutu.
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


Etiket değerinin boyutunu alır.

**Returns:**
long - etiket değerinin boyutu.
### getCount() {#getCount--}
```
public abstract long getCount()
```


Eleman sayısını alır.

Değer: Öğelerin sayısı.

**Returns:**
long - öğelerin sayısı.
### getId() {#getId--}
```
public final int getId()
```


Etiket kimliğini sayı olarak alır.

**Returns:**
int - etiket kimliği sayı olarak.
### getTagId() {#getTagId--}
```
public int getTagId()
```


Etiket kimliğini alır.

**Returns:**
int - Etiket kimliği.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Etiket tipini alır.

**Returns:**
int - Etiket türü.
### getAlignedDataSize(byte sizeOfTagValue) {#getAlignedDataSize-byte-}
```
public final long getAlignedDataSize(byte sizeOfTagValue)
```


Veri boyutunu 4 bayt (int) veya 8 bayt (long) sınırına hizalanmış olarak alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sizeOfTagValue | byte | Etiket değerinin boyutu. |

**Returns:**
long - hizalanmış veri boyutu bayt cinsinden.
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Etiket değeri tamamen sığmazsa ek etiket değerinin bayt cinsinden boyutunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sizeOfTagValue | byte | Etiket değerinin boyutu: BigTiff için 4 veya 8. |

**Returns:**
long - ek veri boyutu bayt cinsinden.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Bu veri tipinin içerdiği değeri alır.

**Returns:**
java.lang.Object - Değer.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Bu veri tipinin içerdiği değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | Değer. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Etiket verisinin geçerli olup olmadığını gösteren bir değer alır. Geçerli etiket, korunabilecek verileri içerir. Geçersiz etiket saklanamaz.

**Returns:**
boolean - etiket verisi geçerli ise `true`; aksi takdirde `false`.
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Etiket verisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Veri akışı. |
| konum | long | Etiket konumu. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Mevcut örneği aynı tipteki başka bir nesneyle karşılaştırır ve mevcut örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu gösteren bir tam sayı döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Bu örnekle karşılaştırılacak bir nesne. |

**Returns:**
int - 32 bit işaretli bir tam sayı olup, karşılaştırılan nesnelerin göreli sırasını gösterir. Dönüş değeri şu anlamlara gelir: Değer Anlamı Sıfırdan küçük Bu örnek `obj`'den küçüktür. Sıfır Bu örnek `obj`'ye eşittir. Sıfırdan büyük Bu örnek `obj`'den büyüktür.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Bu örneğin derin bir kopyasını oluşturur.

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Etiket verisini yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Veri akışı. |
| additionalDataOffset | long | Ek verinin yazılacağı ofset. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Ek etiket verisini yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Veri akışı. |

**Returns:**
long - Gerçek yazılan bayt sayısı.
### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir `System.String` döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir `System.String`.
