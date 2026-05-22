---
title: "EmfPlusLevelsEffect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "LevelsEffect nesnesi bir görüntünün vurgular, orta tonları ve gölgeleri üzerindeki ayarlamaları belirtir."
type: docs
weight: 51
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

LevelsEffect nesnesi, bir görüntünün vurgular, orta tonlar ve gölgelerindeki ayarları belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHighlight()](#getHighlight--) | Bir görüntünün vurgularını ne kadar aydınlatacağını belirten değeri alır veya ayarlar. |
| [setHighlight(int value)](#setHighlight-int-) | Bir görüntünün vurgularını ne kadar aydınlatacağını belirten değeri alır veya ayarlar. |
| [getMidTone()](#getMidTone--) | Bir görüntünün orta tonlarını ne kadar aydınlatacağını veya karartacağını belirten değeri alır veya ayarlar. |
| [setMidTone(int value)](#setMidTone-int-) | Bir görüntünün orta tonlarını ne kadar aydınlatacağını veya karartacağını belirten değeri alır veya ayarlar. |
| [getShadow()](#getShadow--) | Bir görüntünün gölgelerini ne kadar karartacağını belirten değeri alır veya ayarlar. |
| [setShadow(int value)](#setShadow-int-) | Bir görüntünün gölgelerini ne kadar karartacağını belirten değeri alır veya ayarlar. |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


Bir görüntünün vurgularını ne kadar aydınlatacağını belirten değeri alır veya ayarlar. Yoğunluk aralığının yüksek ucundaki renk kanalı değerleri, orta veya düşük uçlardakilere göre daha fazla değiştirilir; bu, görüntünün karanlık bölümlerindeki kontrastı kaybetmeden aydınlatılabileceği anlamına gelir. 0 \\u2264 value < Bu eşik üzerindeki yüzde yoğunlukta vurguların artırılması GEREKİR. 100 vurguların DEĞİŞMEMESİ GEREKİR.

Değer: Vurgulama.

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


Bir görüntünün vurgularını ne kadar aydınlatacağını belirten değeri alır veya ayarlar. Yoğunluk aralığının yüksek ucundaki renk kanalı değerleri, orta veya düşük uçlardakilere göre daha fazla değiştirilir; bu, görüntünün karanlık bölümlerindeki kontrastı kaybetmeden aydınlatılabileceği anlamına gelir. 0 \\u2264 value < Bu eşik üzerindeki yüzde yoğunlukta vurguların artırılması GEREKİR. 100 vurguların DEĞİŞMEMESİ GEREKİR.

Değer: Vurgulama.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


Bir görüntünün orta tonlarını ne kadar aydınlatacağını veya karartacağını belirten değeri alır veya ayarlar. Yoğunluk aralığının ortasındaki renk kanalı değerleri, yüksek veya düşük uçlardakilere göre daha fazla değiştirilir; bu, görüntünün en karanlık ve en aydınlık bölümleri arasındaki kontrastı kaybetmeden aydınlatılıp karartılabileceği anlamına gelir. -100 \\u2264 value < 0 orta tonların karartıldığını belirtir. 0 orta tonların DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 orta tonların aydınlatıldığını belirtir.

Değer: Orta ton.

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


Bir görüntünün orta tonlarını ne kadar aydınlatacağını veya karartacağını belirten değeri alır veya ayarlar. Yoğunluk aralığının ortasındaki renk kanalı değerleri, yüksek veya düşük uçlardakilere göre daha fazla değiştirilir; bu, görüntünün en karanlık ve en aydınlık bölümleri arasındaki kontrastı kaybetmeden aydınlatılıp karartılabileceği anlamına gelir. -100 \\u2264 value < 0 orta tonların karartıldığını belirtir. 0 orta tonların DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 orta tonların aydınlatıldığını belirtir.

Değer: Orta ton.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


Bir görüntünün gölgelerini ne kadar karartacağını belirten değeri alır veya ayarlar. Yoğunluk aralığının düşük ucundaki renk kanalı değerleri, orta veya yüksek uçlardakilere göre daha fazla değiştirilir; bu, görüntünün daha aydınlık bölümlerindeki kontrastı kaybetmeden karartılabileceği anlamına gelir. 0 gölgelerin DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 bu eşik altındaki yüzde yoğunlukta gölgelerin karartılacağını belirtir.

Değer: Gölge.

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


Bir görüntünün gölgelerini ne kadar karartacağını belirten değeri alır veya ayarlar. Yoğunluk aralığının düşük ucundaki renk kanalı değerleri, orta veya yüksek uçlardakilere göre daha fazla değiştirilir; bu, görüntünün daha aydınlık bölümlerindeki kontrastı kaybetmeden karartılabileceği anlamına gelir. 0 gölgelerin DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 bu eşik altındaki yüzde yoğunlukta gölgelerin karartılacağını belirtir.

Değer: Gölge.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

