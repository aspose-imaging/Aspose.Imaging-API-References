---
title: "EmfFillRgn"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_FILLRGN kaydı, belirtilen bölgeyi belirtilen fırça kullanarak doldurur."
type: docs
weight: 59
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

EMR\_FILLRGN kaydı, belirtilen bölgeyi belirtilen fırça ile doldurur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfFillRgn` sınıfının yeni bir örneğini başlatır. |
| [EmfFillRgn()](#EmfFillRgn--) | `EmfFillRgn` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır veya ayarlar. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır veya ayarlar. |
| [getRgnDataSize()](#getRgnDataSize--) | Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getIhBrush()](#getIhBrush--) | Bölgeyi doldurmak için fırça EMF Nesne Tablosu dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIhBrush(int value)](#setIhBrush-int-) | Bölgeyi doldurmak için fırça EMF Nesne Tablosu dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getRgnData()](#getRgnData--) | RegionData (bölüm 2.2.24) nesnesini içeren bir RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | RegionData (bölüm 2.2.24) nesnesini içeren bir RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar. |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


`EmfFillRgn` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


`EmfFillRgn` sınıfının yeni bir örneğini başlatır.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Bölgeyi doldurmak için fırça EMF Nesne Tablosu dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Bölgeyi doldurmak için fırça EMF Nesne Tablosu dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


RegionData (bölüm 2.2.24) nesnesini içeren bir RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


RegionData (bölüm 2.2.24) nesnesini içeren bir RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

