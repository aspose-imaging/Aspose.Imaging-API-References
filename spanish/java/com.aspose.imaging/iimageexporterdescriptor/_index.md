---
title: "IImageExporterDescriptor"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el descriptor del exportador de imágenes."
type: docs
weight: 132
url: /es/java/com.aspose.imaging/iimageexporterdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Representa el descriptor del exportador de imágenes. El descriptor del exportador se utiliza para superar la necesidad de contener cada instancia del exportador en memoria y los problemas de multihilo.
## Métodos

| Método | Descripción |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Determina si el exportador de imágenes puede exportar la imagen especificada al formato de imagen especificado por las opciones de guardado. |
| [createInstance()](#createInstance--) | Crea una nueva instancia del exportador. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Determina si el exportador de imágenes puede exportar la imagen especificada al formato de imagen especificado por las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La imagen a exportar. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | La base de opciones. |

**Returns:**
booleano - `true` si el exportador creado por este descriptor puede exportar la imagen especificada al formato de archivo especificado; de lo contrario, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Crea una nueva instancia del exportador.

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - A new exporter instance.
