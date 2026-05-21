---
title: "EmfPlusSharpenEffect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "SharpenEffect nesnesi, bir görüntüdeki pikseller arasındaki yoğunluk farkının artmasını belirtir."
type: docs
weight: 72
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

SharpenEffect nesnesi, bir görüntüdeki pikseller arasındaki yoğunluk farkının artmasını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Alır veya ayarlar piksellerde keskinleştirme yarıçapını belirten 32-bit kayan nokta sayısını, bu sayı verilen bir pikselin yeni değerinin hesaplanmasında kullanılan piksel sayısını belirler. |
| [setRadius(float value)](#setRadius-float-) | Alır veya ayarlar piksellerde keskinleştirme yarıçapını belirten 32-bit kayan nokta sayısını, bu sayı verilen bir pikselin yeni değerinin hesaplanmasında kullanılan piksel sayısını belirler. |
| [getAmount()](#getAmount--) | Alır veya ayarlar verilen bir piksel ile çevresindeki pikseller arasındaki yoğunluk farkını belirten 32-bit kayan nokta sayısını. |
| [setAmount(float value)](#setAmount-float-) | Alır veya ayarlar verilen bir piksel ile çevresindeki pikseller arasındaki yoğunluk farkını belirten 32-bit kayan nokta sayısını. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


Alır veya ayarlar piksellerde keskinleştirme yarıçapını belirten 32-bit kayan nokta sayısını, bu sayı verilen bir pikselin yeni değerinin hesaplanmasında kullanılan piksel sayısını belirler. Bu değer arttıkça, hesaplamada kullanılan piksel sayısı artar ve ortaya çıkan bitmap daha keskin OLMAK ZORUNDADIR.

Değer: Yarıçap.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


Alır veya ayarlar piksellerde keskinleştirme yarıçapını belirten 32-bit kayan nokta sayısını, bu sayı verilen bir pikselin yeni değerinin hesaplanmasında kullanılan piksel sayısını belirler. Bu değer arttıkça, hesaplamada kullanılan piksel sayısı artar ve ortaya çıkan bitmap daha keskin OLMAK ZORUNDADIR.

Değer: Yarıçap.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


Alır veya ayarlar verilen bir piksel ile çevresindeki pikseller arasındaki yoğunluk farkını belirten 32-bit kayan nokta sayısını. 0, keskinleştirmenin YAPILMAMASI gerektiğini belirtir. 0 < değer \\u2264 100 Bu değer arttıkça, pikseller arasındaki yoğunluk farkı ARTMALIdır.

Değer: Miktar.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


Alır veya ayarlar verilen bir piksel ile çevresindeki pikseller arasındaki yoğunluk farkını belirten 32-bit kayan nokta sayısını. 0, keskinleştirmenin YAPILMAMASI gerektiğini belirtir. 0 < değer \\u2264 100 Bu değer arttıkça, pikseller arasındaki yoğunluk farkı ARTMALIdır.

Değer: Miktar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

