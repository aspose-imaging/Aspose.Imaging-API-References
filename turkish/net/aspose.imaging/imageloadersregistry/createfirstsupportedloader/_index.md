---
title: CreateFirstSupportedLoader
second_title: Aspose.Imaging for .NET API Referansı
description: Belirtilen için uygun ilk bulunan yükleyiciyi oluştururstream ve isteğe bağlı olarakloadOptions .
type: docs
weight: 30
url: /tr/net/aspose.imaging/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Belirtilen için uygun ilk bulunan yükleyiciyi oluşturur*stream* ve isteğe bağlı olarak*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Akış. |
| loadOptions | LoadOptions | Yük seçenekleri. |

### Geri dönüş değeri

Belirtilenleri destekleyen yükleyici*stream* ve*loadOptions* veya böyle bir yükleyici bulunmazsa null.

### Notlar

İlk yükleyici aslında en son kaydedilen olacaktır.

### Ayrıca bakınız

* interface [IImageLoader](../../iimageloader)
* class [LoadOptions](../../loadoptions)
* class [ImageLoadersRegistry](../../imageloadersregistry)
* ad alanı [Aspose.Imaging](../../imageloadersregistry)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
