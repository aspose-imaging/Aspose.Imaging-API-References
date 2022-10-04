---
title: StretchMode
second_title: Aspose.Imaging for .NET API Referansı
description: StretchMode./stretchmodeNumaralandırma sistemin bir bitmapin satırlarını veya sütunlarını mevcut piksellerle nasıl birleştirdiğini tanımlayan bitmap genişletme modunu belirtir.
type: docs
weight: 8090
url: /tr/net/aspose.imaging.fileformats.wmf.consts/stretchmode/
---
## StretchMode enumeration

[`StretchMode`](../stretchmode)Numaralandırma, sistemin bir bitmap'in satırlarını veya sütunlarını mevcut piksellerle nasıl birleştirdiğini tanımlayan bitmap genişletme modunu belirtir.

```csharp
public enum StretchMode
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| BlackOnWhite | `1` | elimine edilen ve mevcut pikseller için renk değerlerini kullanarak bir Boole AND işlemi gerçekleştirir. Bitmap bir monokrom bitmap ise, bu mod white piksel pahasına siyah pikselleri korur |
| WhiteOnBlack | `2` | Yok edilen ve var olan pikseller için renk değerlerini kullanarak bir Boole VEYA işlemi gerçekleştirir. Bitmap bir monokrom bitmap ise, bu mod siyah piksel pahasına beyaz pikselleri korur |
| ColorOnColor | `3` | Pikselleri siler. Bu mod, piksel 'nin elimine edilen tüm satırlarını, bilgilerini korumaya çalışmadan siler. |
| HalfTone | `4` | Kaynak dikdörtgendeki pikselleri, hedef dikdörtgenindeki piksel bloklarına eşler. Hedef blok piksel üzerindeki ortalama renk, kaynak piksellerin rengine yaklaşır. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->