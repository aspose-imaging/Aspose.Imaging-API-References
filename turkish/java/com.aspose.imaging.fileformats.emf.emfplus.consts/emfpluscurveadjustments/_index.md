---
title: "EmfPlusCurveAdjustments"
second_title: "Aspose.Imaging for Java API Referansı"
description: "CurveAdjustments enumarasyonu, bir görüntünün renk eğrisine uygulanabilecek ayarlamaları tanımlar."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

CurveAdjustments enumarasyonu, bir görüntünün renk eğrisine uygulanabilecek ayarlamaları tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | Bir görüntünün pozlamasını artırma veya azaltma simülasyonunu belirtir. |
| [AdjustDensity](#AdjustDensity) | Bir görüntünün yoğunluğunu artırma veya azaltma simülasyonunu belirtir. |
| [AdjustContrast](#AdjustContrast) | Bir görüntünün kontrastını artırma veya azaltma belirtir. |
| [AdjustHighlight](#AdjustHighlight) | Bir görüntünün renk kanalının değerini artırma veya azaltma belirtir, eğer o kanal zaten yarı yoğunluğun üzerindeki bir değere sahipse. |
| [AdjustShadow](#AdjustShadow) | Bir görüntünün renk kanalının değerini artırma veya azaltma belirtir, eğer o kanal zaten yarı yoğunluğun altındaki bir değere sahipse. |
| [AdjustMidtone](#AdjustMidtone) | Bir görüntüyü aydınlatan veya karartan bir ayarlamayı belirtir. |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | Bir görüntünün beyaz doygunluğuna yapılan ayarı belirtir; bu, belirli bir renk kanalının yoğunluk aralığındaki maksimum değer olarak tanımlanır ve aralık genellikle 0 ile 255 arasındadır. |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | Bir görüntünün siyah doygunluğuna yapılan ayarı belirtir; bu, belirli bir renk kanalının yoğunluk aralığındaki minimum değer olup genellikle 0 ile 255 arasındadır. |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


Bir görüntünün pozlamasını artırma veya azaltma simülasyonunu belirtir.

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


Bir görüntünün yoğunluğunu artırma veya azaltma simülasyonunu belirtir.

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


Bir görüntünün kontrastını artırma veya azaltma belirtir.

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


Bir renk kanalının değeri zaten yarı yoğunluğun üzerindeyse, bu kanalın değerinin artırılmasını veya azaltılmasını belirtir. Bu ayar, görüntünün aydınlık bölgelerindeki tanımlamayı artırmak için, karanlık bölgeleri etkilemeden kullanılabilir.

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


Bir renk kanalının değeri zaten yarı yoğunluğun altındaysa, bu kanalın değerinin artırılmasını veya azaltılmasını belirtir. Bu ayar, görüntünün karanlık bölgelerindeki tanımlamayı artırmak için, aydınlık bölgeleri etkilemeden kullanılabilir.

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


Bir görüntüyü aydınlatan veya karartan bir ayarı belirtir. Yoğunluk aralığının ortasındaki renk kanalı değerleri, minimum veya maksimum uçlardaki değerlere göre daha fazla değiştirilir. Bu ayar, görüntünün en karanlık ve en aydınlık bölümleri arasındaki kontrastı kaybetmeden görüntüyü aydınlatmak veya karartmak için kullanılabilir.

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


Bir görüntünün beyaz doygunluğuna yapılan ayarı belirtir; bu, belirli bir renk kanalının yoğunluk aralığındaki maksimum değer olarak tanımlanır ve aralık genellikle 0 ile 255 arasındadır.

--------------------

Örneğin, 240 değerindeki bir beyaz doygunluk ayarı, 0 ile 240 arasındaki renk kanalı değerlerinin 0 ile 255 aralığına yayılacak şekilde ayarlandığını, 240'tan büyük renk kanalı değerlerinin ise 255 olarak ayarlandığını belirtir.

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


Bir görüntünün siyah doygunluğuna yapılan ayarı belirtir; bu, belirli bir renk kanalının yoğunluk aralığındaki minimum değer olup genellikle 0 ile 255 arasındadır.

--------------------

Örneğin, 15 değerindeki bir siyah doygunluk ayarı, 15 ile 255 arasındaki renk kanalı değerlerinin 0 ile 255 aralığına yayılacak şekilde ayarlandığını, 15'ten düşük renk kanalı değerlerinin ise 0 olarak ayarlandığını belirtir.

