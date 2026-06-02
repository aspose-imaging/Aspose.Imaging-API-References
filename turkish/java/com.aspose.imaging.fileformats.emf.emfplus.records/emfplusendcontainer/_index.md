---
title: "EmfPlusEndContainer"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusEndContainer kaydı, daha önce bir başlat konteyner işlemiyle açılmış bir grafik durumu konteynerini kapatır."
type: docs
weight: 30
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

EmfPlusEndContainer kaydı, daha önce bir başlat konteyner işlemiyle açılmış bir grafik durumu konteynerini kapatır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusEndContainer` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Bir grafik durum kapsayıcısının dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setStackIndex(int value)](#setStackIndex-int-) | Bir grafik durum kapsayıcısının dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


Yeni bir `EmfPlusEndContainer` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Bir grafik durum kapsayıcısının dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Dizin **MUST** önceki bir EmfPlusBeginContainer (bölüm 2.3.7.1) veya EmfPlusBeginContainerNoParams kaydı (bölüm 2.3.7.2) tarafından açılan bir grafik durum kapsayıcısıyla ilişkili değere eşleşmelidir.

Değer: Yığının dizini.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Bir grafik durum kapsayıcısının dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Dizin **MUST** önceki bir EmfPlusBeginContainer (bölüm 2.3.7.1) veya EmfPlusBeginContainerNoParams kaydı (bölüm 2.3.7.2) tarafından açılan bir grafik durum kapsayıcısıyla ilişkili değere eşleşmelidir.

Değer: Yığının dizini.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

