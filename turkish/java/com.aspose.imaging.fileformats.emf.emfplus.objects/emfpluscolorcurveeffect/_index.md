---
title: "EmfPlusColorCurveEffect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "ColorCurveEffect nesnesi, bir görüntünün renk eğrisine yapılan sekiz ayardan birini belirtir."
type: docs
weight: 27
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

ColorCurveEffect nesnesi, bir görüntünün renk eğrisine yapılan sekiz ayardan birini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | Bitmap içindeki renklere uygulanacak eğri ayarını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | Bitmap içindeki renklere uygulanacak eğri ayarını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getCurveChannel()](#getCurveChannel--) | Eğri ayarının uygulanacağı renk kanalını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setCurveChannel(int value)](#setCurveChannel-int-) | Eğri ayarının uygulanacağı renk kanalını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | CurveChannel tarafından belirtilen renk kanalına yapılan eğri ayarının şiddetini belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | CurveChannel tarafından belirtilen renk kanalına yapılan eğri ayarının şiddetini belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


Bitmap içindeki renklere uygulanacak eğri ayarını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer CurveAdjustments numaralandırmasında (bölüm 2.1.1.7) tanımlanmalıdır.

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


Bitmap içindeki renklere uygulanacak eğri ayarını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer CurveAdjustments numaralandırmasında (bölüm 2.1.1.7) tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


Eğri ayarının uygulanacağı renk kanalını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer CurveChannel numaralandırmasında (bölüm 2.1.1.8) tanımlanmalıdır.

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


Eğri ayarının uygulanacağı renk kanalını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer CurveChannel numaralandırmasında (bölüm 2.1.1.8) tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


CurveChannel tarafından belirtilen renk kanalına yapılan eğri ayarının şiddetini belirten 32 bit işaretli tamsayıyı alır veya ayarlar. Bu alan için anlamlı değer aralıkları, CurveAdjustment değerine göre aşağıdaki gibi değişir: Pozlama ayar aralığı: -255 \\u2264 value < 0 Değer azaldıkça, görüntünün pozlaması AZALMALI. 0 Değeri 0, pozlamanın DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 255 Değer arttıkça, görüntünün pozlaması ARTMALI. Yoğunluk ayar aralığı: -255 \\u2264 value < 0 Değer azaldıkça, görüntünün yoğunluğu AZALMALI ve daha karanlık bir görüntü elde edilir. 0 Değeri 0, yoğunluğun DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 255 Değer arttıkça, görüntünün yoğunluğu ARTMALI. Kontrast ayar aralığı: -100 \\u2264 value < 0 Değer azaldıkça, görüntünün kontrastı AZALMALI. 0 Değeri 0, kontrastın DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 Değer arttıkça, görüntünün kontrastı ARTMALI. Vurgulama ayar aralığı: -100 \\u2264 value < 0 Değer azaldıkça, görüntünün aydınlık bölgeleri daha karanlık görünmelidir. 0 Değeri 0, vurgulamanın DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 Değer arttıkça, görüntünün aydınlık bölgeleri daha aydınlık görünmelidir. Gölge ayar aralığı: -100 \\u2264 value < 0 Değer azaldıkça, görüntünün karanlık bölgeleri daha karanlık görünmelidir. 0 Değeri 0, gölgenin DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 Değer arttıkça, görüntünün karanlık bölgeleri daha aydınlık görünmelidir. Beyaz doygunluk ayar aralığı: 0 \\u2014 255 Değer arttıkça, renk kanalı yoğunluk aralığının üst sınırı artar. Siyah doygunluk ayar aralığı: 0 \\u2014 255 Değer arttıkça, renk kanalı yoğunluk aralığının alt sınırı artar.

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


CurveChannel tarafından belirtilen renk kanalına yapılan eğri ayarının şiddetini belirten 32 bit işaretli tamsayıyı alır veya ayarlar. Bu alan için anlamlı değer aralıkları, CurveAdjustment değerine göre aşağıdaki gibi değişir: Pozlama ayar aralığı: -255 \\u2264 value < 0 Değer azaldıkça, görüntünün pozlaması AZALMALI. 0 Değeri 0, pozlamanın DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 255 Değer arttıkça, görüntünün pozlaması ARTMALI. Yoğunluk ayar aralığı: -255 \\u2264 value < 0 Değer azaldıkça, görüntünün yoğunluğu AZALMALI ve daha karanlık bir görüntü elde edilir. 0 Değeri 0, yoğunluğun DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 255 Değer arttıkça, görüntünün yoğunluğu ARTMALI. Kontrast ayar aralığı: -100 \\u2264 value < 0 Değer azaldıkça, görüntünün kontrastı AZALMALI. 0 Değeri 0, kontrastın DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 Değer arttıkça, görüntünün kontrastı ARTMALI. Vurgulama ayar aralığı: -100 \\u2264 value < 0 Değer azaldıkça, görüntünün aydınlık bölgeleri daha karanlık görünmelidir. 0 Değeri 0, vurgulamanın DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 Değer arttıkça, görüntünün aydınlık bölgeleri daha aydınlık görünmelidir. Gölge ayar aralığı: -100 \\u2264 value < 0 Değer azaldıkça, görüntünün karanlık bölgeleri daha karanlık görünmelidir. 0 Değeri 0, gölgenin DEĞİŞMEMESİ gerektiğini belirtir. 0 < value \\u2264 100 Değer arttıkça, görüntünün karanlık bölgeleri daha aydınlık görünmelidir. Beyaz doygunluk ayar aralığı: 0 \\u2014 255 Değer arttıkça, renk kanalı yoğunluk aralığının üst sınırı artar. Siyah doygunluk ayar aralığı: 0 \\u2014 255 Değer arttıkça, renk kanalı yoğunluk aralığının alt sınırı artar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

