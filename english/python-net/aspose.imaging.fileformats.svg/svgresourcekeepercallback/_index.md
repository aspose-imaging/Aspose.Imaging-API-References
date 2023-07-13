---
title: SvgResourceKeeperCallback Class
type: docs
weight: 50
url: /python-net/aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---

The resource keeper callback.

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.SvgResourceKeeperCallback

**Inheritance:** ISvgResourceKeeperCallback

**Aspose.Imaging Version:** 23.6

The SvgResourceKeeperCallback type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback__0) | Initializes a new instance of the SvgResourceKeeperCallback class |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_1) | Called when the image resource is ready for export. |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_2) | Called when the font resource is ready for export. |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | Called when the SVG document is ready for export. |

### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback__0}


```
 SvgResourceKeeperCallback() 
```

Initializes a new instance of the SvgResourceKeeperCallback class

### on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_1}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

Called when the image resource is ready for export.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_data | byte | The resource data. |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype) | Type of the image. |
| suggested_file_name | string | Name of the suggested file. |
| use_embedded_image | Boolean | if set to <c>true</c> the embedded image must be used. |

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the path to the saved resource. Path should be relative to target SVG document. |


### on_font_resource_ready(args) {#on_font_resource_ready_args_2}


```
 on_font_resource_ready(args) 
```

Called when the font resource is ready for export.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs) | The font storing options. |

### on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

Called when the SVG document is ready for export.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| html_data | byte | The SVG data. |
| suggested_file_name | string | Name of the suggested file. |

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the path to the saved SVG document. |


