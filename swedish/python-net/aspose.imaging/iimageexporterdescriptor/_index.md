---
title: "IImageExporterDescriptor klass"
type: docs
weight: 5330
url: /sv/python-net/aspose.imaging/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageExporterDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Bestämmer om bildexportören kan exportera den angivna bilden till det angivna bildformatet som specificeras av sparalternativen. |
| [create_instance()](#create_instance__2) | Skapar en ny exportörsinstans. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Bestämmer om bildexportören kan exportera den angivna bilden till det angivna bildformatet som specificeras av sparalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att exportera. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativbasen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>True</c> om exportören som skapats av denna beskrivare kan exportera den angivna bilden till det angivna filformatet; annars <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Skapar en ny exportörsinstans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | En ny exportörsinstans. |


