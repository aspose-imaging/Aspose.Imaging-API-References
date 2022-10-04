---
title: WmfFontQuality
second_title: Aspose.Imaging for .NET API Referansı
description: FontQuality Enumeration metin oluşturulurken mantıksal fontun niteliklerinin fiziksel fontun öznitelikleriyle ne kadar yakından eşleşmesi gerektiğini belirtir.
type: docs
weight: 8180
url: /tr/net/aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
## WmfFontQuality enumeration

FontQuality Enumeration, metin oluşturulurken mantıksal fontun niteliklerinin fiziksel fontun öznitelikleriyle ne kadar yakından eşleşmesi gerektiğini belirtir.

```csharp
public enum WmfFontQuality : byte
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Default | `0` | Yazı tipinin karakter kalitesinin önemli olmadığını belirtir, bu nedenle TASLAK kullanılabilir. |
| Draft | `1` | Yazı tipinin karakter kalitesinin, mantıksal niteliklerin eşleşmesinden daha az önemli olduğunu belirtir. Rasterleştirilmiş yazı tipleri için, ölçekleme etkinleştirilmelidir, bu da daha fazla yazı tipi boyutunun mevcut olduğu anlamına gelir. |
| Proof | `2` | Yazı tipinin karakter kalitesinin, mantıksal özniteliklerin eşleşmesinden daha önemli olduğunu belirtir. Rasterleştirilmiş yazı tipleri için, ölçekleme devre dışı bırakılmalı ve boyut olarak en yakın font seçilmelidir. |
| Nonantialiased | `3` | text oluşturulurken kenar yumuşatmanın KULLANILMAMASI gerektiğini belirtir |
| Antialiased | `4` | Metin oluşturulurken kenar yumuşatma kullanılması gerektiğini belirtir, eğer yazı tipi destekliyorsa. |
| Cleartype | `5` | Yazı tipi destekliyorsa, metin oluşturulurken ClearType kenar yumuşatma kullanılması GEREKLİ olduğunu belirtir. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->