---
title: "Clase SvgResourceKeeperCallback"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---

**Summary:** The resource keeper callback.

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.SvgResourceKeeperCallback

**Inheritance:** ISvgResourceKeeperCallback

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback__1) | Inicializa una nueva instancia de la clase SvgResourceKeeperCallback |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_1) | Se llama cuando el recurso de fuente está listo para exportarse. |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2) | Se llama cuando el recurso de imagen está listo para exportarse. |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | Se llama cuando el documento SVG está listo para exportarse. |


### Constructor: SvgResourceKeeperCallback() {#SvgResourceKeeperCallback__1}


```
 SvgResourceKeeperCallback() 
```

Inicializa una nueva instancia de la clase SvgResourceKeeperCallback

### Method: on_font_resource_ready(args) {#on_font_resource_ready_args_1}


```
 on_font_resource_ready(args) 
```

Se llama cuando el recurso de fuente está listo para exportarse.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs/) | Las opciones de almacenamiento de fuentes. |

### Method: on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

Se llama cuando el recurso de imagen está listo para exportarse.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_data | System.Byte | Los datos del recurso. |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype/) | Tipo de la imagen. |
| suggested_file_name | string | Nombre del archivo sugerido. |
| use_embedded_image | bool[] | si se establece en <c>true</c> la imagen incrustada debe usarse. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve la ruta al recurso guardado. La ruta debe ser relativa al documento SVG de destino. |


### Method: on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

Se llama cuando el documento SVG está listo para exportarse.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| html_data | System.Byte | Los datos SVG. |
| suggested_file_name | string | Nombre del archivo sugerido. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve la ruta al documento SVG guardado. |


