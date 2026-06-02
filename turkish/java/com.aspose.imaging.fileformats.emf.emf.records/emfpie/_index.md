---
title: "EmfPie"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_PIE kaydı, bir elips ve iki radyalın kesişimiyle sınırlanan pasta şeklinde bir dilimi tanımlar."
type: docs
weight: 82
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

EMR\\_PIE kaydı, bir elips ve iki radyalın kesişimiyle sınırlanan pasta şeklinde bir dilimi tanımlar. Pasta, mevcut kalem kullanılarak konturlanır ve mevcut fırça kullanılarak doldurulur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfPie` sınıfının yeni bir örneğini başlatır. |
| [EmfPie()](#EmfPie--) | `EmfPie` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBox()](#getBox--) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, kapsayıcı-kapsayıcı sınırlayıcı dikdörtgeni belirten 128 bit WMF RectL nesnesini alır veya ayarlar. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, kapsayıcı-kapsayıcı sınırlayıcı dikdörtgeni belirten 128 bit WMF RectL nesnesini alır veya ayarlar. |
| [getStart()](#getStart--) | İlk radyalin uç noktasının mantıksal birimlerdeki koordinatlarını belirten, [MS-WMF] bölüm 2.2.2.15'te tanımlanan 64 bit WMF PointL nesnesini alır veya ayarlar. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | İlk radyalin uç noktasının mantıksal birimlerdeki koordinatlarını belirten, [MS-WMF] bölüm 2.2.2.15'te tanımlanan 64 bit WMF PointL nesnesini alır veya ayarlar. |
| [getEnd()](#getEnd--) | İkinci radyalin uç noktasının mantıksal birimlerdeki koordinatlarını belirten 64 bit PointL nesnesini alır veya ayarlar. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | İkinci radyalin uç noktasının mantıksal birimlerdeki koordinatlarını belirten 64 bit PointL nesnesini alır veya ayarlar. |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


`EmfPie` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


`EmfPie` sınıfının yeni bir örneğini başlatır.

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


İlk radyalin uç noktasının mantıksal birimlerdeki koordinatlarını belirten, [MS-WMF] bölüm 2.2.2.15'te tanımlanan 64 bit WMF PointL nesnesini alır veya ayarlar.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


İlk radyalin uç noktasının mantıksal birimlerdeki koordinatlarını belirten, [MS-WMF] bölüm 2.2.2.15'te tanımlanan 64 bit WMF PointL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


İkinci radyalin uç noktasının mantıksal birimlerdeki koordinatlarını belirten 64 bit PointL nesnesini alır veya ayarlar.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


İkinci radyalin uç noktasının mantıksal birimlerdeki koordinatlarını belirten 64 bit PointL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

