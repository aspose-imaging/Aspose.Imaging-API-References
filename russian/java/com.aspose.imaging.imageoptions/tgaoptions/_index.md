---
title: "TgaOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры создания файлов формата TGA."
type: docs
weight: 47
url: /ru/java/com.aspose.imaging.imageoptions/tgaoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class TgaOptions extends ImageOptionsBase
```

Параметры создания файлов формата TGA.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TgaOptions()](#TgaOptions--) | Инициализирует новый экземпляр класса [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |
| [TgaOptions(TgaOptions tgaOptions)](#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-) | Инициализирует новый экземпляр класса [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions). |

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


Инициализирует новый экземпляр класса [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

### TgaOptions(TgaOptions tgaOptions) {#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-}
```
public TgaOptions(TgaOptions tgaOptions)
```


Инициализирует новый экземпляр класса [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tgaOptions | [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) | Параметры TGA. |

