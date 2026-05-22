---
title: "EmfExtSelectClipRgn"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_EXTSELECTCLIPRGN kaydı, belirtilen bölgeyi belirtilen mod kullanarak mevcut kırpma bölgesiyle birleştirir."
type: docs
weight: 55
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

EMR\_EXTSELECTCLIPRGN kaydı, belirtilen bölgeyi belirtilen mod kullanarak mevcut kırpma bölgesiyle birleştirir. Not: Bu bölümde açıklanmayan alanlar bölüm 2.3.2'de belirtilmiştir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfExtSelectClipRgn` sınıfı örneği başlatır. |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | Yeni bir `EmfExtSelectClipRgn` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | Bölge verisinin bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayı alır veya ayarlar. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Bölge verisinin bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayı alır veya ayarlar. |
| [getRegionMode()](#getRegionMode--) | Bölgenin kullanım şeklini belirten 32-bit işaretsiz tam sayı alır veya ayarlar. |
| [setRegionMode(int value)](#setRegionMode-int-) | Bölgenin kullanım şeklini belirten 32-bit işaretsiz tam sayı alır veya ayarlar. |
| [getRgnData()](#getRgnData--) | Mantıksal birimlerde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bir bayt dizisini alır veya ayarlar. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Mantıksal birimlerde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bir bayt dizisini alır veya ayarlar. |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


Yeni bir `EmfExtSelectClipRgn` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


Yeni bir `EmfExtSelectClipRgn` sınıfı örneği başlatır.

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Bölge verisinin bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayı alır veya ayarlar.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Bölge verisinin bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Bölgenin kullanım şeklini belirten 32-bit işaretsiz tam sayı alır veya ayarlar. Değer, RegionMode (bölüm 2.1.29) enumarasyonunda OLMAK ZORUNDADIR.

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Bölgenin kullanım şeklini belirten 32-bit işaretsiz tam sayı alır veya ayarlar. Değer, RegionMode (bölüm 2.1.29) enumarasyonunda OLMAK ZORUNDADIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Mantıksal birimlerde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bir bayt dizisini alır veya ayarlar. RegionMode RGN\_COPY ise, bu veri atlanabilir ve kırpma bölgesi, varsayılan (NULL) kırpma bölgesi olarak AYARLANMALIYDUR.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Mantıksal birimlerde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bir bayt dizisini alır veya ayarlar. RegionMode RGN\_COPY ise, bu veri atlanabilir ve kırpma bölgesi, varsayılan (NULL) kırpma bölgesi olarak AYARLANMALIYDUR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

