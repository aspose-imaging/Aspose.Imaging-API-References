---
title: "TgaOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات إنشاء صيغة ملف TGA."
type: docs
weight: 47
url: /ar/java/com.aspose.imaging.imageoptions/tgaoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class TgaOptions extends ImageOptionsBase
```

خيارات إنشاء صيغة ملف TGA.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TgaOptions()](#TgaOptions--) | يُنشئ مثيلاً جديدًا من الفئة [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |
| [TgaOptions(TgaOptions tgaOptions)](#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-) | يُنشئ مثيلاً جديدًا من الفئة [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |

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


يُنشئ مثيلاً جديدًا من الفئة [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

### TgaOptions(TgaOptions tgaOptions) {#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-}
```
public TgaOptions(TgaOptions tgaOptions)
```


يُنشئ مثيلاً جديدًا من الفئة [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tgaOptions | [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) | خيارات TGA. |

