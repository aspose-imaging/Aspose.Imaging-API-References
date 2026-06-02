---
title: "EmfPlusBeginContainer"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusBeginContainer kaydı yeni bir grafik durum kapsayıcısı açar ve onun için bir dönüşüm belirtir."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

EmfPlusBeginContainer kaydı yeni bir grafik durum kapsayıcısı açar ve onun için bir dönüşüm belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusBeginContainer` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Sayfa birimini alır. |
| [getDestRect()](#getDestRect--) | SrcRect ile birlikte konteyner için bir dönüşüm belirten bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar. |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | SrcRect ile birlikte konteyner için bir dönüşüm belirten bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar. |
| [getSrcRect()](#getSrcRect--) | DestRect ile birlikte konteyner için bir dönüşüm belirten bir EmfPlusRectF dikdörtgenini alır veya ayarlar. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | DestRect ile birlikte konteyner için bir dönüşüm belirten bir EmfPlusRectF dikdörtgenini alır veya ayarlar. |
| [getStackIndex()](#getStackIndex--) | Grafik durum konteyneriyle ilişkilendirilecek bir dizini belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setStackIndex(int value)](#setStackIndex-int-) | Grafik durum konteyneriyle ilişkilendirilecek bir dizini belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


`EmfPlusBeginContainer` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Sayfa birimini alır.

Değer: Sayfa birimi.

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


SrcRect ile birlikte konteyner için bir dönüşüm belirten bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar. Bu dönüşüm, DestRect'e uygulandığında SrcRect sonucunu verir.

Değer: Hedef dikdörtgen.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


SrcRect ile birlikte konteyner için bir dönüşüm belirten bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar. Bu dönüşüm, DestRect'e uygulandığında SrcRect sonucunu verir.

Değer: Hedef dikdörtgen.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


DestRect ile birlikte konteyner için bir dönüşüm belirten bir EmfPlusRectF dikdörtgenini alır veya ayarlar. Bu dönüşüm, DestRect'e uygulandığında SrcRect sonucunu verir.

Değer: Kaynak dikdörtgen.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


DestRect ile birlikte konteyner için bir dönüşüm belirten bir EmfPlusRectF dikdörtgenini alır veya ayarlar. Bu dönüşüm, DestRect'e uygulandığında SrcRect sonucunu verir.

Değer: Kaynak dikdörtgen.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Grafik durum konteyneriyle ilişkilendirilecek bir dizini belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. Dizine, grafik durum konteynerini kapatmak için sonraki bir EmfPlusEndContainer kaydı (bölüm 2.3.7.3) tarafından başvurulMASI GEREKİR.

Değer: Yığının dizini.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Grafik durum konteyneriyle ilişkilendirilecek bir dizini belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. Dizine, grafik durum konteynerini kapatmak için sonraki bir EmfPlusEndContainer kaydı (bölüm 2.3.7.3) tarafından başvurulMASI GEREKİR.

Değer: Yığının dizini.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

