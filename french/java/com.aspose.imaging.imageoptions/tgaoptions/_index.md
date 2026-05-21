---
title: "TgaOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options de création du format de fichier TGA."
type: docs
weight: 47
url: /fr/java/com.aspose.imaging.imageoptions/tgaoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class TgaOptions extends ImageOptionsBase
```

Les options de création du format de fichier TGA.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TgaOptions()](#TgaOptions--) | Initialise une nouvelle instance de la classe [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |
| [TgaOptions(TgaOptions tgaOptions)](#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-) | Initialise une nouvelle instance de la classe [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |

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


Initialise une nouvelle instance de la classe [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

### TgaOptions(TgaOptions tgaOptions) {#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-}
```
public TgaOptions(TgaOptions tgaOptions)
```


Initialise une nouvelle instance de la classe [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tgaOptions | [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) | Les options TGA. |

