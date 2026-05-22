---
title: "EmfPlusSave"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSave kaydı, belirli bir indeksle tanımlanan grafik durumunu kaydedilmiş grafik durumları yığını üzerinde kaydeder."
type: docs
weight: 51
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

EmfPlusSave kaydı, belirtilen bir indeksle tanımlanan grafik durumunu, kaydedilmiş grafik durumları yığınına kaydeder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusSave` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Grafik durumuyla ilişkilendirilecek bir seviyeyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setStackIndex(int value)](#setStackIndex-int-) | Grafik durumuyla ilişkilendirilecek bir seviyeyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


`EmfPlusSave` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Grafik durumuyla ilişkilendirilecek bir seviyeyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Seviye değeri, sonraki bir EmfPlusRestore kaydı (bölüm 2.3.7.4) işlemi tarafından grafik durumunu geri almak için kullanılabilir.

Değer: Yığının dizini.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Grafik durumuyla ilişkilendirilecek bir seviyeyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Seviye değeri, sonraki bir EmfPlusRestore kaydı (bölüm 2.3.7.4) işlemi tarafından grafik durumunu geri almak için kullanılabilir.

Değer: Yığının dizini.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

