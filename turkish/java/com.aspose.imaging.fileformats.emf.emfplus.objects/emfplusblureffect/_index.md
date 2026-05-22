---
title: "EmfPlusBlurEffect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BlurEffect nesnesi, bir görüntüdeki pikseller arasındaki yoğunluk farkının azalmasını belirtir."
type: docs
weight: 19
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

BlurEffect nesnesi, bir görüntüdeki pikseller arasındaki yoğunluk farkının azalmasını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 32-bit kayan noktalı bir sayı alır veya ayarlar; bu sayı piksellerdeki bulanıklık yarıçapını belirtir ve verilen pikselin yeni değerinin hesaplanmasında kullanılan piksel sayısını belirler. |
| [setBlurRadius(float value)](#setBlurRadius-float-) | 32-bit kayan noktalı bir sayı alır veya ayarlar; bu sayı piksellerdeki bulanıklık yarıçapını belirtir ve verilen pikselin yeni değerinin hesaplanmasında kullanılan piksel sayısını belirler. |
| [getExpandEdge()](#getExpandEdge--) | 32-bit Boolean değeri alır veya ayarlar; bu değer bitmap'in BlurRadius değerine eşit bir miktarda genişleyerek yumuşak kenarlar üretip üretmeyeceğini belirtir. |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | 32-bit Boolean değeri alır veya ayarlar; bu değer bitmap'in BlurRadius değerine eşit bir miktarda genişleyerek yumuşak kenarlar üretip üretmeyeceğini belirtir. |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


32-bit kayan noktalı bir sayı alır veya ayarlar; bu sayı piksellerdeki bulanıklık yarıçapını belirtir ve verilen pikselin yeni değerinin hesaplanmasında kullanılan piksel sayısını belirler. Bu değer 0.0 ile 255.0 arasında olmalıdır.

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


32-bit kayan noktalı bir sayı alır veya ayarlar; bu sayı piksellerdeki bulanıklık yarıçapını belirtir ve verilen pikselin yeni değerinin hesaplanmasında kullanılan piksel sayısını belirler. Bu değer 0.0 ile 255.0 arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


32-bit Boolean değeri alır veya ayarlar; bu değer bitmap'in BlurRadius değerine eşit bir miktarda genişleyerek yumuşak kenarlar üretip üretmeyeceğini belirtir. Bu değer aşağıdakilerden biri olmalıdır: FALSE 0x00000000 Bitmap'in boyutu DEĞİŞMEMELİ ve yumuşak kenarları BlurRadius boyutuna kırpılmalıdır. TRUE 0x00000001 Bitmap'in boyutu BlurRadius kadar genişleyerek yumuşak kenarlar üretmelidir.

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


32-bit Boolean değeri alır veya ayarlar; bu değer bitmap'in BlurRadius değerine eşit bir miktarda genişleyerek yumuşak kenarlar üretip üretmeyeceğini belirtir. Bu değer aşağıdakilerden biri olmalıdır: FALSE 0x00000000 Bitmap'in boyutu DEĞİŞMEMELİ ve yumuşak kenarları BlurRadius boyutuna kırpılmalıdır. TRUE 0x00000001 Bitmap'in boyutu BlurRadius kadar genişleyerek yumuşak kenarlar üretmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

