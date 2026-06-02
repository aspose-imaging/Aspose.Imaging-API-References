---
title: "EmfPlusBrightnessContrastEffect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BrightnessContrastEffect nesnesi, bir görüntünün en açık ve en karanlık alanlarının genişlemesini veya daralmasını belirtir."
type: docs
weight: 23
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

BrightnessContrastEffect nesnesi, bir görüntünün en açık ve en karanlık alanlarının genişlemesini veya daralmasını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | Parlaklık seviyesini belirten 32-bit işaretli bir tam sayıyı alır veya ayarlar. |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | Parlaklık seviyesini belirten 32-bit işaretli bir tam sayıyı alır veya ayarlar. |
| [getContrastLevel()](#getContrastLevel--) | Kontrast seviyesini belirten 32-bit işaretli bir tam sayıyı alır veya ayarlar. |
| [setContrastLevel(int value)](#setContrastLevel-int-) | Kontrast seviyesini belirten 32-bit işaretli bir tam sayıyı alır veya ayarlar. |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


Parlaklık seviyesini belirten 32 bit işaretli bir tamsayıyı alır veya ayarlar. Bu değer MUTLAKA -255 ile 255 arasında olmalıdır, etkileri aşağıdaki gibidir: -255 \\u2264 değer < 0 Değer azaldıkça, görüntünün parlaklığı AZALMALIdır. 0 Değer 0, parlaklığın MUTLAKA değişmemesi gerektiğini belirtir. 0 < değer \\u2264 255 Değer arttıkça, görüntünün parlaklığı ARTMALIdır.

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


Parlaklık seviyesini belirten 32 bit işaretli bir tamsayıyı alır veya ayarlar. Bu değer MUTLAKA -255 ile 255 arasında olmalıdır, etkileri aşağıdaki gibidir: -255 \\u2264 değer < 0 Değer azaldıkça, görüntünün parlaklığı AZALMALIdır. 0 Değer 0, parlaklığın MUTLAKA değişmemesi gerektiğini belirtir. 0 < değer \\u2264 255 Değer arttıkça, görüntünün parlaklığı ARTMALIdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


Kontrast seviyesini belirten 32 bit işaretli bir tamsayıyı alır veya ayarlar. Bu değer MUTLAKA -100 ile 100 arasında olmalıdır, etkileri aşağıdaki gibidir: -100 \\u2264 değer < 0 Değer azaldıkça, görüntünün kontrastı AZALMALIdır. 0 Değer 0, kontrastın MUTLAKA değişmemesi gerektiğini belirtir. 0 < değer \\u2264 100 Değer arttıkça, görüntünün kontrastı ARTMALIdır.

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


Kontrast seviyesini belirten 32 bit işaretli bir tamsayıyı alır veya ayarlar. Bu değer MUTLAKA -100 ile 100 arasında olmalıdır, etkileri aşağıdaki gibidir: -100 \\u2264 değer < 0 Değer azaldıkça, görüntünün kontrastı AZALMALIdır. 0 Değer 0, kontrastın MUTLAKA değişmemesi gerektiğini belirtir. 0 < değer \\u2264 100 Değer arttıkça, görüntünün kontrastı ARTMALIdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

