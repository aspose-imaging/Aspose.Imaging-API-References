---
title: "EmfPlusFillClosedCurve"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusFillClosedCurve kaydı, kapalı bir kardinal spline'ın içini doldurmayı belirtir"
type: docs
weight: 32
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

EmfPlusFillClosedCurve kaydı, kapalı bir kardinal spline'ın içini doldurmayı belirtir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusFillClosedCurve` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isColor()](#isColor--) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setColor(boolean value)](#setColor-boolean-) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getCompressed()](#getCompressed--) | Bu `EmfPlusFillClosedCurve`'ın sıkıştırılmış olup olmadığını belirten bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Bu `EmfPlusFillClosedCurve`'ın sıkıştırılmış olup olmadığını belirten bir değeri alır veya ayarlar. |
| [getWinding()](#getWinding--) | Bu `EmfPlusFillClosedCurve`'ın dolambaçlı (winding) olup olmadığını belirten bir değeri alır veya ayarlar. |
| [setWinding(boolean value)](#setWinding-boolean-) | Bu `EmfPlusFillClosedCurve`'ın dolambaçlı (winding) olup olmadığını belirten bir değeri alır veya ayarlar. |
| [getRelative()](#getRelative--) | Bu `EmfPlusFillClosedCurve`'ın göreli (relative) olup olmadığını belirten bir değeri alır veya ayarlar. |
| [setRelative(boolean value)](#setRelative-boolean-) | Bu `EmfPlusFillClosedCurve`'ın göreli (relative) olup olmadığını belirten bir değeri alır veya ayarlar. |
| [getBrushId()](#getBrushId--) | Fırça tanımlayıcısını alır veya ayarlar; EmfPlusBrush'ı belirten, içeriği Flags alanındaki S biti tarafından belirlenen 32 bit işaretsiz tam sayı. |
| [setBrushId(int value)](#setBrushId-int-) | Fırça tanımlayıcısını alır veya ayarlar; EmfPlusBrush'ı belirten, içeriği Flags alanındaki S biti tarafından belirlenen 32 bit işaretsiz tam sayı. |
| [getTension()](#getTension--) | Gerilimi alır veya ayarlar; noktalar üzerinden geçerken spline'ın ne kadar sık büküleceğini belirten 32 bit kayan nokta değeri. |
| [setTension(float value)](#setTension-float-) | Gerilimi alır veya ayarlar; noktalar üzerinden geçerken spline'ın ne kadar sık büküleceğini belirten 32 bit kayan nokta değeri. |
| [getPointData()](#getPointData--) | Nokta verisini alır veya ayarlar; spline'ı tanımlayan çizgilerin uç noktalarını belirten Count noktasından oluşan bir dizi. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Nokta verisini alır veya ayarlar; spline'ı tanımlayan çizgilerin uç noktalarını belirten Count noktasından oluşan bir dizi. |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


`EmfPlusFillClosedCurve` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, BrushId bir renk olarak EmfPlusARGB nesnesi (bölüm 2.2.2.1) ile belirtilir. Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir.

Değer: Bu örnek renk ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, BrushId bir renk olarak EmfPlusARGB nesnesi (bölüm 2.2.2.1) ile belirtilir. Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir.

Değer: Bu örnek renk ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Bu `EmfPlusFillClosedCurve`'ın sıkıştırılmış olup olmadığını belirten bir değeri alır veya ayarlar. Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir. Ayarlıysa, PointData 16 bit tam sayı koordinatlarıyla koordinat uzayında mutlak konumları belirtir. Temizlenmişse, PointData 32 bit kayan nokta koordinatlarıyla mutlak konumları belirtir. ---------------------- Bir "winding" doldurma işlemi, alanları "çift tek parite" kuralına göre doldurur. Bu kurala göre, bir test noktası aşağıdaki gibi kapalı bir eğrinin içinde mi dışarıda mı olduğu belirlenebilir: Test noktasından eğriden uzak bir noktaya bir çizgi çizin. Eğer bu çizgi eğriyi tek sayıda keserse, test noktası eğrinin içindedir; aksi takdirde dışındadır. --------------------- Bir "alternate" doldurma işlemi, alanları "sıfır olmayan" kurala göre doldurur. Bu kurala göre, bir test noktası aşağıdaki gibi kapalı bir eğrinin içinde mi dışarıda mı olduğu belirlenebilir: Test noktasından eğriden uzak bir noktaya bir çizgi çizin. Eğrinin çizgiyi soldan sağa kaç kez kestiğini ve sağdan sola kaç kez kestiğini sayın. Bu iki sayı aynıysa, test noktası eğrinin dışındadır; aksi takdirde içindedir.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Bu `EmfPlusFillClosedCurve`'ın sıkıştırılmış olup olmadığını belirten bir değeri alır veya ayarlar. Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir. Ayarlıysa, PointData 16 bit tam sayı koordinatlarıyla koordinat uzayında mutlak konumları belirtir. Temizlenmişse, PointData 32 bit kayan nokta koordinatlarıyla mutlak konumları belirtir. ---------------------- Bir "winding" doldurma işlemi, alanları "çift tek parite" kuralına göre doldurur. Bu kurala göre, bir test noktası aşağıdaki gibi kapalı bir eğrinin içinde mi dışarıda mı olduğu belirlenebilir: Test noktasından eğriden uzak bir noktaya bir çizgi çizin. Eğer bu çizgi eğriyi tek sayıda keserse, test noktası eğrinin içindedir; aksi takdirde dışındadır. --------------------- Bir "alternate" doldurma işlemi, alanları "sıfır olmayan" kurala göre doldurur. Bu kurala göre, bir test noktası aşağıdaki gibi kapalı bir eğrinin içinde mi dışarıda mı olduğu belirlenebilir: Test noktasından eğriden uzak bir noktaya bir çizgi çizin. Eğrinin çizgiyi soldan sağa kaç kez kestiğini ve sağdan sola kaç kez kestiğini sayın. Bu iki sayı aynıysa, test noktası eğrinin dışındadır; aksi takdirde içindedir.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


Bu `EmfPlusFillClosedCurve`'ın dolambaçlı (winding) olup olmadığını belirten bir değeri alır veya ayarlar. Bu bit, doldurma işleminin nasıl yapılacağını gösterir. Ayarlıysa, doldurma bir "winding" doldurma olur. Temizlenmişse, doldurma bir "alternate" doldurma olur.

Değer: dolambaçlı ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


Bu `EmfPlusFillClosedCurve`'ın dolambaçlı (winding) olup olmadığını belirten bir değeri alır veya ayarlar. Bu bit, doldurma işleminin nasıl yapılacağını gösterir. Ayarlıysa, doldurma bir "winding" doldurma olur. Temizlenmişse, doldurma bir "alternate" doldurma olur.

Değer: dolambaçlı ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Bu `EmfPlusFillClosedCurve`'ın göreli (relative) olup olmadığını belirten bir değeri alır veya ayarlar. Bu bit, PointData alanının göreli mi yoksa mutlak mı konumları belirttiğini gösterir. Ayarlıysa, PointData'daki her öğe, dizideki önceki öğe tarafından belirtilen konuma göre koordinat uzayında bir konum belirtir. PointData'daki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir. Not: Bu bayrak ayarlıysa, yukarıdaki C bayrağı tanımsızdır ve YOK EDİLMELİDİR.

Değer: göreceli ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Bu `EmfPlusFillClosedCurve`'ın göreli (relative) olup olmadığını belirten bir değeri alır veya ayarlar. Bu bit, PointData alanının göreli mi yoksa mutlak mı konumları belirttiğini gösterir. Ayarlıysa, PointData'daki her öğe, dizideki önceki öğe tarafından belirtilen konuma göre koordinat uzayında bir konum belirtir. PointData'daki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir. Not: Bu bayrak ayarlıysa, yukarıdaki C bayrağı tanımsızdır ve YOK EDİLMELİDİR.

Değer: göreceli ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Fırça tanımlayıcısını alır veya ayarlar; Flags alanındaki S biti tarafından belirlenen içeriğe sahip EmfPlusBrush'ı belirten 32 bit işaretsiz tam sayı. Bu fırça, kapalı kardinal spline'ın içini doldurmak için kullanılır.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Fırça tanımlayıcısını alır veya ayarlar; Flags alanındaki S biti tarafından belirlenen içeriğe sahip EmfPlusBrush'ı belirten 32 bit işaretsiz tam sayı. Bu fırça, kapalı kardinal spline'ın içini doldurmak için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


Gerilimi alır veya ayarlar; noktalar üzerinden geçerken spline'ın ne kadar sık büküleceğini belirten 32 bit kayan nokta değeri. 0.0 değeri, spline'ın düz çizgilerin bir dizisi olduğunu belirtir. Değer arttıkça eğri daha yuvarlaklaşır. Daha fazla bilgi için [SPLINE77] ve [PETZOLD] bakınız.

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Gerilimi alır veya ayarlar; noktalar üzerinden geçerken spline'ın ne kadar sık büküleceğini belirten 32 bit kayan nokta değeri. 0.0 değeri, spline'ın düz çizgilerin bir dizisi olduğunu belirtir. Değer arttıkça eğri daha yuvarlaklaşır. Daha fazla bilgi için [SPLINE77] ve [PETZOLD] bakınız.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Nokta verisini alır veya ayarlar; spline'ı tanımlayan çizgilerin uç noktalarını belirten Count noktasından oluşan bir dizi. Kapalı bir kardinal spline'da, eğri PointData dizisindeki son noktadan geçerek dizinin ilk noktasıyla bağlanır.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Nokta verisini alır veya ayarlar; spline'ı tanımlayan çizgilerin uç noktalarını belirten Count noktasından oluşan bir dizi. Kapalı bir kardinal spline'da, eğri PointData dizisindeki son noktadan geçerek dizinin ilk noktasıyla bağlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

