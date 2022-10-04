---
title: ToCmykIccBytes
second_title: Aspose.Imaging for .NET API Referansı
description: Özel ICC profillerini kullanarak RGByi CMYKya dönüştürür.
type: docs
weight: 120
url: /tr/net/aspose.imaging/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

Özel ICC profillerini kullanarak RGB'yi CMYK'ya dönüştürür.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pixels | Int32[] | 32 bit tamsayı değerleri olarak sunulan RGB renkleri. |
| startIndex | Int32 | RGB renginin başlangıç dizini. |
| length | Int32 | Dönüştürülecek RGB piksel sayısı. |
| rgbIccStream | Stream | RGB profil akışı. |
| cmykIccStream | Stream | CMYK profil akışı. |

### Geri dönüş değeri

Bir bayt dizisi olarak sunulan CMYK renkleri.

### Ayrıca bakınız

* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->