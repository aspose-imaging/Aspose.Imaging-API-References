---
title: "IImageExporterDescriptor"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta il descrittore dell'esportatore dell'immagine."
type: docs
weight: 132
url: /it/java/com.aspose.imaging/iimageexporterdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Rappresenta il descrittore dell'esportatore di immagini. Il descrittore dell'esportatore è usato per superare la necessità di contenere ogni istanza dell'esportatore in memoria e i problemi di multithreading.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Determina se l'esportatore di immagini può esportare l'immagine specificata nel formato immagine specificato dalle opzioni di salvataggio. |
| [createInstance()](#createInstance--) | Crea una nuova istanza dell'esportatore. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Determina se l'esportatore di immagini può esportare l'immagine specificata nel formato immagine specificato dalle opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'immagine da esportare. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | La base delle opzioni. |

**Returns:**
boolean - `true` se l'esportatore creato da questo descrittore può esportare l'immagine specificata nel formato file specificato; altrimenti, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Crea una nuova istanza dell'esportatore.

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - A new exporter instance.
