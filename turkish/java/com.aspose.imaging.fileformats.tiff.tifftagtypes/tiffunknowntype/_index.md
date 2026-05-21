---
title: "TiffUnknownType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bilinmeyen tiff türü."
type: docs
weight: 27
url: /tr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

Bilinmeyen tiff türü. tiff etiketi tanınamazsa bu tür örneklenir.

Not: `TiffUnknownType` akışa geri serileştirilmez.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | Yeni bir `TiffUnknownType` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Eleman sayısını alır. |
| [getOffsetOrValue()](#getOffsetOrValue--) | Sayım 1 ise ek veri veya değerin kendisi için ofset değerini alır. |
| [getStream()](#getStream--) | Ek veriyi okumak için akışı alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Etiket değeri tamamen sığmazsa ek etiket değerinin bayt cinsinden boyutunu alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
| [toString()](#toString--) | Bu örneği temsil eden bir `System.String` döndürür. |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


Yeni bir `TiffUnknownType` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Okunacak akış. |
| tagType | int | Etiketin türü. |
| tagId | int | Etiket kimliği. |
| count | long | Sayım değeri. |
| offsetOrValue | long | Ofset ya da değer. |

### getCount() {#getCount--}
```
public long getCount()
```


Eleman sayısını alır.

Değer: Öğelerin sayısı.

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


Sayım 1 ise ek veri veya değerin kendisi için ofset değerini alır.

Değer: Ofset ya da değer.

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


Ek veriyi okumak için akışı alır.

Değer: Veriyi okumak için akış.

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


Etiket tipini alır.

Değer: Etiket türü.

**Returns:**
int
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
public Object getValue()
```


Bu veri tipinin içerdiği değeri alır veya ayarlar.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Bu veri tipinin içerdiği değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
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
