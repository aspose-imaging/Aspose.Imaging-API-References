---
title: "IImageExporterDescriptor Classe"
type: docs
weight: 5330
url: /it/python-net/aspose.imaging/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageExporterDescriptor

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Determina se l'esportatore di immagini può esportare l'immagine specificata nel formato immagine specificato dalle opzioni di salvataggio. |
| [create_instance()](#create_instance__2) | Crea una nuova istanza dell'esportatore. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Determina se l'esportatore di immagini può esportare l'immagine specificata nel formato immagine specificato dalle opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da esportare. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | La base delle opzioni. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>True</c> se l'esportatore creato da questo descrittore può esportare l'immagine specificata nel formato file specificato; altrimenti, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nuova istanza dell'esportatore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Una nuova istanza dell'esportatore. |


