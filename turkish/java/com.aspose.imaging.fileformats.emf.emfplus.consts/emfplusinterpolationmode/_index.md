---
title: "EmfPlusInterpolationMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "InterpolationMode sayımı, germe ve küçültme dahil ölçeklendirme yollarını tanımlar."
type: docs
weight: 29
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

InterpolationMode sayımı, germe ve küçültme dahil olmak üzere ölçeklendirme yöntemlerini tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | Varsayılan ara değerleme modunu, InterpolationModeBilinear olarak tanımlandığını belirtir. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | Düşük kaliteli bir ara değerleme modunu, InterpolationModeNearestNeighbor olarak tanımlandığını belirtir. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | Yüksek kaliteli bir ara değerleme modunu, InterpolationModeHighQualityBicubic olarak tanımlandığını belirtir. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | Bilinear ara değerlemeyi, ara değerlenen pikselin etrafındaki en yakın 2x2 bilinen piksel komşuluğunu kullandığını belirtir. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | Bicubic interpolasyonu belirtir; bu, ara değerli pikselin etrafındaki bilinen piksellerin en yakın 4x4 komşuluğunu kullanır. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | En yakın komşu interpolasyonunu belirtir; bu, ara değerli piksele en yakın pikselin değerini yalnızca kullanır. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | Ön filtrelemeli bilinear interpolasyonu belirtir. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | Ön filtrelemeli bicubic interpolasyonu belirtir; bu, bu seçenekler arasında en yüksek kaliteyi üretir. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


Varsayılan ara değerleme modunu, InterpolationModeBilinear olarak tanımlandığını belirtir.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


Düşük kaliteli bir ara değerleme modunu, InterpolationModeNearestNeighbor olarak tanımlandığını belirtir.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


Yüksek kaliteli bir ara değerleme modunu, InterpolationModeHighQualityBicubic olarak tanımlandığını belirtir.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


Bilinear interpolasyonu belirtir; bu, ara değerli pikselin etrafındaki bilinen piksellerin en yakın 2x2 komşuluğunu kullanır. Bu 4 bilinen piksel değerinin ağırlıklı ortalaması, ara değere atanacak değeri belirler. Sonuç, InterpolationModeNearestNeighbor'dan daha pürüzsüz görünür.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


Bicubic interpolasyonu belirtir; bu, ara değerli pikselin etrafındaki bilinen piksellerin en yakın 4x4 komşuluğunu kullanır. Bu 16 bilinen piksel değerinin ağırlıklı ortalaması, ara değere atanacak değeri belirler. Bilinen piksellerin ara değere olan mesafeleri değişebileceği için, daha yakın piksellere hesaplamada daha yüksek ağırlık verilir. Sonuç, InterpolationModeBilinear'dan daha pürüzsüz görünür.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


En yakın komşu interpolasyonunu belirtir; bu, ara değerli piksele en yakın pikselin değerini yalnızca kullanır. Bu mod, pikselleri basitçe çoğaltır veya kaldırır ve bu seçenekler arasında en düşük kaliteyi üretir.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


Ön filtrelemeli bilinear interpolasyonu belirtir.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


Ön filtrelemeli bicubic interpolasyonu belirtir; bu, bu seçenekler arasında en yüksek kaliteyi üretir.

