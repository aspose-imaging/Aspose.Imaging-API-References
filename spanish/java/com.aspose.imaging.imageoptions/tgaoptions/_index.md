---
title: "TgaOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de creación del formato de archivo TGA."
type: docs
weight: 47
url: /es/java/com.aspose.imaging.imageoptions/tgaoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class TgaOptions extends ImageOptionsBase
```

Las opciones de creación del formato de archivo TGA.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TgaOptions()](#TgaOptions--) | Inicializa una nueva instancia de la clase [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |
| [TgaOptions(TgaOptions tgaOptions)](#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-) | Inicializa una nueva instancia de la clase [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |

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


Inicializa una nueva instancia de la clase [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

### TgaOptions(TgaOptions tgaOptions) {#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-}
```
public TgaOptions(TgaOptions tgaOptions)
```


Inicializa una nueva instancia de la clase [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tgaOptions | [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) | Las opciones TGA. |

