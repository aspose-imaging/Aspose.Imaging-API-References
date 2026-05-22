---
title: "EmfPlusDrawLines"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawlLines kaydı bağlanan bir dizi çizgi çizmeyi belirtir."
type: docs
weight: 24
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

EmfPlusDrawlLines kaydı bağlanan bir dizi çizgi çizmeyi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusDrawLines` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getCompressed()](#getCompressed--) | Bu `EmfPlusDrawClosedCurve`'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Bu `EmfPlusDrawClosedCurve`'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [getRelative()](#getRelative--) | Bu `EmfPlusDrawClosedCurve`'ın göreli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setRelative(boolean value)](#setRelative-boolean-) | Bu `EmfPlusDrawClosedCurve`'ın göreli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getClosedShape()](#getClosedShape--) | [closed shape] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | [closed shape] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getPointData()](#getPointData--) | Nokta verisini alır veya ayarlar. Çizilecek çizgilerin başlangıç ve bitiş noktalarını belirten Count noktasından oluşan bir dizi. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Nokta verisini alır veya ayarlar. Çizilecek çizgilerin başlangıç ve bitiş noktalarını belirten Count noktasından oluşan bir dizi. |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


`EmfPlusDrawLines` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. Çizgileri çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. Çizgileri çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

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

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


[closed shape] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: [closed shape] ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


[closed shape] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: [closed shape] ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Nokta verisini alır veya ayarlar. Çizilecek çizgilerin başlangıç ve bitiş noktalarını belirten Count noktasından oluşan bir dizi.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Nokta verisini alır veya ayarlar. Çizilecek çizgilerin başlangıç ve bitiş noktalarını belirten Count noktasından oluşan bir dizi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

