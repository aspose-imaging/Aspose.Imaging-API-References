---
title: "Classe SvgResourceKeeperCallback"
type: docs
weight: 50
url: /fr/python-net/aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---

**Summary:** The resource keeper callback.

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.SvgResourceKeeperCallback

**Inheritance:** ISvgResourceKeeperCallback

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback__1) | Initialise une nouvelle instance de la classe SvgResourceKeeperCallback |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_1) | Appelé lorsque la ressource de police est prête à être exportée. |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2) | Appelé lorsque la ressource d'image est prête à être exportée. |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | Appelé lorsque le document SVG est prêt à être exporté. |


### Constructor: SvgResourceKeeperCallback() {#SvgResourceKeeperCallback__1}


```
 SvgResourceKeeperCallback() 
```

Initialise une nouvelle instance de la classe SvgResourceKeeperCallback

### Method: on_font_resource_ready(args) {#on_font_resource_ready_args_1}


```
 on_font_resource_ready(args) 
```

Appelé lorsque la ressource de police est prête à être exportée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs/) | Les options de stockage de la police. |

### Method: on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

Appelé lorsque la ressource d'image est prête à être exportée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_data | System.Byte | Les données de la ressource. |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype/) | Type de l'image. |
| suggested_file_name | string | Nom du fichier suggéré. |
| use_embedded_image | bool[] | si défini sur <c>true</c> l'image intégrée doit être utilisée. |

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie le chemin vers la ressource enregistrée. Le chemin doit être relatif au document SVG cible. |


### Method: on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

Appelé lorsque le document SVG est prêt à être exporté.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| html_data | System.Byte | Les données SVG. |
| suggested_file_name | string | Nom du fichier suggéré. |

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie le chemin du document SVG enregistré. |


