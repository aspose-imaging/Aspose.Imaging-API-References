---
title: EmfPlusColorBalanceEffect
second_title: Aspose.Imaging for .NET API Referansı
description: ColorBalanceEffect nesnesi bir görüntüdeki göreli kırmızı yeşil ve mavi miktarlarına yönelik ayarlamaları belirtir.
type: docs
weight: 5290
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
## EmfPlusColorBalanceEffect class

ColorBalanceEffect nesnesi, bir görüntüdeki göreli kırmızı, yeşil ve mavi miktarlarına yönelik ayarlamaları belirtir.

```csharp
public sealed class EmfPlusColorBalanceEffect : EmfPlusImageEffectsObjectType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusColorBalanceEffect](emfpluscolorbalanceeffect)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CyanRed](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/cyanred) { get; set; } | görüntüsündeki kırmızı miktarındaki değişikliği belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. Bu değer, -100 ila 100 aralığında OLMALIDIR ve aşağıdaki etkilerle birlikte: -100 ≤ değer &lt; 0 Değer azaldıkça, görüntüdeki kırmızı miktarı AZALMALIDIR ve camgöbeği miktarı ARTIRILMALIDIR. 0 A değeri / 0, kırmızı ve camgöbeği miktarlarının DEĞİŞMEMESİ gerektiğini belirtir. 0 &lt; değer ≤ 100 Değer arttıkça, görüntüdeki kırmızı miktarı ARTIRILMALIDIR ve camgöbeği miktarı AZALMALIDIR. |
| [MagentaGreen](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/magentagreen) { get; set; } | Görüntüdeki yeşil miktarındaki değişikliği belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. Bu değer -100 ila 100 aralığında OLMALIDIR, etkileri as aşağıdaki gibidir: -100 ≤ değer &lt; 0 Değer azaldıkça, görüntüdeki yeşil miktarı AZALMALIDIR ve macenta miktarı ARTIRILMALIDIR. 0 A değeri / 0, yeşil ve macenta miktarlarının DEĞİŞMEMESİ gerektiğini belirtir. 0 &lt; değer ≤ 100 Değer arttıkça, görüntüdeki yeşil miktarı ARTIRILMALIDIR ve macenta miktarı DÜŞMELİDİR. |
| [YellowBlue](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/yellowblue) { get; set; } | Görüntüdeki mavi miktarındaki değişikliği belirten 32 bit işaretli bir tamsayı alır veya ayarlar. Bu değer -100 ile 100 arasında OLMALIDIR ve aşağıdaki etkilerle birlikte: -100 ≤ değer &lt; 0 Değer azaldıkça, görüntüdeki mavi miktarı AZALMALIDIR ve sarı miktarı ARTIRILMALIDIR. 0 A değeri of 0, mavi ve sarı miktarlarının DEĞİŞMEMESİ gerektiğini belirtir. 0 &lt; değer ≤ 100 Değer arttıkça, görüntüdeki mavi miktarı artmalı ve sarı miktarı azalmalıdır. |

### Ayrıca bakınız

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->