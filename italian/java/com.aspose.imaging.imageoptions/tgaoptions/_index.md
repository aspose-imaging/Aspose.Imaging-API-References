---
title: "TgaOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni di creazione del formato file TGA."
type: docs
weight: 47
url: /it/java/com.aspose.imaging.imageoptions/tgaoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class TgaOptions extends ImageOptionsBase
```

Le opzioni di creazione del formato file TGA.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TgaOptions()](#TgaOptions--) | Inizializza una nuova istanza della classe [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |
| [TgaOptions(TgaOptions tgaOptions)](#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-) | Inizializza una nuova istanza della classe [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |

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


Inizializza una nuova istanza della classe [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

### TgaOptions(TgaOptions tgaOptions) {#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-}
```
public TgaOptions(TgaOptions tgaOptions)
```


Inizializza una nuova istanza della classe [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tgaOptions | [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) | Le opzioni TGA. |

