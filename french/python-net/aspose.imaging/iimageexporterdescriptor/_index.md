---
title: "Classe IImageExporterDescriptor"
type: docs
weight: 5330
url: /fr/python-net/aspose.imaging/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageExporterDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Détermine si l'exportateur d'image peut exporter l'image spécifiée au format d'image spécifié par les options d'enregistrement. |
| [create_instance()](#create_instance__2) | Crée une nouvelle instance d'exportateur. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Détermine si l'exportateur d'image peut exporter l'image spécifiée au format d'image spécifié par les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à exporter. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | La base des options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>True</c> si l'exportateur créé par ce descripteur peut exporter l'image spécifiée au format de fichier spécifié ; sinon, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crée une nouvelle instance d'exportateur.

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Une nouvelle instance d'exportateur. |


