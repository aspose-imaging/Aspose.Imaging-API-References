---
title: "EmfExtFloodFill"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_EXTFLOODFILL kaydı, görüntü yüzeyinin bir alanını mevcut fırça ile doldurur"
type: docs
weight: 54
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

EMR\_EXTFLOODFILL kaydı, görüntü yüzeyinin bir alanını mevcut fırça ile doldurur
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfExtFloodFill` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStart()](#getStart--) | Doldurmanın başladığı koordinatları mantıksal birimlerde belirten bir WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Doldurmanın başladığı koordinatları mantıksal birimlerde belirten bir WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar. |
| [getArgb32Color()](#getArgb32Color--) | Doldurulacak alanı belirlemek için FloodFillMode ile kullanılan bir WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Doldurulacak alanı belirlemek için FloodFillMode ile kullanılan bir WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. |
| [getFloodFillMode()](#getFloodFillMode--) | Flood fill işlemi için alanı belirlemek amacıyla Color değerinin nasıl kullanılacağını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | Flood fill işlemi için alanı belirlemek amacıyla Color değerinin nasıl kullanılacağını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


`EmfExtFloodFill` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getStart() {#getStart--}
```
public Point getStart()
```


Doldurmanın başladığı koordinatları mantıksal birimlerde belirten bir WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Doldurmanın başladığı koordinatları mantıksal birimlerde belirten bir WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Doldurulacak alanı belirlemek için FloodFillMode ile kullanılan bir WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Doldurulacak alanı belirlemek için FloodFillMode ile kullanılan bir WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


Flood fill işlemi için alanı belirlemek amacıyla Color değerinin nasıl kullanılacağını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer FloodFill numaralandırmasında (bölüm 2.1.13) OLMAK ZORUNDADIR.

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


Flood fill işlemi için alanı belirlemek amacıyla Color değerinin nasıl kullanılacağını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer FloodFill numaralandırmasında (bölüm 2.1.13) OLMAK ZORUNDADIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

