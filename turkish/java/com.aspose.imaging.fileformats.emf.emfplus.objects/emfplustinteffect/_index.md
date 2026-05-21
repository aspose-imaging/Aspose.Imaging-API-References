---
title: "EmfPlusTintEffect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "TintEffect nesnesi, bir görüntüde belirtilen bir ton için siyah veya beyaz eklenmesini belirtir."
type: docs
weight: 79
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

TintEffect nesnesi, bir görüntüde belirtilen bir ton için siyah veya beyaz eklenmesini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHue()](#getHue--) | Alır veya ayarlar, renk tonu etkisinin uygulandığı tonu belirten 32 bit işaretli bir tam sayıyı. |
| [setHue(int value)](#setHue-int-) | Alır veya ayarlar, renk tonu etkisinin uygulandığı tonu belirten 32 bit işaretli bir tam sayıyı. |
| [getAmount()](#getAmount--) | Alır veya ayarlar, tonun ne kadar güçlendirildiğini veya zayıflatıldığını belirten 32 bit işaretli bir tam sayıyı. |
| [setAmount(int value)](#setAmount-int-) | Alır veya ayarlar, tonun ne kadar güçlendirildiğini veya zayıflatıldığını belirten 32 bit işaretli bir tam sayıyı. |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


Alır veya ayarlar, renk tonu etkisinin uygulandığı tonu belirten 32 bit işaretli bir tam sayı. -180 \\u2264 değer < 0 Renk çarkının mavi renginden başlayarak belirtilen saat yönünün tersine dönüşündeki renk. 0 Değer 0, renk çarkında mavi rengi belirtir. 0 < değer \\u2264 180 Renk çarkının mavi renginden başlayarak belirtilen saat yönündeki dönüşündeki renk.

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


Alır veya ayarlar, renk tonu etkisinin uygulandığı tonu belirten 32 bit işaretli bir tam sayı. -180 \\u2264 değer < 0 Renk çarkının mavi renginden başlayarak belirtilen saat yönünün tersine dönüşündeki renk. 0 Değer 0, renk çarkında mavi rengi belirtir. 0 < değer \\u2264 180 Renk çarkının mavi renginden başlayarak belirtilen saat yönündeki dönüşündeki renk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


Alır veya ayarlar, tonun ne kadar güçlendirildiğini veya zayıflatıldığını belirten 32 bit işaretli bir tam sayı. -100 \\u2264 değer < 0 Negatif değerler tonun ne kadar zayıflatıldığını belirtir, bu siyah eklenmesine eşittir. 0 Değer 0, renk tonunun DEĞİŞMEMESİ gerektiğini belirtir. 0 < değer \\u2264 100 Pozitif değerler tonun ne kadar güçlendirildiğini belirtir, bu beyaz eklenmesine eşittir.

Değer: Miktar.

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


Alır veya ayarlar, tonun ne kadar güçlendirildiğini veya zayıflatıldığını belirten 32 bit işaretli bir tam sayı. -100 \\u2264 değer < 0 Negatif değerler tonun ne kadar zayıflatıldığını belirtir, bu siyah eklenmesine eşittir. 0 Değer 0, renk tonunun DEĞİŞMEMESİ gerektiğini belirtir. 0 < değer \\u2264 100 Pozitif değerler tonun ne kadar güçlendirildiğini belirtir, bu beyaz eklenmesine eşittir.

Değer: Miktar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

