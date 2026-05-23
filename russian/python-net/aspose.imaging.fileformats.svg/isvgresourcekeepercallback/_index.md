---
title: "ISvgResourceKeeperCallback Класс"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/
---

**Summary:** The svg callback interface

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_1) | Вызывается, когда ресурс шрифта готов к экспорту. |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2) | Вызывается, когда ресурс изображения готов к экспорту. |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | Вызывается, когда документ SVG готов к экспорту. |


### Method: on_font_resource_ready(args) {#on_font_resource_ready_args_1}


```
 on_font_resource_ready(args) 
```

Вызывается, когда ресурс шрифта готов к экспорту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs/) | Параметры сохранения шрифта. |

### Method: on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

Вызывается, когда ресурс изображения готов к экспорту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_data | System.Byte | Данные ресурса. |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype/) | Тип изображения. |
| suggested_file_name | string | Имя предложенного файла. |
| use_embedded_image | bool[] | если установлено <c>true</c>, должно использоваться встроенное изображение. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает путь к сохранённому ресурсу. Путь должен быть относительным к целевому документу SVG. |


### Method: on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

Вызывается, когда документ SVG готов к экспорту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| html_data | System.Byte | Данные SVG. |
| suggested_file_name | string | Имя предложенного файла. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает путь к сохраненному документу SVG. |


