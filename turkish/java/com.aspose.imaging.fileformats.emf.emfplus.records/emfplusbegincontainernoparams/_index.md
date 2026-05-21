---
title: "EmfPlusBeginContainerNoParams"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusBeginContainerNoParams kaydı yeni bir grafik durum kapsayıcısı açar."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

EmfPlusBeginContainerNoParams kaydı yeni bir grafik durum kapsayıcısı açar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusBeginContainerNoParams` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Grafik durum konteyneriyle ilişkilendirilecek bir dizini belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setStackIndex(int value)](#setStackIndex-int-) | Grafik durum konteyneriyle ilişkilendirilecek bir dizini belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


Yeni bir `EmfPlusBeginContainerNoParams` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Grafik durum konteyneriyle ilişkilendirilecek bir dizini belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. Dizine, grafik durum konteynerini kapatmak için sonraki bir EmfPlusEndContainer kaydı (bölüm 2.3.7.3) tarafından başvurulMASI GEREKİR.

Değer: Yığının dizini.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Grafik durum konteyneriyle ilişkilendirilecek bir dizini belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. Dizine, grafik durum konteynerini kapatmak için sonraki bir EmfPlusEndContainer kaydı (bölüm 2.3.7.3) tarafından başvurulMASI GEREKİR.

Değer: Yığının dizini.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

