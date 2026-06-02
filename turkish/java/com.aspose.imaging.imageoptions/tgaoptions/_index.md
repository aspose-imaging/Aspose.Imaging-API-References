---
title: "TgaOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "TGA dosya formatı oluşturma seçenekleri."
type: docs
weight: 47
url: /tr/java/com.aspose.imaging.imageoptions/tgaoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class TgaOptions extends ImageOptionsBase
```

TGA dosya formatı oluşturma seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TgaOptions()](#TgaOptions--) | Yeni bir [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) sınıfı örneği başlatır. |
| [TgaOptions(TgaOptions tgaOptions)](#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-) | Yeni bir [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) sınıfı örneği başlatır. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```

### TgaOptions() {#TgaOptions--}
```
public TgaOptions()
```


Yeni bir [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) sınıfı örneği başlatır.

### TgaOptions(TgaOptions tgaOptions) {#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-}
```
public TgaOptions(TgaOptions tgaOptions)
```


Yeni bir [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tgaOptions | [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) | TGA seçenekleri. |

