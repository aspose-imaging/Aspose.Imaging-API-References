---
title: "EmfPlusRedEyeCorrectionEffect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "RedEyeCorrectionEffect nesnesi, kırmızı göz düzeltmesinin uygulandığı bir görüntünün alanlarını belirtir."
type: docs
weight: 67
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

RedEyeCorrectionEffect nesnesi, kırmızı göz düzeltmesinin uygulandığı bir görüntünün alanlarını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | Areas alanındaki dikdörtgen sayısını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | Areas alanındaki dikdörtgen sayısını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getAreas()](#getAreas--) | NumberOfAreas WMF RectL nesnelerinin bir dizisini ([MS-WMF] bölüm 2.2.2.19'da belirtilen) alır veya ayarlar. |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | NumberOfAreas WMF RectL nesnelerinin bir dizisini ([MS-WMF] bölüm 2.2.2.19'da belirtilen) alır veya ayarlar. |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


Areas alanındaki dikdörtgen sayısını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

Değer: Alan sayısı.

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


Areas alanındaki dikdörtgen sayısını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

Değer: Alan sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


Alır veya ayarlar NumberOfAreas WMF RectL nesnelerinin bir dizisini, [MS-WMF] bölüm 2.2.2.19'da belirtilen. Her dikdörtgen, kırmızı göz düzeltme etkisinin UYGULANMASI GEREKEN bitmap görüntüsünün bir alanını belirtir.

Değer: Alanlar.

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


Alır veya ayarlar NumberOfAreas WMF RectL nesnelerinin bir dizisini, [MS-WMF] bölüm 2.2.2.19'da belirtilen. Her dikdörtgen, kırmızı göz düzeltme etkisinin UYGULANMASI GEREKEN bitmap görüntüsünün bir alanını belirtir.

Değer: Alanlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

