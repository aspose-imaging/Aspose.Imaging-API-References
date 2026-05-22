---
title: "EmfPlusCustomLineCapData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusCustomLineCapData nesnesi, özel bir çizgi ucu için varsayılan verileri belirtir."
type: docs
weight: 36
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

EmfPlusCustomLineCapData nesnesi, özel bir çizgi ucu için varsayılan verileri belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | Alır veya ayarlar, OptionalData alanındaki veriyi belirten 32 bit işaretsiz tam sayı. |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | Alır veya ayarlar, OptionalData alanındaki veriyi belirten 32 bit işaretsiz tam sayı. |
| [getBaseCap()](#getBaseCap--) | Alır veya ayarlar, özel çizgi kapağının dayandığı LineCap numaralandırmasından (bölüm 2.1.1.18) değeri belirten 32 bit işaretsiz tam sayı. |
| [setBaseCap(int value)](#setBaseCap-int-) | Alır veya ayarlar, özel çizgi kapağının dayandığı LineCap numaralandırmasından (bölüm 2.1.1.18) değeri belirten 32 bit işaretsiz tam sayı. |
| [getBaseInset()](#getBaseInset--) | Alır veya ayarlar, çizgi kapağının başlangıcı ile çizginin sonu arasındaki mesafeyi belirten 32 bit kayan nokta değerini. |
| [setBaseInset(float value)](#setBaseInset-float-) | Alır veya ayarlar, çizgi kapağının başlangıcı ile çizginin sonu arasındaki mesafeyi belirten 32 bit kayan nokta değerini. |
| [getStrokeStartCap()](#getStrokeStartCap--) | Alır veya ayarlar, çizilecek çizginin başlangıcında kullanılan çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32 bit işaretsiz tam sayı. |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | Alır veya ayarlar, çizilecek çizginin başlangıcında kullanılan çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32 bit işaretsiz tam sayı. |
| [getStrokeEndCap()](#getStrokeEndCap--) | Alır veya ayarlar, çizilecek çizginin sonunda kullanılacak çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32 bit işaretsiz tam sayı. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | Alır veya ayarlar, çizilecek çizginin sonunda kullanılacak çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32 bit işaretsiz tam sayı. |
| [getStrokeJoin()](#getStrokeJoin--) | Alır veya ayarlar, aynı kalemle çizilen ve uçları buluşan iki çizgiyi nasıl birleştirileceğini belirten LineJoin numaralandırmasındaki (bölüm 2.1.1.19) değeri belirten 32 bit işaretsiz tam sayı. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Alır veya ayarlar, aynı kalemle çizilen ve uçları buluşan iki çizgiyi nasıl birleştirileceğini belirten LineJoin numaralandırmasındaki (bölüm 2.1.1.19) değeri belirten 32 bit işaretsiz tam sayı. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | Alır veya ayarlar, mitre köşesindeki birleşim kalınlığı sınırını, mitre uzunluğunun çizgi genişliğine izin verilen maksimum oranını ayarlayarak içeren 32 bit kayan nokta değerini. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | Alır veya ayarlar, mitre köşesindeki birleşim kalınlığı sınırını, mitre uzunluğunun çizgi genişliğine izin verilen maksimum oranını ayarlayarak içeren 32 bit kayan nokta değerini. |
| [getWidthScale()](#getWidthScale--) | Çizgileri çizmek için kullanılan EmfPlusPen nesnesinin (bölüm 2.2.1.7) genişliğine göre özel çizgi ucunu ölçeklendirme miktarını belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setWidthScale(float value)](#setWidthScale-float-) | Çizgileri çizmek için kullanılan EmfPlusPen nesnesinin (bölüm 2.2.1.7) genişliğine göre özel çizgi ucunu ölçeklendirme miktarını belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getFillHotSpot()](#getFillHotSpot--) | Şu anda kullanılmayan EmfPlusPointF nesnesini alır veya ayarlar. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Şu anda kullanılmayan EmfPlusPointF nesnesini alır veya ayarlar. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | Şu anda kullanılmayan EmfPlusPointF nesnesini alır veya ayarlar. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | Şu anda kullanılmayan EmfPlusPointF nesnesini alır veya ayarlar. |
| [getOptionalData()](#getOptionalData--) | Özel grafik çizgi ucu için ek verileri belirten isteğe bağlı EmfPlusCustomLineCapOptionalData nesnesini (bölüm 2.2.2.14) alır veya ayarlar. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | Özel grafik çizgi ucu için ek verileri belirten isteğe bağlı EmfPlusCustomLineCapOptionalData nesnesini (bölüm 2.2.2.14) alır veya ayarlar. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


Alır veya ayarlar, OptionalData alanındaki veriyi belirten 32 bit işaretsiz tam sayı.

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


Alır veya ayarlar, OptionalData alanındaki veriyi belirten 32 bit işaretsiz tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Alır veya ayarlar, özel çizgi kapağının dayandığı LineCap numaralandırmasından (bölüm 2.1.1.18) değeri belirten 32 bit işaretsiz tam sayı.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Alır veya ayarlar, özel çizgi kapağının dayandığı LineCap numaralandırmasından (bölüm 2.1.1.18) değeri belirten 32 bit işaretsiz tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Alır veya ayarlar, çizgi kapağının başlangıcı ile çizginin sonu arasındaki mesafeyi belirten 32 bit kayan nokta değerini.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Alır veya ayarlar, çizgi kapağının başlangıcı ile çizginin sonu arasındaki mesafeyi belirten 32 bit kayan nokta değerini.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


Alır veya ayarlar, çizilecek çizginin başlangıcında kullanılan çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32 bit işaretsiz tam sayı.

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


Alır veya ayarlar, çizilecek çizginin başlangıcında kullanılan çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32 bit işaretsiz tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


Alır veya ayarlar, çizilecek çizginin sonunda kullanılacak çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32 bit işaretsiz tam sayı.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


Alır veya ayarlar, çizilecek çizginin sonunda kullanılacak çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32 bit işaretsiz tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Aynı kalemle çizilen ve uçları birleşen iki çizgiyi nasıl birleştirileceğini belirten LineJoin numaralandırmasındaki (bölüm 2.1.1.19) değeri belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. İki çizgi ucunun kesişiminde, bir çizgi birleşimi bağlantıyı daha kesintisiz gösterir.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Aynı kalemle çizilen ve uçları birleşen iki çizgiyi nasıl birleştirileceğini belirten LineJoin numaralandırmasındaki (bölüm 2.1.1.19) değeri belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. İki çizgi ucunun kesişiminde, bir çizgi birleşimi bağlantıyı daha kesintisiz gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


Alır veya ayarlar, mitre köşesindeki birleşim kalınlığı sınırını, mitre uzunluğunun çizgi genişliğine izin verilen maksimum oranını ayarlayarak içeren 32 bit kayan nokta değerini.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


Alır veya ayarlar, mitre köşesindeki birleşim kalınlığı sınırını, mitre uzunluğunun çizgi genişliğine izin verilen maksimum oranını ayarlayarak içeren 32 bit kayan nokta değerini.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Çizgileri çizmek için kullanılan EmfPlusPen nesnesinin (bölüm 2.2.1.7) genişliğine göre özel çizgi ucunu ölçeklendirme miktarını belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Çizgileri çizmek için kullanılan EmfPlusPen nesnesinin (bölüm 2.2.1.7) genişliğine göre özel çizgi ucunu ölçeklendirme miktarını belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


Şu anda kullanılmayan EmfPlusPointF nesnesini alır veya ayarlar. \{0.0, 0.0\} olarak ayarlanması ZORUNLUDUR.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


Şu anda kullanılmayan EmfPlusPointF nesnesini alır veya ayarlar. \{0.0, 0.0\} olarak ayarlanması ZORUNLUDUR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


Şu anda kullanılmayan EmfPlusPointF nesnesini alır veya ayarlar. \{0.0, 0.0\} olarak ayarlanması ZORUNLUDUR.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


Şu anda kullanılmayan EmfPlusPointF nesnesini alır veya ayarlar. \{0.0, 0.0\} olarak ayarlanması ZORUNLUDUR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


Özel grafik çizgi ucu için ek verileri belirten isteğe bağlı EmfPlusCustomLineCapOptionalData nesnesini (bölüm 2.2.2.14) alır veya ayarlar. Bu alanın belirli içeriği CustomLineCapDataFlags alanının değeriyle belirlenir.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


Özel grafik çizgi ucu için ek verileri belirten isteğe bağlı EmfPlusCustomLineCapOptionalData nesnesini (bölüm 2.2.2.14) alır veya ayarlar. Bu alanın belirli içeriği CustomLineCapDataFlags alanının değeriyle belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

