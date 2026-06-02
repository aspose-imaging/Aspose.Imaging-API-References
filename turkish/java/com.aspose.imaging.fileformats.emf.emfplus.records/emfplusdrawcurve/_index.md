---
title: "EmfPlusDrawCurve"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawCurve kaydı, bir kardinal spline çizmeyi belirtir NOT ObjectID 1 bayt EmfPlusPen nesnesinin (bölüm 2.2.1.7) EMF Nesne Tablosundaki indeksi, eğriyi çizmek için."
type: docs
weight: 19
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

EmfPlusDrawCurve kaydı, bir kardinal spline çizmeyi belirtir NOT: ObjectID (1 bayt): EmfPlusPen nesnesinin (bölüm 2.2.1.7) EMF+ Nesne Tablosundaki indeksi, eğriyi çizmek için. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusDrawCurve` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompressed()](#getCompressed--) | Bu `EmfPlusDrawClosedCurve`'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Bu `EmfPlusDrawClosedCurve`'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getTension()](#getTension--) | Gerilimi alır veya ayarlar. Noktalardan geçerken spline'ın ne kadar sık büküleceğini belirten 32-bit kayan nokta sayısı. |
| [setTension(float value)](#setTension-float-) | Gerilimi alır veya ayarlar. Noktalardan geçerken spline'ın ne kadar sık büküleceğini belirten 32-bit kayan nokta sayısı. |
| [getNumSegments()](#getNumSegments--) | Segment sayısını alır veya ayarlar. Spline'ı oluşturan çizgi segmentlerinin sayısını belirten 32-bit işaretsiz tamsayı. |
| [setNumSegments(int value)](#setNumSegments-int-) | Segment sayısını alır veya ayarlar. Spline'ı oluşturan çizgi segmentlerinin sayısını belirten 32-bit işaretsiz tamsayı. |
| [getPointData()](#getPointData--) | Çizilecek çizgilerin uç noktalarının koordinat değerlerini tanımlayan, Count uzunluğunda 32-bit işaretli tamsayılar veya 32-bit kayan nokta sayılarından oluşan bir dizi alır veya ayarlar. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Çizilecek çizgilerin uç noktalarının koordinat değerlerini tanımlayan, Count uzunluğunda 32-bit işaretli tamsayılar veya 32-bit kayan nokta sayılarından oluşan bir dizi alır veya ayarlar. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


Yeni bir `EmfPlusDrawCurve` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Bu `EmfPlusDrawClosedCurve` nesnesinin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir. Ayarlanmışsa, PointData koordinat uzayında 16-bit tam sayı koordinatlarıyla mutlak konumları belirtir. Temizlenmişse, PointData koordinat uzayında 32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir. Not: Aşağıdaki Relative bayrağı ayarlanmışsa, bu bayrak tanımsızdır ve YOK EDİLMELİDİR.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Bu `EmfPlusDrawClosedCurve` nesnesinin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir. Ayarlanmışsa, PointData koordinat uzayında 16-bit tam sayı koordinatlarıyla mutlak konumları belirtir. Temizlenmişse, PointData koordinat uzayında 32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir. Not: Aşağıdaki Relative bayrağı ayarlanmışsa, bu bayrak tanımsızdır ve YOK EDİLMELİDİR.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. EmfPlusPen nesnesinin (bölüm 2.2.1.7) EMF+ Nesne Tablosundaki indeksi, eğriyi çizmek için. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. EmfPlusPen nesnesinin (bölüm 2.2.1.7) EMF+ Nesne Tablosundaki indeksi, eğriyi çizmek için. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getTension() {#getTension--}
```
public float getTension()
```


Gerginliği alır veya ayarlar. Noktalar üzerinden geçerken spline'ın ne kadar sık büküleceğini belirten 32 bit kayan nokta sayısı. 0 değeri, spline'ın düz çizgilerden oluşan bir dizi olduğunu belirtir. Değer arttıkça eğri daha yuvarlaklaşır. Daha fazla bilgi için [SPLINE77] ve [PETZOLD] bağlantılarına bakın.

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Gerginliği alır veya ayarlar. Noktalar üzerinden geçerken spline'ın ne kadar sık büküleceğini belirten 32 bit kayan nokta sayısı. 0 değeri, spline'ın düz çizgilerden oluşan bir dizi olduğunu belirtir. Değer arttıkça eğri daha yuvarlaklaşır. Daha fazla bilgi için [SPLINE77] ve [PETZOLD] bağlantılarına bakın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


Segment sayısını alır veya ayarlar. Spline'ı oluşturan çizgi segmentlerinin sayısını belirten 32-bit işaretsiz tamsayı.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


Segment sayısını alır veya ayarlar. Spline'ı oluşturan çizgi segmentlerinin sayısını belirten 32-bit işaretsiz tamsayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Çizilecek çizgilerin uç noktalarının koordinat değerlerini tanımlayan, Count uzunluğunda 32-bit işaretli tamsayılar veya 32-bit kayan nokta sayılarından oluşan bir dizi alır veya ayarlar.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Çizilecek çizgilerin uç noktalarının koordinat değerlerini tanımlayan, Count uzunluğunda 32-bit işaretli tamsayılar veya 32-bit kayan nokta sayılarından oluşan bir dizi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

