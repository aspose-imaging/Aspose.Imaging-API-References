---
title: "EmfPlusFillPolygon"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusFillPolygon kaydı, bir çokgenin içini doldurmayı belirtir."
type: docs
weight: 36
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPolygon extends EmfPlusDrawingRecordType
```

EmfPlusFillPolygon kaydı, bir çokgenin içini doldurmayı belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusFillPolygon(EmfPlusRecord source)](#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusFillPolygon` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isColor()](#isColor--) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setColor(boolean value)](#setColor-boolean-) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isCompressed()](#isCompressed--) | Bu örneğin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Bu örneğin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isRelative()](#isRelative--) | Alır veya ayarlar bu örneğin göreli olup olmadığını gösteren bir değeri. |
| [setRelative(boolean value)](#setRelative-boolean-) | Alır veya ayarlar bu örneğin göreli olup olmadığını gösteren bir değeri. |
| [getBrushId()](#getBrushId--) | Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir. |
| [setBrushId(int value)](#setBrushId-int-) | Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir. |
| [getPointData()](#getPointData--) | Alır veya ayarlar nokta verisini: Çokgenin köşelerini tanımlayan Count noktasından oluşan bir dizi. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Alır veya ayarlar nokta verisini: Çokgenin köşelerini tanımlayan Count noktasından oluşan bir dizi. |
### EmfPlusFillPolygon(EmfPlusRecord source) {#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPolygon(EmfPlusRecord source)
```


Yeni bir `EmfPlusFillPolygon` sınıfı örneği başlatır.

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

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Bu örneğin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, PointData koordinat uzayında 16-bit tam sayı koordinatlarıyla mutlak konumları belirtir. Temizlenmişse, PointData koordinat uzayında 32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir.

Değer: Bu örnek sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Bu örneğin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, PointData koordinat uzayında 16-bit tam sayı koordinatlarıyla mutlak konumları belirtir. Temizlenmişse, PointData koordinat uzayında 32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir.

Değer: Bu örnek sıkıştırılmışsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### isRelative() {#isRelative--}
```
public boolean isRelative()
```


Bu örneğin göreli olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, PointData içindeki her öğe, dizideki önceki öğe tarafından belirtilen konuma göreceli bir konumu belirtir. PointData'nın ilk öğesi için, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir.

Değer: Bu örnek göreli ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Bu örneğin göreli olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, PointData içindeki her öğe, dizideki önceki öğe tarafından belirtilen konuma göreceli bir konumu belirtir. PointData'nın ilk öğesi için, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir.

Değer: Bu örnek göreli ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Nokta verisini alır veya ayarlar. Çokgenin köşelerini tanımlayan Count noktasından oluşan bir dizi. Dizideki ilk iki nokta çokgenin ilk kenarını belirtir. Her ek nokta yeni bir kenar belirtir; bu kenarın köşeleri nokta ve önceki noktayı içerir. Son nokta ve ilk nokta aynı değilse, çokgenin son kenarını belirtir.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Nokta verisini alır veya ayarlar. Çokgenin köşelerini tanımlayan Count noktasından oluşan bir dizi. Dizideki ilk iki nokta çokgenin ilk kenarını belirtir. Her ek nokta yeni bir kenar belirtir; bu kenarın köşeleri nokta ve önceki noktayı içerir. Son nokta ve ilk nokta aynı değilse, çokgenin son kenarını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

