---
title: "WmfBitmapBaseHeader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Temel bitmap başlık sınıfı."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

Temel bitmap başlık sınıfı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Bu nesnenin boyutunu bayt cinsinden tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setHeaderSize(int value)](#setHeaderSize-int-) | Bu nesnenin boyutunu bayt cinsinden tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getPlanes()](#getPlanes--) | `planes` sayısını hedef aygıt için tanımlayan 16-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setPlanes(short value)](#setPlanes-short-) | `planes` sayısını hedef aygıt için tanımlayan 16-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getBitCount()](#getBitCount--) | Her pikselin biçimini ve DIB'deki maksimum renk sayısını tanımlayan 16-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setBitCount(short value)](#setBitCount-short-) | Her pikselin biçimini ve DIB'deki maksimum renk sayısını tanımlayan 16-bit işaretsiz tam sayıyı alır veya ayarlar. |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


Bu nesnenin boyutunu bayt cinsinden tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


Bu nesnenin boyutunu bayt cinsinden tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Hedef aygıt için `planes` sayısını tanımlayan 16-bit işaretsiz tam sayı. Bu değer 0x0001 olmalıdır. |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


Hedef cihaz için `planes` sayısını tanımlayan 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 0x0001 OLMALIDIR.

**Returns:**
short - hedef cihaz için `planes` sayısını tanımlayan 16 bit işaretsiz tam sayı.
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


Hedef cihaz için `planes` sayısını tanımlayan 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 0x0001 OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short | hedef cihaz için `planes` sayısını tanımlayan 16 bit işaretsiz tam sayı. Bu değer \* 0x0001 OLMALIDIR. |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


Her pikselin biçimini ve DIB içindeki en fazla renk sayısını tanımlayan 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer `BitCount` Sıralamasında (bölüm 2.1.1.3) OLMALIDIR.

**Returns:**
short - her pikselin biçimini ve DIB içindeki en fazla renk sayısını tanımlayan 16 bit işaretsiz tam sayı.
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


Her pikselin biçimini ve DIB içindeki en fazla renk sayısını tanımlayan 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer `BitCount` Sıralamasında (bölüm 2.1.1.3) OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short | her pikselin biçimini ve DIB içindeki en fazla renk sayısını tanımlayan 16 bit işaretsiz tam sayı. |

