---
title: "EmfPlusFillEllipse"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusFillEllipse kaydı, bir elipsin içini doldurmayı belirtir"
type: docs
weight: 33
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

EmfPlusFillEllipse kaydı, bir elipsin içini doldurmayı belirtir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusFillEllipse` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isColor()](#isColor--) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setColor(boolean value)](#setColor-boolean-) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isCompressed()](#isCompressed--) | Bu örneğin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Bu örneğin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getBrushId()](#getBrushId--) | Fırça tanımlayıcısını alır veya ayarlar. Fırçayı belirten 32 bit işaretsiz tamsayı; içeriği Flags alanındaki S biti tarafından belirlenir. |
| [setBrushId(int value)](#setBrushId-int-) | Fırça tanımlayıcısını alır veya ayarlar. Fırçayı belirten 32 bit işaretsiz tamsayı; içeriği Flags alanındaki S biti tarafından belirlenir. |
| [getRectData()](#getRectData--) | Elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi olan dikdörtgen verisini alır veya ayarlar |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi olan dikdörtgen verisini alır veya ayarlar |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


`EmfPlusFillEllipse` sınıfının yeni bir örneğini başlatır.

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


Bu örneğin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, RectData bir EmfPlusRect nesnesi içerir (bölüm 2.2.2.38). Temizlenmişse, RectData bir EmfPlusRectF nesnesi içerir (bölüm 2.2.2.39).

Değer: Bu örnek sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Bu örneğin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, RectData bir EmfPlusRect nesnesi içerir (bölüm 2.2.2.38). Temizlenmişse, RectData bir EmfPlusRectF nesnesi içerir (bölüm 2.2.2.39).

Değer: Bu örnek sıkıştırılmışsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Fırça tanımlayıcısını alır veya ayarlar. Fırçayı belirten 32 bit işaretsiz bir tam sayı; içeriği Flags alanındaki S biti tarafından belirlenir. Bu tanım, elipsin içini doldurmak için kullanılır.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Fırça tanımlayıcısını alır veya ayarlar. Fırçayı belirten 32 bit işaretsiz bir tam sayı; içeriği Flags alanındaki S biti tarafından belirlenir. Bu tanım, elipsin içini doldurmak için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi olan dikdörtgen verisini alır veya ayarlar

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi olan dikdörtgen verisini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

