---
title: "EmfChord"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_CHORD kaydı, bir sekant olarak adlandırılan bir doğru parçası ile bir elipsin kesişimiyle sınırlanan bir bölge olan kordı belirtir."
type: docs
weight: 20
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

EMR\_CHORD kaydı, bir sekant olarak adlandırılan bir doğru parçası ile bir elipsin kesişimiyle sınırlanan bir bölge olan kordı belirtir. Kord, mevcut kalem kullanılarak kenar çizilir ve mevcut fırça kullanılarak doldurulur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfChord` sınıfının yeni bir örneğini başlatır. |
| [EmfChord()](#EmfChord--) | `EmfChord` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBox()](#getBox--) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, kapsayıcı-kapsayıcı sınırlayıcı dikdörtgeni belirten 128 bit WMF RectL nesnesini alır veya ayarlar. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, kapsayıcı-kapsayıcı sınırlayıcı dikdörtgeni belirten 128 bit WMF RectL nesnesini alır veya ayarlar. |
| [getStart()](#getStart--) | Kordun başlangıcını tanımlayan radyalin uç noktasının mantıksal koordinatlarını belirten, [MS-WMF] bölüm 2.2.2.15'de tanımlanan 64-bit WMF PointL nesnesini alır veya ayarlar. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Kordun başlangıcını tanımlayan radyalin uç noktasının mantıksal koordinatlarını belirten, [MS-WMF] bölüm 2.2.2.15'de tanımlanan 64-bit WMF PointL nesnesini alır veya ayarlar. |
| [getEnd()](#getEnd--) | Kordun sonunu tanımlayan radyalin uç noktasının mantıksal koordinatlarını belirten 64-bit WMF PointL nesnesini alır veya ayarlar. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Kordun sonunu tanımlayan radyalin uç noktasının mantıksal koordinatlarını belirten 64-bit WMF PointL nesnesini alır veya ayarlar. |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


`EmfChord` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


`EmfChord` sınıfının yeni bir örneğini başlatır.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, kapsayıcı-kapsayıcı sınırlayıcı dikdörtgeni belirten 128 bit WMF RectL nesnesini alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, kapsayıcı-kapsayıcı sınırlayıcı dikdörtgeni belirten 128 bit WMF RectL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Kordun başlangıcını tanımlayan radyalin uç noktasının mantıksal koordinatlarını belirten, [MS-WMF] bölüm 2.2.2.15'de tanımlanan 64-bit WMF PointL nesnesini alır veya ayarlar.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Kordun başlangıcını tanımlayan radyalin uç noktasının mantıksal koordinatlarını belirten, [MS-WMF] bölüm 2.2.2.15'de tanımlanan 64-bit WMF PointL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Kordun sonunu tanımlayan radyalin uç noktasının mantıksal koordinatlarını belirten 64-bit WMF PointL nesnesini alır veya ayarlar.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Kordun sonunu tanımlayan radyalin uç noktasının mantıksal koordinatlarını belirten 64-bit WMF PointL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

