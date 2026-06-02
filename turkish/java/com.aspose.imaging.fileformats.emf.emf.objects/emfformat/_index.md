---
title: "EmfFormat"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmrFormat nesnesi, EMR_COMMENT_MULTIFORMATS recordsection 2.3.3.4.3 içinde görüntü verisinin biçimini tanımlayan bilgileri içerir."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

EmrFormat nesnesi, EMR\_COMMENT\_MULTIFORMATS kaydındaki (bölüm 2.3.3.4.3) görüntü verisinin formatını tanımlayan bilgileri içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSignature()](#getSignature--) | Görüntü verisinin biçimini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setSignature(int value)](#setSignature-int-) | Görüntü verisinin biçimini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getVersion()](#getVersion--) | Biçim sürüm numarasını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setVersion(int value)](#setVersion-int-) | Biçim sürüm numarasını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getSizeData()](#getSizeData--) | Verinin bayt cinsinden boyutunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setSizeData(int value)](#setSizeData-int-) | Verinin bayt cinsinden boyutunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getOffData()](#getOffData--) | EMR\_COMMENT\_PUBLIC kaydındaki tanımlayıcı alanın başlangıcından veriye olan offseti belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar (bölüm 2.3.3.4). |
| [setOffData(int value)](#setOffData-int-) | EMR\_COMMENT\_PUBLIC kaydındaki tanımlayıcı alanın başlangıcından veriye olan offseti belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar (bölüm 2.3.3.4). |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Görüntü verisinin biçimini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer FormatSignature enumerasyonunda (bölüm 2.1.14) bulunmalıdır.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Görüntü verisinin biçimini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer FormatSignature enumerasyonunda (bölüm 2.1.14) bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Biçim sürüm numarasını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Signature alanı kapsüllenmiş PostScript (EPS) belirtirse, bu değer 0x00000001 olmalıdır; aksi takdirde bu değer göz ardı edilmelidir.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Biçim sürüm numarasını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Signature alanı kapsüllenmiş PostScript (EPS) belirtirse, bu değer 0x00000001 olmalıdır; aksi takdirde bu değer göz ardı edilmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Verinin bayt cinsinden boyutunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Verinin bayt cinsinden boyutunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


EMR\_COMMENT\_PUBLIC kaydındaki tanımlayıcı alanın başlangıcından veriye olan offseti belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar (bölüm 2.3.3.4). Offset 32 bit hizalı olmalıdır.

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


EMR\_COMMENT\_PUBLIC kaydındaki tanımlayıcı alanın başlangıcından veriye olan offseti belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar (bölüm 2.3.3.4). Offset 32 bit hizalı olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

