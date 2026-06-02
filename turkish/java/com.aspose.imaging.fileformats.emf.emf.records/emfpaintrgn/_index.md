---
title: "EmfPaintRgn"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_PAINTRGN kaydı, oynatma aygıt bağlamına şu anda seçili olan fırçayı kullanarak belirtilen bölgeyi boyar."
type: docs
weight: 80
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

EMR_PAINTRGN kaydı, oynatma cihaz bağlamına şu anda seçili fırça kullanılarak belirtilen bölgeyi boyar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfPaintRgn` sınıfının yeni bir örneğini başlatır. |
| [EmfPaintRgn()](#EmfPaintRgn--) | `EmfPaintRgn` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini ayarlar. |
| [getRgnDataSize()](#getRgnDataSize--) | Bölge verisinin boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı alır. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Bölge verisinin boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı ayarlar. |
| [getRgnData()](#getRgnData--) | Mantıksal birimlerde bir RegionData (bölüm 2.2.24) nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Mantıksal birimlerde bir RegionData (bölüm 2.2.24) nesnesini belirten RgnDataSize uzunluğunda bayt dizisini ayarlar. |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


`EmfPaintRgn` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


`EmfPaintRgn` sınıfının yeni bir örneğini başlatır.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Bölge verisinin boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı alır.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Bölge verisinin boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Mantıksal birimlerde bir RegionData (bölüm 2.2.24) nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Mantıksal birimlerde bir RegionData (bölüm 2.2.24) nesnesini belirten RgnDataSize uzunluğunda bayt dizisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

