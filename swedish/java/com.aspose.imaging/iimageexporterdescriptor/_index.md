---
title: "IImageExporterDescriptor"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar bildexportörens beskrivning."
type: docs
weight: 132
url: /sv/java/com.aspose.imaging/iimageexporterdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Representerar bildexportörens beskrivning. Exportörbeskrivningen används för att undvika behovet av att hålla varje exportörsinstans i minnet och problem med flertrådad körning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Bestämmer om bildexportören kan exportera den angivna bilden till det angivna bildformatet som specificeras av sparalternativen. |
| [createInstance()](#createInstance--) | Skapar en ny exportörsinstans. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Bestämmer om bildexportören kan exportera den angivna bilden till det angivna bildformatet som specificeras av sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Bilden att exportera. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Alternativbasen. |

**Returns:**
boolean - `true` om exportören som skapats av denna beskrivning kan exportera den angivna bilden till det angivna filformatet; annars `false`.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Skapar en ny exportörsinstans.

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - A new exporter instance.
