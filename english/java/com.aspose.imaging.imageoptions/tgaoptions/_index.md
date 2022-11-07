---
title: TgaOptions
second_title: Aspose.Imaging for Java API Reference
description: The TGA file format create options.
type: docs
weight: 44
url: /java/com.aspose.imaging.imageoptions/tgaoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class TgaOptions extends ImageOptionsBase
```

The TGA file format create options.
## Constructors

| Constructor | Description |
| --- | --- |
| [TgaOptions()](#TgaOptions--) | Initializes a new instance of the [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) class. |
| [TgaOptions(TgaOptions tgaOptions)](#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-) | Initializes a new instance of the [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) class. |

## Example
Saving of the JPG image as a TGA image.
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


Initializes a new instance of the [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) class.

### TgaOptions(TgaOptions tgaOptions) {#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-}
```
public TgaOptions(TgaOptions tgaOptions)
```


Initializes a new instance of the [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tgaOptions | [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) | The TGA options. |

