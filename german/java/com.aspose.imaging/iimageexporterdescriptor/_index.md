---
title: "IImageExporterDescriptor"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt den Bild-Exporter-Deskriptor dar."
type: docs
weight: 132
url: /de/java/com.aspose.imaging/iimageexporterdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Stellt den Bildexporter-Deskriptor dar. Der Exporter-Deskriptor wird verwendet, um die Notwendigkeit zu umgehen, jede Exporter-Instanz im Speicher zu halten und Multithreading-Probleme zu vermeiden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Bestimmt, ob der Bildexporter das angegebene Bild in das durch die Speicheroptionen angegebene Bildformat exportieren kann. |
| [createInstance()](#createInstance--) | Erstellt eine neue Exporter-Instanz. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Bestimmt, ob der Bildexporter das angegebene Bild in das durch die Speicheroptionen angegebene Bildformat exportieren kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das Bild zum Exportieren. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Optionsbasis. |

**Returns:**
boolean - `true`, wenn der durch diesen Deskriptor erstellte Exporter das angegebene Bild in das angegebene Dateiformat exportieren kann; andernfalls `false`.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Erstellt eine neue Exporter-Instanz.

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - A new exporter instance.
