---
title: "EmfPlusInterpolationMode Sıralaması"
type: docs
weight: 200
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

InterpolationMode sayımı, germe ve küçültme dahil olmak üzere ölçeklendirme yöntemlerini tanımlar.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | Bikübik enterpolasyonu belirtir; bu, ara değerli pikselin etrafındaki en yakın 4x4 komşu bilinen pikseli kullanır. Bu 16 bilinen piksel değerinin ağırlıklı ortalaması, ara değerli piksele atanacak değeri belirler. Bilinen piksellerin ara değere olan mesafeleri farklı olabileceği için, daha yakın piksellere hesaplamada daha yüksek ağırlık verilir. Sonuç, InterpolationModeBilinear'dan daha pürüzsüz görünür. |
| INTERPOLATION_MODE_BILINEAR | Bilineer enterpolasyonu belirtir; bu, ara değerli pikselin etrafındaki en yakın 2x2 komşu bilinen pikseli kullanır. Bu 4 bilinen piksel değerinin ağırlıklı ortalaması, ara değerli piksele atanacak değeri belirler. Sonuç, InterpolationModeNearestNeighbor'dan daha pürüzsüz görünür. |
| INTERPOLATION_MODE_DEFAULT | Varsayılan enterpolasyon modunu belirtir; bu, InterpolationModeBilinear olarak tanımlanmıştır. |
| INTERPOLATION_MODE_HIGH_QUALITY | Yüksek kaliteli bir ara değerleme modunu belirtir, bu mod InterpolationModeHighQualityBicubic olarak tanımlanır. |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | Ön filtreleme ile bikübik ara değerlemeyi belirtir; bu seçenekler arasında en yüksek kaliteli sonucu üretir. |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | Ön filtreleme ile ikili ara değerlemeyi belirtir. |
| INTERPOLATION_MODE_LOW_QUALITY | Düşük kaliteli bir ara değerleme modunu belirtir, bu mod InterpolationModeNearestNeighbor olarak tanımlanır. |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | En yakın komşu ara değerlemeyi belirtir; bu, ara değerlenen piksele en yakın pikselin değerini kullanır. Bu mod sadece pikselleri çoğaltır veya kaldırır ve seçenekler arasında en düşük kaliteli sonucu üretir. |
