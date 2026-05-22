---
title: "EmfSelectObject"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SELECTOBJECT kaydı, bir grafik nesnesini mevcut metafile oynatma cihaz bağlamına ekler."
type: docs
weight: 116
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

EMR\_SELECTOBJECT kaydı, bir grafik nesnesini mevcut metafile oynatma cihaz bağlamına ekler. Nesne, EMF Nesne Tablosu (bölüm 3.1.1.1) içindeki indeksiyle ya da StockObject enumarasyonundan (bölüm 2.1.31) değeriyle belirtilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfSelectObject` sınıfı örneği başlatır. |
| [EmfSelectObject()](#EmfSelectObject--) | Yeni bir `EmfSelectObject` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | EMF Nesne Tablosundaki bir grafik nesnesinin indeksini ya da `Consts.EmfStockObject` enumarasyonundaki bir stok nesnesinin indeksini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | EMF Nesne Tablosundaki bir grafik nesnesinin indeksini ya da `Consts.EmfStockObject` enumarasyonundaki bir stok nesnesinin indeksini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


Yeni bir `EmfSelectObject` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kayıt. |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


Yeni bir `EmfSelectObject` sınıfı örneği başlatır.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


EMF Nesne Tablosundaki bir grafik nesnesinin indeksini ya da `Consts.EmfStockObject` enumarasyonundaki bir stok nesnesinin indeksini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


EMF Nesne Tablosundaki bir grafik nesnesinin indeksini ya da `Consts.EmfStockObject` enumarasyonundaki bir stok nesnesinin indeksini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

