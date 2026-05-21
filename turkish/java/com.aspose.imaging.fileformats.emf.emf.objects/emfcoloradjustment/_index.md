---
title: "EmfColorAdjustment"
second_title: "Aspose.Imaging for Java API Referansı"
description: "ColorAdjustment nesnesi, bit-blok transferlerinde kaynak bitmaplerde renkleri ayarlamak için değerleri tanımlar."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfColorAdjustment extends EmfObject
```

ColorAdjustment nesnesi, bit-blok transferlerinde kaynak bitmaplerde renkleri ayarlamak için değerleri tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfColorAdjustment()](#EmfColorAdjustment--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Bu nesnenin bayt cinsinden boyutunu belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setSize(short value)](#setSize-short-) | Bu nesnenin bayt cinsinden boyutunu belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getValues()](#getValues--) | Çıktı görüntüsünün nasıl hazırlanacağını belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setValues(int value)](#setValues-int-) | Çıktı görüntüsünün nasıl hazırlanacağını belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getIlluminantIndex()](#getIlluminantIndex--) | Görüntünün görüntülendiği standart ışık kaynağı türünü, Illuminant enumarasyonundan (bölüm 2.1.19) belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setIlluminantIndex(int value)](#setIlluminantIndex-int-) | Görüntünün görüntülendiği standart ışık kaynağı türünü, Illuminant enumarasyonundan (bölüm 2.1.19) belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getRedGamma()](#getRedGamma--) | Kaynak renklerin kırmızı birincil bileşeni için n'inci dereceden gama düzeltme değerini belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setRedGamma(short value)](#setRedGamma-short-) | Kaynak renklerin kırmızı birincil bileşeni için n'inci dereceden gama düzeltme değerini belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getGreenGamma()](#getGreenGamma--) | Kaynak renklerin yeşil birincil bileşeni için n'inci dereceden gama düzeltme değerini belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setGreenGamma(short value)](#setGreenGamma-short-) | Kaynak renklerin yeşil birincil bileşeni için n'inci dereceden gama düzeltme değerini belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getBlueGamma()](#getBlueGamma--) | Kaynak renklerin mavi birincil bileşeni için n'inci dereceden gama düzeltme değerini belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setBlueGamma(short value)](#setBlueGamma-short-) | Kaynak renklerin mavi birincil bileşeni için n'inci dereceden gama düzeltme değerini belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getReferenceBlack()](#getReferenceBlack--) | Kaynak renkler için siyah referansını belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setReferenceBlack(short value)](#setReferenceBlack-short-) | Kaynak renkler için siyah referansını belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getReferenceWhite()](#getReferenceWhite--) | Kaynak renkler için beyaz referansını belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setReferenceWhite(short value)](#setReferenceWhite-short-) | Kaynak renkler için beyaz referansını belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getContrast()](#getContrast--) | Kaynak nesneye uygulanacak kontrast miktarını belirten 16-bit işaretli tamsayıyı alır veya ayarlar. |
| [setContrast(short value)](#setContrast-short-) | Kaynak nesneye uygulanacak kontrast miktarını belirten 16-bit işaretli tamsayıyı alır veya ayarlar. |
| [getBrightness()](#getBrightness--) | Kaynak nesneye uygulanacak parlaklık miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. |
| [setBrightness(short value)](#setBrightness-short-) | Kaynak nesneye uygulanacak parlaklık miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. |
| [getColorfullness()](#getColorfullness--) | Kaynak nesneye uygulanacak renk doygunluğu miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. |
| [setColorfullness(short value)](#setColorfullness-short-) | Kaynak nesneye uygulanacak renk doygunluğu miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. |
| [getRedGreenTint()](#getRedGreenTint--) | Kaynak nesneye uygulanacak kırmızı veya yeşil ton ayarı miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. |
| [setRedGreenTint(short value)](#setRedGreenTint-short-) | Kaynak nesneye uygulanacak kırmızı veya yeşil ton ayarı miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. |
### EmfColorAdjustment() {#EmfColorAdjustment--}
```
public EmfColorAdjustment()
```


### getSize() {#getSize--}
```
public short getSize()
```


Bu nesnenin bayt cinsinden boyutunu belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu 0x0018 olmalıdır.

**Returns:**
short
### setSize(short value) {#setSize-short-}
```
public void setSize(short value)
```


Bu nesnenin bayt cinsinden boyutunu belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu 0x0018 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getValues() {#getValues--}
```
public int getValues()
```


Çıktı görüntüsünün nasıl hazırlanacağını belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu alan NULL olarak veya ColorAdjustment numaralandırmasındaki (bölüm 2.1.5) herhangi bir değer kombinasyonu olarak ayarlanabilir.

**Returns:**
int
### setValues(int value) {#setValues-int-}
```
public void setValues(int value)
```


Çıktı görüntüsünün nasıl hazırlanacağını belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu alan NULL olarak veya ColorAdjustment numaralandırmasındaki (bölüm 2.1.5) herhangi bir değer kombinasyonu olarak ayarlanabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getIlluminantIndex() {#getIlluminantIndex--}
```
public int getIlluminantIndex()
```


Görüntünün görüntülendiği standart ışık kaynağı türünü, Illuminant enumarasyonundan (bölüm 2.1.19) belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setIlluminantIndex(int value) {#setIlluminantIndex-int-}
```
public void setIlluminantIndex(int value)
```


Görüntünün görüntülendiği standart ışık kaynağı türünü, Illuminant enumarasyonundan (bölüm 2.1.19) belirten 16-bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRedGamma() {#getRedGamma--}
```
public short getRedGamma()
```


Kaynak renklerin kırmızı birincil rengi için n'inci dereceden gama düzeltme değerini belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 2.500 ile 65.000 arasında olmalıdır. 10.000 değeri gama düzeltmesinin YAPILMAMASI gerektiğini gösterir.

**Returns:**
short
### setRedGamma(short value) {#setRedGamma-short-}
```
public void setRedGamma(short value)
```


Kaynak renklerin kırmızı birincil rengi için n'inci dereceden gama düzeltme değerini belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 2.500 ile 65.000 arasında olmalıdır. 10.000 değeri gama düzeltmesinin YAPILMAMASI gerektiğini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getGreenGamma() {#getGreenGamma--}
```
public short getGreenGamma()
```


Kaynak renklerin yeşil birincil rengi için n'inci dereceden gama düzeltme değerini belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 2.500 ile 65.000 arasında olmalıdır. 10.000 değeri gama düzeltmesinin YAPILMAMASI gerektiğini gösterir.

**Returns:**
short
### setGreenGamma(short value) {#setGreenGamma-short-}
```
public void setGreenGamma(short value)
```


Kaynak renklerin yeşil birincil rengi için n'inci dereceden gama düzeltme değerini belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 2.500 ile 65.000 arasında olmalıdır. 10.000 değeri gama düzeltmesinin YAPILMAMASI gerektiğini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getBlueGamma() {#getBlueGamma--}
```
public short getBlueGamma()
```


Kaynak renklerin mavi birincil rengi için n'inci dereceden gama düzeltme değerini belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 2.500 ile 65.000 arasında olmalıdır. 10.000 değeri gama düzeltmesinin YAPILMAMASI gerektiğini gösterir.

**Returns:**
short
### setBlueGamma(short value) {#setBlueGamma-short-}
```
public void setBlueGamma(short value)
```


Kaynak renklerin mavi birincil rengi için n'inci dereceden gama düzeltme değerini belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 2.500 ile 65.000 arasında olmalıdır. 10.000 değeri gama düzeltmesinin YAPILMAMASI gerektiğini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getReferenceBlack() {#getReferenceBlack--}
```
public short getReferenceBlack()
```


Kaynak renkler için siyah referansını belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bundan daha koyu olan renkler siyah olarak kabul edilir. Bu değer 0 ile 4.000 arasında olmalıdır.

**Returns:**
short
### setReferenceBlack(short value) {#setReferenceBlack-short-}
```
public void setReferenceBlack(short value)
```


Kaynak renkler için siyah referansını belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bundan daha koyu olan renkler siyah olarak kabul edilir. Bu değer 0 ile 4.000 arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getReferenceWhite() {#getReferenceWhite--}
```
public short getReferenceWhite()
```


Kaynak renkler için beyaz referansını belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bundan daha açık renkler beyaz olarak kabul edilir. Bu değer 6.000 ile 10.000 arasında olmalıdır.

**Returns:**
short
### setReferenceWhite(short value) {#setReferenceWhite-short-}
```
public void setReferenceWhite(short value)
```


Kaynak renkler için beyaz referansını belirten 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bundan daha açık renkler beyaz olarak kabul edilir. Bu değer 6.000 ile 10.000 arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getContrast() {#getContrast--}
```
public short getContrast()
```


Kaynak nesneye uygulanacak kontrast miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. Bu değer –100 ile 100 arasında olmalıdır. Sıfır değeri kontrast ayarının YAPILMAMASI gerektiğini gösterir.

**Returns:**
short
### setContrast(short value) {#setContrast-short-}
```
public void setContrast(short value)
```


Kaynak nesneye uygulanacak kontrast miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. Bu değer –100 ile 100 arasında olmalıdır. Sıfır değeri kontrast ayarının YAPILMAMASI gerektiğini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getBrightness() {#getBrightness--}
```
public short getBrightness()
```


Kaynak nesneye uygulanacak parlaklık miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. Bu değer –100 ile 100 arasında olmalıdır. Sıfır değeri parlaklık ayarının YAPILMAMASI gerektiğini gösterir.

**Returns:**
short
### setBrightness(short value) {#setBrightness-short-}
```
public void setBrightness(short value)
```


Kaynak nesneye uygulanacak parlaklık miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. Bu değer –100 ile 100 arasında olmalıdır. Sıfır değeri parlaklık ayarının YAPILMAMASI gerektiğini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getColorfullness() {#getColorfullness--}
```
public short getColorfullness()
```


Kaynak nesneye uygulanacak renk doygunluğu miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. Bu değer –100 ile 100 arasında olmalıdır. Sıfır değeri renk doygunluğu ayarının YAPILMAMASI gerektiğini gösterir.

**Returns:**
short
### setColorfullness(short value) {#setColorfullness-short-}
```
public void setColorfullness(short value)
```


Kaynak nesneye uygulanacak renk doygunluğu miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. Bu değer –100 ile 100 arasında olmalıdır. Sıfır değeri renk doygunluğu ayarının YAPILMAMASI gerektiğini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getRedGreenTint() {#getRedGreenTint--}
```
public short getRedGreenTint()
```


Kaynak nesneye uygulanacak kırmızı veya yeşil ton ayarı miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. Bu değer –100 ile 100 arasında olmalıdır. Pozitif sayılar kırmızıya, negatif sayılar yeşile doğru ayar yapar. Sıfır değeri ton ayarının YAPILMAMASI gerektiğini gösterir.

**Returns:**
short
### setRedGreenTint(short value) {#setRedGreenTint-short-}
```
public void setRedGreenTint(short value)
```


Kaynak nesneye uygulanacak kırmızı veya yeşil ton ayarı miktarını belirten 16 bit işaretli tam sayıyı alır veya ayarlar. Bu değer –100 ile 100 arasında olmalıdır. Pozitif sayılar kırmızıya, negatif sayılar yeşile doğru ayar yapar. Sıfır değeri ton ayarının YAPILMAMASI gerektiğini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

