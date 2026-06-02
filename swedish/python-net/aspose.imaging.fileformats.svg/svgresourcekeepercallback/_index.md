---
title: "SvgResourceKeeperCallback klass"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---

**Summary:** The resource keeper callback.

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.SvgResourceKeeperCallback

**Inheritance:** ISvgResourceKeeperCallback

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback__1) | Initierar en ny instans av SvgResourceKeeperCallback-klassen |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_1) | Kallas när teckensnittresursen är klar för export. |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2) | Kallas när bildresursen är klar för export. |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | Kallas när SVG-dokumentet är klart för export. |


### Constructor: SvgResourceKeeperCallback() {#SvgResourceKeeperCallback__1}


```
 SvgResourceKeeperCallback() 
```

Initierar en ny instans av SvgResourceKeeperCallback-klassen

### Method: on_font_resource_ready(args) {#on_font_resource_ready_args_1}


```
 on_font_resource_ready(args) 
```

Kallas när teckensnittresursen är klar för export.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs/) | Teckensnittslagringsalternativen. |

### Method: on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

Kallas när bildresursen är klar för export.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_data | System.Byte | Resursdata. |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype/) | Typ av bilden. |
| suggested_file_name | string | Namn på den föreslagna filen. |
| use_embedded_image | bool[] | Om den är inställd på <c>true</c> måste den inbäddade bilden användas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar sökvägen till den sparade resursen. Sökvägen bör vara relativ till mål‑SVG‑dokumentet. |


### Method: on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

Kallas när SVG-dokumentet är klart för export.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| html_data | System.Byte | SVG-data. |
| suggested_file_name | string | Namn på den föreslagna filen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar sökvägen till det sparade SVG-dokumentet. |


