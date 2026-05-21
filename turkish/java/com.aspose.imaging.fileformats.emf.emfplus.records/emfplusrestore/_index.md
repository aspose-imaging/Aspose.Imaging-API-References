---
title: "EmfPlusRestore"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusRestore kaydı, kaydedilmiş grafik durumları yığınından belirtilen bir dizinle tanımlanan grafik durumunu geri yükler."
type: docs
weight: 49
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

EmfPlusRestore kaydı, belirtilen bir indeksle tanımlanan grafik durumunu, kaydedilmiş grafik durumları yığından geri yükler.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusRestore` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Grafik durumu ile ilişkili seviyeyi belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setStackIndex(int value)](#setStackIndex-int-) | Grafik durumu ile ilişkili seviyeyi belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


`EmfPlusRestore` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Grafik durumu ile ilişkili seviyeyi belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Seviye değeri, önceki bir EmfPlusSave kaydı (bölüm 2.3.7.5) tarafından grafik durumuna atanmıştır.

Değer: Yığının dizini.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Grafik durumu ile ilişkili seviyeyi belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Seviye değeri, önceki bir EmfPlusSave kaydı (bölüm 2.3.7.5) tarafından grafik durumuna atanmıştır.

Değer: Yığının dizini.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

