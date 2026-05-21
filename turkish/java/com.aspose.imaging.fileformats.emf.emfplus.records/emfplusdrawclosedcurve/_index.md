---
title: "EmfPlusDrawClosedCurve"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawClosedCurve kaydı kapalı bir kardinal spline çizmeyi belirtir."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawClosedCurve extends EmfPlusDrawingRecordType
```

EmfPlusDrawClosedCurve kaydı kapalı bir kardinal spline çizmeyi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawClosedCurve(EmfPlusRecord source)](#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusDrawClosedCurve` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getCompressed()](#getCompressed--) | Bu `EmfPlusDrawClosedCurve`'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Bu `EmfPlusDrawClosedCurve`'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [getRelative()](#getRelative--) | Bu `EmfPlusDrawClosedCurve`'ın göreli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setRelative(boolean value)](#setRelative-boolean-) | Bu `EmfPlusDrawClosedCurve`'ın göreli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getTension()](#getTension--) | Gerilimi alır veya ayarlar. Noktalardan geçerken spline'ın ne kadar sık büküleceğini belirten 32-bit kayan nokta sayısı. |
| [setTension(float value)](#setTension-float-) | Gerilimi alır veya ayarlar. Noktalardan geçerken spline'ın ne kadar sık büküleceğini belirten 32-bit kayan nokta sayısı. |
| [getPointData()](#getPointData--) | Nokta verisini alır veya ayarlar; spline'ı tanımlayan çizgilerin uç noktalarını belirten Count noktasından oluşan bir dizi. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Nokta verisini alır veya ayarlar; spline'ı tanımlayan çizgilerin uç noktalarını belirten Count noktasından oluşan bir dizi. |
### EmfPlusDrawClosedCurve(EmfPlusRecord source) {#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawClosedCurve(EmfPlusRecord source)
```


`EmfPlusDrawClosedCurve` sınıfının yeni bir örneğini başlatır. RecordType - RecordType enumarasyonundan (bölüm 2.1.1.1) bu kayıt türünü EmfPlusDrawClosedCurve olarak tanımlayan 16-bit işaretsiz tam sayı. Değer 0x4017 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. Kapalı eğriyi çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. Kapalı eğriyi çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

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

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Bu `EmfPlusDrawClosedCurve` nesnesinin göreceli olup olmadığını gösteren bir değeri alır veya ayarlar. Bu bit, PointData alanının göreceli mi yoksa mutlak konumları mı belirttiğini gösterir. Ayarlanmışsa, PointData'deki her öğe, dizideki bir önceki öğe tarafından belirtilen konuma göreceli bir konumu belirtir. PointData'deki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir. Not: Bu bayrak ayarlanmışsa, yukarıdaki Compressed bayrağı tanımsızdır ve YOK EDİLMELİDİR.

Değer: göreceli ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Bu `EmfPlusDrawClosedCurve` nesnesinin göreceli olup olmadığını gösteren bir değeri alır veya ayarlar. Bu bit, PointData alanının göreceli mi yoksa mutlak konumları mı belirttiğini gösterir. Ayarlanmışsa, PointData'deki her öğe, dizideki bir önceki öğe tarafından belirtilen konuma göreceli bir konumu belirtir. PointData'deki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir. Not: Bu bayrak ayarlanmışsa, yukarıdaki Compressed bayrağı tanımsızdır ve YOK EDİLMELİDİR.

Değer: göreceli ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Nokta verisini alır veya ayarlar. Spline'ı tanımlayan çizgilerin uç noktalarını belirten Count sayıda nokta içeren bir dizi. Kapalı bir kardinal spline'da, eğri PointData dizisindeki son nokta üzerinden devam eder ve dizinin ilk noktasıyla bağlanır. Bu dizideki veri tipi Flags alanı tarafından aşağıdaki gibi belirtilir: Veri Tipi Anlamı EmfPlusPointR nesnesi (bölüm 2.2.2.37) Flags içinde P bayrağı ayarlıysa, noktalar göreli konumları belirtir. EmfPlusPointF nesnesi (bölüm 2.2.2.36) Flags alanında P ve C bitleri ayarlıysa, noktalar mutlak konumları belirtir. EmfPlusPoint nesnesi (bölüm 2.2.2.35) Flags alanında P biti temiz ve C biti ayarlıysa, noktalar göreli konumları belirtir.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Nokta verisini alır veya ayarlar. Spline'ı tanımlayan çizgilerin uç noktalarını belirten Count sayıda nokta içeren bir dizi. Kapalı bir kardinal spline'da, eğri PointData dizisindeki son nokta üzerinden devam eder ve dizinin ilk noktasıyla bağlanır. Bu dizideki veri tipi Flags alanı tarafından aşağıdaki gibi belirtilir: Veri Tipi Anlamı EmfPlusPointR nesnesi (bölüm 2.2.2.37) Flags içinde P bayrağı ayarlıysa, noktalar göreli konumları belirtir. EmfPlusPointF nesnesi (bölüm 2.2.2.36) Flags alanında P ve C bitleri ayarlıysa, noktalar mutlak konumları belirtir. EmfPlusPoint nesnesi (bölüm 2.2.2.35) Flags alanında P biti temiz ve C biti ayarlıysa, noktalar göreli konumları belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

