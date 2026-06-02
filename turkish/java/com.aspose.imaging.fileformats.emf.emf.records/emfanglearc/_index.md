---
title: "EmfAngleArc"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_ANGLEARC kaydı, bir yayının çizgi segmentini belirtir."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

EMR\_ANGLEARC kaydı, bir yayının çizgi segmentini belirtir. Çizgi segmenti, mevcut konumdan yayının başlangıcına doğru çizilir. Yay, verilen yarıçap ve merkezle bir dairenin çevresi boyunca çizilir. Yayın uzunluğu, verilen başlangıç ve süpürme açılarıyla tanımlanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfAngleArc` sınıfı örneği başlatır. |
| [EmfAngleArc()](#EmfAngleArc--) | Yeni bir `EmfAngleArc` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCenter()](#getCenter--) | 64-bit WMF PointL nesnesini alır veya ayarlar, [MS-WMF] bölüm 2.2.2.15'te belirtilen, dairenin merkezinin mantıksal koordinatlarını belirten. |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | 64-bit WMF PointL nesnesini alır veya ayarlar, [MS-WMF] bölüm 2.2.2.15'te belirtilen, dairenin merkezinin mantıksal koordinatlarını belirten. |
| [getRadius()](#getRadius--) | Dairenin yarıçapını mantıksal birimlerde belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setRadius(int value)](#setRadius-int-) | Dairenin yarıçapını mantıksal birimlerde belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getStartAngle()](#getStartAngle--) | Kemerin başlangıç açısını derece cinsinden belirten 32-bit kayan nokta sayısını alır veya ayarlar. |
| [setStartAngle(float value)](#setStartAngle-float-) | Kemerin başlangıç açısını derece cinsinden belirten 32-bit kayan nokta sayısını alır veya ayarlar. |
| [getSweepAngle()](#getSweepAngle--) | Kemerin süpürme açısını derece cinsinden belirten 32-bit kayan nokta sayısını alır veya ayarlar. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Kemerin süpürme açısını derece cinsinden belirten 32-bit kayan nokta sayısını alır veya ayarlar. |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


Yeni bir `EmfAngleArc` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


Yeni bir `EmfAngleArc` sınıfı örneği başlatır.

### getCenter() {#getCenter--}
```
public Point getCenter()
```


64-bit WMF PointL nesnesini alır veya ayarlar, [MS-WMF] bölüm 2.2.2.15'te belirtilen, dairenin merkezinin mantıksal koordinatlarını belirten.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


64-bit WMF PointL nesnesini alır veya ayarlar, [MS-WMF] bölüm 2.2.2.15'te belirtilen, dairenin merkezinin mantıksal koordinatlarını belirten.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


Dairenin yarıçapını mantıksal birimlerde belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Dairenin yarıçapını mantıksal birimlerde belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Kemerin başlangıç açısını derece cinsinden belirten 32-bit kayan nokta sayısını alır veya ayarlar.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Kemerin başlangıç açısını derece cinsinden belirten 32-bit kayan nokta sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Kemerin süpürme açısını derece cinsinden belirten 32-bit kayan nokta sayısını alır veya ayarlar.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Kemerin süpürme açısını derece cinsinden belirten 32-bit kayan nokta sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

