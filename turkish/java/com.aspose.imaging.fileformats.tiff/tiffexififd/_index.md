---
title: "TiffExifIfd"
second_title: "Aspose.Imaging for Java API Referansı"
description: "TIFF Exif görüntü dosyası dizini sınıfı."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

TIFF Exif görüntü dosyası dizini sınıfı.

Exif IFD'ye bir işaretçi kapsüller. Interoperability, Exif IFD, TIFF'te belirtilen IFD'nin aynı yapısına sahiptir. Ancak, genellikle TIFF durumunda olduğu gibi görüntü verisi içermez. Daha fazla ayrıntı için http://www.exiv2.org/tags.html ve http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html adreslerine bakın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Yeni bir `TiffExifIfd` sınıfı örneği başlatır. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Yeni bir `TiffExifIfd` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [hasValue()](#hasValue--) | Bu örneğin değer içerip içermediğini gösteren bir değer alır. |
| [getOffset()](#getOffset--) | EXIF IFD'ye işaretçiyi alır veya ayarlar. |
| [setOffset(long value)](#setOffset-long-) | EXIF IFD'ye işaretçiyi alır veya ayarlar. |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Yeni bir `TiffExifIfd` sınıfı örneği başlatır.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Yeni bir `TiffExifIfd` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ifdOffset | long | Exif IFD'ye bir işaretçi. |

Interoperability, Exif IFD, TIFF'te belirtilen IFD'nin aynı yapısına sahiptir. Ancak, genellikle TIFF durumunda olduğu gibi görüntü verisi içermez. |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Bu örneğin değer içerip içermediğini gösteren bir değer alır.

**Returns:**
boolean - bu örnek değer içeriyorsa `true`; aksi takdirde `false`.
### getOffset() {#getOffset--}
```
public long getOffset()
```


EXIF IFD'ye işaretçiyi alır veya ayarlar.

**Returns:**
long - EXIF IFD'ye işaretçi.
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


EXIF IFD'ye işaretçiyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | EXIF IFD'ye işaretçi. |

