---
title: "EmfRectangle"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_RECTANGLE kaydı bir dikdörtgen çizer."
type: docs
weight: 107
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

EMR\_RECTANGLE kaydı bir dikdörtgen çizer. Dikdörtgen, mevcut kalem kullanılarak kenar çizilir ve mevcut fırça kullanılarak doldurulur.

Mevcut konum Rectangle tarafından ne kullanılır ne de güncellenir. Eğer bir PS\_NULL kalem kullanılırsa, dikdörtgenin boyutları yükseklikte 1 piksel ve genişlikte 1 piksel daha az olur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfRectangle` sınıfı örneği başlatır. |
| [EmfRectangle()](#EmfRectangle--) | Yeni bir `EmfRectangle` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBox()](#getBox--) | Çizilecek kapsayıcı- kapsayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Çizilecek kapsayıcı- kapsayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar. |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


Yeni bir `EmfRectangle` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


Yeni bir `EmfRectangle` sınıfı örneği başlatır.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Çizilecek kapsayıcı- kapsayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Çizilecek kapsayıcı- kapsayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

