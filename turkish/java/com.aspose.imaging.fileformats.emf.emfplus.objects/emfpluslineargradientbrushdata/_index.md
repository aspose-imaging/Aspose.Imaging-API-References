---
title: "EmfPlusLinearGradientBrushData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusLinearGradientBrushData nesnesi, bir grafik fırçası için doğrusal degrade belirtir."
type: docs
weight: 53
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

EmfPlusLinearGradientBrushData nesnesi, bir grafik fırçası için doğrusal degrade belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Fırça veri bayraklarını alır veya ayarlar. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Fırça veri bayraklarını alır veya ayarlar. |
| [getEndArgb32Color()](#getEndArgb32Color--) | Bitiş rengini alır veya ayarlar. |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | Bitiş rengini alır veya ayarlar. |
| [getOptionalData()](#getOptionalData--) | İsteğe bağlı veriyi alır veya ayarlar. |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | İsteğe bağlı veriyi alır veya ayarlar. |
| [getRectF()](#getRectF--) | rect f'yi alır veya ayarlar. |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | rect f'yi alır veya ayarlar. |
| [getStartArgb32Color()](#getStartArgb32Color--) | Başlangıç rengini alır veya ayarlar. |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | Başlangıç rengini alır veya ayarlar. |
| [getWrapMode()](#getWrapMode--) | Sarım modunu alır veya ayarlar. |
| [setWrapMode(int value)](#setWrapMode-int-) | Sarım modunu alır veya ayarlar. |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Fırça veri bayraklarını alır veya ayarlar.

Değer: BrushDataFlags (4 bayt): OptionalData alanındaki verileri belirten 32 bit işaretsiz tam sayı. Bu değer `EmfPlusBrushDataFlags` (bölüm 2.1.2.1) içermelidir.

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Fırça veri bayraklarını alır veya ayarlar.

Değer: BrushDataFlags (4 bayt): OptionalData alanındaki verileri belirten 32 bit işaretsiz tam sayı. Bu değer `EmfPlusBrushDataFlags` (bölüm 2.1.2.1) içermelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


Bitiş rengini alır veya ayarlar.

Değer: Doğrusal degrade fırçasının bitiş sınır noktasındaki rengi belirten bir EmfPlusARGB nesnesi.

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


Bitiş rengini alır veya ayarlar.

Değer: Doğrusal degrade fırçasının bitiş sınır noktasındaki rengi belirten bir EmfPlusARGB nesnesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


İsteğe bağlı veriyi alır veya ayarlar.

Değer: Doğrusal degrade fırçası için ek veri belirten isteğe bağlı bir `EmfPlusLinearGradientBrushOptionalData` nesnesi (bölüm 2.2.2.25). Bu alanın belirli içeriği BrushDataFlags alanının değerine göre belirlenir.

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


İsteğe bağlı veriyi alır veya ayarlar.

Değer: Doğrusal degrade fırçası için ek veri belirten isteğe bağlı bir `EmfPlusLinearGradientBrushOptionalData` nesnesi (bölüm 2.2.2.25). Bu alanın belirli içeriği BrushDataFlags alanının değerine göre belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


rect f'yi alır veya ayarlar.

Değer: Gradient çizgisinin başlangıç ve bitiş noktalarını belirten bir EmfPlusRectF nesnesi (bölüm 2.2.2.39). Dikdörtgenin sol üst köşesi başlangıç noktası, sağ alt köşesi ise bitiş noktasıdır.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


rect f'yi alır veya ayarlar.

Değer: Gradient çizgisinin başlangıç ve bitiş noktalarını belirten bir EmfPlusRectF nesnesi (bölüm 2.2.2.39). Dikdörtgenin sol üst köşesi başlangıç noktası, sağ alt köşesi ise bitiş noktasıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


Başlangıç rengini alır veya ayarlar.

Değer: Doğrusal degrade fırçasının başlangıç sınır noktasındaki rengi belirten bir EmfPlusARGB nesnesi (bölüm 2.2.2.1).

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


Başlangıç rengini alır veya ayarlar.

Değer: Doğrusal degrade fırçasının başlangıç sınır noktasındaki rengi belirten bir EmfPlusARGB nesnesi (bölüm 2.2.2.1).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Sarım modunu alır veya ayarlar.

Değer: Brush'ın sınırının dışındaki alanın boyanıp boyanmayacağını belirten WrapMode enumarasyonundan (bölüm 2.1.1.34) 32 bit işaretli tam sayı. Sınırın dışına boyanırken, sarım modu renk geçişinin nasıl tekrarlanacağını belirtir.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Sarım modunu alır veya ayarlar.

Değer: Brush'ın sınırının dışındaki alanın boyanıp boyanmayacağını belirten WrapMode enumarasyonundan (bölüm 2.1.1.34) 32 bit işaretli tam sayı. Sınırın dışına boyanırken, sarım modu renk geçişinin nasıl tekrarlanacağını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

