---
title: "EmfPlusPenOptionalData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusPenOptionalData nesnesi, bir grafik kalemi için isteğe bağlı verileri belirtir."
type: docs
weight: 65
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

EmfPlusPenOptionalData nesnesi, bir grafik kalemi için isteğe bağlı verileri belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Kalem için dünya uzayından aygıt uzayına dönüşümü belirten isteğe bağlı EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Kalem için dünya uzayından aygıt uzayına dönüşümü belirten isteğe bağlı EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. |
| [getStartCap()](#getStartCap--) | CustomStartCapData alanında bir çizginin başlangıç şekli belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setStartCap(int value)](#setStartCap-int-) | CustomStartCapData alanında bir çizginin başlangıç şekli belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getEndCap()](#getEndCap--) | CustomEndCapData alanında bir çizginin bitiş şekli belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setEndCap(int value)](#setEndCap-int-) | CustomEndCapData alanında bir çizginin bitiş şekli belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getJoin()](#getJoin--) | Aynı kalemle çizilen ve uçları birleşen iki çizgiyi nasıl birleştirileceğini belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setJoin(int value)](#setJoin-int-) | Aynı kalemle çizilen ve uçları birleşen iki çizgiyi nasıl birleştirileceğini belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getMiterLimit()](#getMiterLimit--) | Miter uzunluğunun çizgi genişliğine olan maksimum izin verilen oranı belirten isteğe bağlı 32 bit kayan nokta değerini alır veya ayarlar. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Miter uzunluğunun çizgi genişliğine olan maksimum izin verilen oranı belirten isteğe bağlı 32 bit kayan nokta değerini alır veya ayarlar. |
| [getLineStyle()](#getLineStyle--) | Bu kalem nesnesiyle çizilen çizgilerde kullanılan stili belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setLineStyle(int value)](#setLineStyle-int-) | Bu kalem nesnesiyle çizilen çizgilerde kullanılan stili belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getDashedLineCapType()](#getDashedLineCapType--) | Kesikli bir çizgideki her tire için her iki ucun şeklini belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | Kesikli bir çizgideki her tire için her iki ucun şeklini belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getDashOffset()](#getDashOffset--) | Kesikli çizgi deseninde bir çizginin başlangıcından ilk boşluğun başlangıcına olan mesafeyi belirten isteğe bağlı 32 bit kayan nokta değerini alır veya ayarlar. |
| [setDashOffset(float value)](#setDashOffset-float-) | Kesikli çizgi deseninde bir çizginin başlangıcından ilk boşluğun başlangıcına olan mesafeyi belirten isteğe bağlı 32 bit kayan nokta değerini alır veya ayarlar. |
| [getDashedLineData()](#getDashedLineData--) | Özel bir kesikli çizgide tire ve boşluk uzunluklarını belirten isteğe bağlı EmfPlusDashedLineData nesnesini (bölüm 2.2.2.16) alır veya ayarlar. |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | Özel bir kesikli çizgide tire ve boşluk uzunluklarını belirten isteğe bağlı EmfPlusDashedLineData nesnesini (bölüm 2.2.2.16) alır veya ayarlar. |
| [getPenAlignment()](#getPenAlignment--) | Çizilen çizginin koordinatlarına göre kalem genişliğinin dağılımını belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setPenAlignment(int value)](#setPenAlignment-int-) | Çizilen çizginin koordinatlarına göre kalem genişliğinin dağılımını belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getCompoundLineData()](#getCompoundLineData--) | Paralel çizgiler ve boşluklardan oluşan kalemin birleşik çizgisini tanımlayan kayan nokta değerleri dizisini belirten isteğe bağlı EmfPlusCompoundLineData nesnesini (bölüm 2.2.2.9) alır veya ayarlar. |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | Paralel çizgiler ve boşluklardan oluşan kalemin birleşik çizgisini tanımlayan kayan nokta değerleri dizisini belirten isteğe bağlı EmfPlusCompoundLineData nesnesini (bölüm 2.2.2.9) alır veya ayarlar. |
| [getCustomStartCapData()](#getCustomStartCapData--) | Bu kalemle çizilen bir çizginin başlangıcında kullanılacak şekli tanımlayan, özel başlangıç kapağı şeklini belirten isteğe bağlı EmfPlusCustomStartCapData nesnesini (bölüm 2.2.2.15) alır veya ayarlar. |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | Bu kalemle çizilen bir çizginin başlangıcında kullanılacak şekli tanımlayan, özel başlangıç kapağı şeklini belirten isteğe bağlı EmfPlusCustomStartCapData nesnesini (bölüm 2.2.2.15) alır veya ayarlar. |
| [getCustomEndCapData()](#getCustomEndCapData--) | Bu kalemle çizilen bir çizginin sonunda kullanılacak şekli tanımlayan, özel bitiş kapağı şeklini belirten isteğe bağlı EmfPlusCustomEndCapData nesnesini (bölüm 2.2.2.11) alır veya ayarlar. |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | Bu kalemle çizilen bir çizginin sonunda kullanılacak şekli tanımlayan, özel bitiş kapağı şeklini belirten isteğe bağlı EmfPlusCustomEndCapData nesnesini (bölüm 2.2.2.11) alır veya ayarlar. |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Kalem için dünya uzayından aygıt uzayına dönüşümü belirten isteğe bağlı EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. PenDataTransform bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa bu alan ZORUNLU olarak bulunmalıdır.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Kalem için dünya uzayından aygıt uzayına dönüşümü belirten isteğe bağlı EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. PenDataTransform bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa bu alan ZORUNLU olarak bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


CustomStartCapData alanında bir çizginin başlangıç şekli belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. PenDataStartCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa bu alan ZORUNLU olarak bulunmalıdır ve değer LineCapType sayımında (bölüm 2.1.1.18) tanımlanmalıdır.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


CustomStartCapData alanında bir çizginin başlangıç şekli belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. PenDataStartCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa bu alan ZORUNLU olarak bulunmalıdır ve değer LineCapType sayımında (bölüm 2.1.1.18) tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


CustomEndCapData alanında bir çizginin bitiş şekli belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. PenDataEndCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa bu alan ZORUNLU olarak bulunmalı ve değer LineCapType sayımında tanımlanmalıdır.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


CustomEndCapData alanında bir çizginin bitiş şekli belirten isteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar. PenDataEndCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa bu alan ZORUNLU olarak bulunmalı ve değer LineCapType sayımında tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


İsteğe bağlı 32 bit işaretli bir tam sayı alır veya ayarlar; aynı kalemle çizilen ve uçları birleşen iki çizginin nasıl birleştirileceğini belirtir. PenDataJoin bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır ve değer LineJoinType sayımında (bölüm 2.1.1.19) tanımlanmış olmalıdır.

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


İsteğe bağlı 32 bit işaretli bir tam sayı alır veya ayarlar; aynı kalemle çizilen ve uçları birleşen iki çizginin nasıl birleştirileceğini belirtir. PenDataJoin bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır ve değer LineJoinType sayımında (bölüm 2.1.1.19) tanımlanmış olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


İsteğe bağlı 32 bit kayan nokta değeri alır veya ayarlar; bu değer, birleştirme noktasındaki açı uzunluğunun çizgi genişliğine olan maksimum izin verilen oranı olan mitre sınırını belirtir. Mitre uzunluğu, birleşmenin iç tarafındaki çizgi duvarlarının kesişiminden dış tarafındaki kesişime olan mesafedir. İki çizgi arasındaki açı küçük olduğunda mitre uzunluğu büyük olabilir. PenDataMiterLimit bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


İsteğe bağlı 32 bit kayan nokta değeri alır veya ayarlar; bu değer, birleştirme noktasındaki açı uzunluğunun çizgi genişliğine olan maksimum izin verilen oranı olan mitre sınırını belirtir. Mitre uzunluğu, birleşmenin iç tarafındaki çizgi duvarlarının kesişiminden dış tarafındaki kesişime olan mesafedir. İki çizgi arasındaki açı küçük olduğunda mitre uzunluğu büyük olabilir. PenDataMiterLimit bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


İsteğe bağlı 32 bit işaretli bir tam sayı alır veya ayarlar; bu, bu kalem nesnesiyle çizilen çizgilerin kullanılan stilini belirtir. PenDataLineStyle bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır ve değer LineStyle sayımında (bölüm 2.1.1.20) tanımlanmış olmalıdır.

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


İsteğe bağlı 32 bit işaretli bir tam sayı alır veya ayarlar; bu, bu kalem nesnesiyle çizilen çizgilerin kullanılan stilini belirtir. PenDataLineStyle bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır ve değer LineStyle sayımında (bölüm 2.1.1.20) tanımlanmış olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


İsteğe bağlı 32 bit işaretli bir tam sayı alır veya ayarlar; bu, kesikli bir çizgideki her tire'nin iki ucunun şeklini belirtir. PenDataDashedLineCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır ve değer DashedLineCapType sayımında (bölüm 2.1.1.10) tanımlanmış olmalıdır.

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


İsteğe bağlı 32 bit işaretli bir tam sayı alır veya ayarlar; bu, kesikli bir çizgideki her tire'nin iki ucunun şeklini belirtir. PenDataDashedLineCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır ve değer DashedLineCapType sayımında (bölüm 2.1.1.10) tanımlanmış olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


İsteğe bağlı 32 bit kayan nokta değeri alır veya ayarlar; bu, bir çizginin başlangıcından kesikli çizgi desenindeki ilk boşluğun başlangıcına olan mesafeyi belirtir. PenDataDashedLineOffset bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır.

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


İsteğe bağlı 32 bit kayan nokta değeri alır veya ayarlar; bu, bir çizginin başlangıcından kesikli çizgi desenindeki ilk boşluğun başlangıcına olan mesafeyi belirtir. PenDataDashedLineOffset bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


İsteğe bağlı EmfPlusDashedLineData nesnesi (bölüm 2.2.2.16) alır veya ayarlar; bu, özel bir kesikli çizgideki tire ve boşluk uzunluklarını belirtir. PenDataDashedLine bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır.

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


İsteğe bağlı EmfPlusDashedLineData nesnesi (bölüm 2.2.2.16) alır veya ayarlar; bu, özel bir kesikli çizgideki tire ve boşluk uzunluklarını belirtir. PenDataDashedLine bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


İsteğe bağlı 32 bit işaretli bir tam sayı alır veya ayarlar; bu, çizilen çizginin koordinatlarına göre kalem genişliğinin dağılımını belirtir. PenDataNonCenter bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır ve değer PenAlignment sayımında (bölüm 2.1.1.24) tanımlanmış olmalıdır.

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


İsteğe bağlı 32 bit işaretli bir tam sayı alır veya ayarlar; bu, çizilen çizginin koordinatlarına göre kalem genişliğinin dağılımını belirtir. PenDataNonCenter bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır ve değer PenAlignment sayımında (bölüm 2.1.1.24) tanımlanmış olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


İsteğe bağlı EmfPlusCompoundLineData nesnesi (bölüm 2.2.2.9) alır veya ayarlar; bu, paralel çizgiler ve boşluklardan oluşan kalemin bileşik çizgisini tanımlayan kayan nokta değerleri dizisini belirtir. PenDataCompoundLine bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


İsteğe bağlı EmfPlusCompoundLineData nesnesi (bölüm 2.2.2.9) alır veya ayarlar; bu, paralel çizgiler ve boşluklardan oluşan kalemin bileşik çizgisini tanımlayan kayan nokta değerleri dizisini belirtir. PenDataCompoundLine bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


İsteğe bağlı EmfPlusCustomStartCapData nesnesi (bölüm 2.2.2.15) alır veya ayarlar; bu, bu kalemle çizilen bir çizginin başlangıcında kullanılacak özel başlangıç kapağı şeklini tanımlar. Kare, daire veya elmas gibi çeşitli şekillerden biri olabilir. PenDataCustomStartCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


İsteğe bağlı EmfPlusCustomStartCapData nesnesi (bölüm 2.2.2.15) alır veya ayarlar; bu, bu kalemle çizilen bir çizginin başlangıcında kullanılacak özel başlangıç kapağı şeklini tanımlar. Kare, daire veya elmas gibi çeşitli şekillerden biri olabilir. PenDataCustomStartCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


İsteğe bağlı EmfPlusCustomEndCapData nesnesi (bölüm 2.2.2.11) alır veya ayarlar; bu, bu kalemle çizilen bir çizginin sonunda kullanılacak özel bitiş kapağı şeklini tanımlar. Kare, daire veya elmas gibi çeşitli şekillerden biri olabilir. PenDataCustomEndCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


İsteğe bağlı EmfPlusCustomEndCapData nesnesi (bölüm 2.2.2.11) alır veya ayarlar; bu, bu kalemle çizilen bir çizginin sonunda kullanılacak özel bitiş kapağı şeklini tanımlar. Kare, daire veya elmas gibi çeşitli şekillerden biri olabilir. PenDataCustomEndCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan ZORUNLU olarak bulunmalıdır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

