---
title: "Clase IImageExporterDescriptor"
type: docs
weight: 5330
url: /es/python-net/aspose.imaging/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageExporterDescriptor

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Determina si el exportador de imágenes puede exportar la imagen especificada al formato de imagen especificado por las opciones de guardado. |
| [create_instance()](#create_instance__2) | Crea una nueva instancia del exportador. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Determina si el exportador de imágenes puede exportar la imagen especificada al formato de imagen especificado por las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a exportar. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | La base de opciones. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>True</c> si el exportador creado por este descriptor puede exportar la imagen especificada al formato de archivo especificado; de lo contrario, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nueva instancia del exportador.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Una nueva instancia del exportador. |


