---
title: ImageAttributes
second_title: Aspose.Imaging for .NET API Referansı
description: BirImageAttributes./imageattributes nesne oluşturma sırasında bitmap ve meta dosyası renklerinin nasıl değiştirildiği hakkında bilgi içerir. BirImageAttributes./imageattributesnesne renk ayarlama matrisleri gri tonlama ayarlama matrisleri gama düzeltme değerleri renk haritası tabloları ve renk eşiği değerleri dahil olmak üzere çeşitli renk ayarlama ayarlarını korur. Render sırasında renkler düzeltilebilir koyulaştırılabilir aydınlatılabilir ve kaldırılabilir. Bu tür manipülasyonları uygulamak için birImageAttributes./imageattributes nesne ve bunun yolunu geçmekImageAttributes./imageattributes nesne birImage./image  DrawImage yöntemine.
type: docs
weight: 9680
url: /tr/aspose.imaging/imageattributes/
---
## ImageAttributes class

Bir[`ImageAttributes`](../imageattributes) nesne, oluşturma sırasında bitmap ve meta dosyası renklerinin nasıl değiştirildiği hakkında bilgi içerir. Bir[`ImageAttributes`](../imageattributes)nesne, renk ayarlama matrisleri, gri tonlama ayarlama matrisleri, gama düzeltme değerleri, renk haritası tabloları ve renk eşiği değerleri dahil olmak üzere çeşitli renk ayarlama ayarlarını korur. Render sırasında renkler düzeltilebilir, koyulaştırılabilir, aydınlatılabilir ve kaldırılabilir. Bu tür manipülasyonları uygulamak için bir[`ImageAttributes`](../imageattributes) nesne ve bunun yolunu geçmek[`ImageAttributes`](../imageattributes) nesne (bir[`Image`](../image) ) DrawImage yöntemine.

```csharp
public sealed class ImageAttributes
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ImageAttributes](imageattributes)() | Default_Constructor |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable)() | Bunun fırça rengi yeniden eşleme tablosunu temizler[`ImageAttributes`](../imageattributes) nesne. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey)() | Varsayılan kategori için renk anahtarını (saydamlık aralığı) temizler. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey_1)(ColorAdjustType) | Belirtilen kategori için renk anahtarını (saydamlık aralığı) temizler. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix)() | Varsayılan kategori için renk ayarlama matrisini temizler. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix_1)(ColorAdjustType) | Belirtilen kategori için renk ayarlama matrisini temizler. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma)() | Varsayılan kategori için gama düzeltmesini devre dışı bırakır. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma_1)(ColorAdjustType) | Belirtilen kategori için gama düzeltmesini devre dışı bırakır. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop)() | Varsayılan kategori için NoOp ayarını temizler. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop_1)(ColorAdjustType) | Belirtilen kategori için NoOp ayarını temizler. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel)() | Varsayılan kategori için CMYK (camgöbeği-macenta-sarı-siyah) çıkış kanalı ayarını temizler. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel_1)(ColorAdjustType) | Belirtilen kategori için (camgöbeği-macenta-sarı-siyah) çıkış kanalı ayarını temizler. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile)() | Varsayılan kategori için çıktı kanalı renk profili ayarını temizler. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Belirtilen kategori için çıktı kanalı renk profili ayarını temizler. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable)() | Varsayılan kategori için renk yeniden eşleme tablosunu temizler. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable_1)(ColorAdjustType) | Belirtilen kategori için renk yeniden eşleme tablosunu temizler. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold)() | Varsayılan kategori için eşik değerini temizler. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold_1)(ColorAdjustType) | Belirtilen kategori için eşik değerini temizler. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable)(ColorMap[]) | Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey)(Color, Color) | Varsayılan kategori için renk anahtarını ayarlar. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey_1)(Color, Color, ColorAdjustType) | Belirtilen kategori için renk anahtarını (saydamlık aralığı) ayarlar. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices)(ColorMatrix, ColorMatrix) | Varsayılan kategori için renk ayar matrisini ve gri tonlamalı ayar matrisini ayarlar. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Varsayılan kategori için renk ayar matrisini ve gri tonlamalı ayar matrisini ayarlar. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Belirtilen kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix)(ColorMatrix) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Belirtilen kategori için renk ayarlama matrisini ayarlar. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma)(float) | Varsayılan kategori için gama değerini ayarlar. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma_1)(float, ColorAdjustType) | Belirtilen kategori için gama değerini ayarlar. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop)() | Varsayılan kategori için renk ayarını kapatır. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop_1)(ColorAdjustType) | Belirtilen kategori için renk ayarını kapatır. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel)(ColorChannelFlag) | Varsayılan kategori için CMYK (camgöbeği-macenta-sarı-siyah) çıkış kanalını ayarlar. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Belirtilen kategori için CMYK (camgöbeği-macenta-sarı-siyah) çıkış kanalını ayarlar. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile)(string) | Varsayılan kategori için çıktı kanalı renk profili dosyasını ayarlar. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Belirtilen kategori için çıktı kanalı renk profili dosyasını ayarlar. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable)(ColorMap[]) | Varsayılan kategori için renk yeniden eşleme tablosunu ayarlar. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable_1)(ColorMap[], ColorAdjustType) | Belirtilen kategori için renk yeniden eşleme tablosunu ayarlar. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold)(float) | Varsayılan kategori için eşiği (saydamlık aralığı) ayarlar. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold_1)(float, ColorAdjustType) | Belirtilen kategori için eşiği (saydamlık aralığı) ayarlar. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode)(WrapMode) | Bir dokunun bir şekilde veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ayarlar. Bir doku, doku doldurduğu şekilden daha küçük olduğunda, onu doldurmak için bir şekle döşenir. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_1)(WrapMode, Color) | Bir dokunun bir şekilde veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Bir doku, doku doldurduğu şekilden daha küçük olduğunda, onu doldurmak için bir şekle döşenir. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_2)(WrapMode, Color, bool) | Bir dokunun bir şekilde veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Bir doku, doku doldurduğu şekilden daha küçük olduğunda, onu doldurmak için bir şekle döşenir. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
