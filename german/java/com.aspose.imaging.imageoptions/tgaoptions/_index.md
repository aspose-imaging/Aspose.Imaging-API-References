---
title: "TgaOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Erstellungsoptionen für das TGA-Dateiformat."
type: docs
weight: 47
url: /de/java/com.aspose.imaging.imageoptions/tgaoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class TgaOptions extends ImageOptionsBase
```

Die Erstellungsoptionen für das TGA-Dateiformat.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TgaOptions()](#TgaOptions--) | Initialisiert eine neue Instanz der [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) Klasse. |
| [TgaOptions(TgaOptions tgaOptions)](#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-) | Initialisiert eine neue Instanz der [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) Klasse. |

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


Initialisiert eine neue Instanz der [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) Klasse.

### TgaOptions(TgaOptions tgaOptions) {#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-}
```
public TgaOptions(TgaOptions tgaOptions)
```


Initialisiert eine neue Instanz der [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tgaOptions | [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) | Die TGA-Optionen. |

