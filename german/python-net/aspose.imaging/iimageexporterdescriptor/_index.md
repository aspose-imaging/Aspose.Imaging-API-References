---
title: "IImageExporterDescriptor Klasse"
type: docs
weight: 5330
url: /de/python-net/aspose.imaging/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageExporterDescriptor

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Bestimmt, ob der Bildexporter das angegebene Bild in das durch die Speicheroptionen angegebene Bildformat exportieren kann. |
| [create_instance()](#create_instance__2) | Erstellt eine neue Exporter-Instanz. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Bestimmt, ob der Bildexporter das angegebene Bild in das durch die Speicheroptionen angegebene Bildformat exportieren kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das zu exportierende Bild. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionsbasis. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>True</c> wenn der von diesem Deskriptor erstellte Exporter das angegebene Bild in das angegebene Dateiformat exportieren kann; andernfalls <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Erstellt eine neue Exporter-Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Eine neue Exporter-Instanz. |


