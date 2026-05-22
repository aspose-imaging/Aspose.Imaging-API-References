---
title: "ISvgResourceKeeperCallback 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/
---

**Summary:** The svg callback interface

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_1) | 当字体资源准备好导出时调用。 |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2) | 当图像资源准备好导出时调用。 |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | 当 SVG 文档准备好导出时调用。 |


### Method: on_font_resource_ready(args) {#on_font_resource_ready_args_1}


```
 on_font_resource_ready(args) 
```

当字体资源准备好导出时调用。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs/) | 字体存储选项。 |

### Method: on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

当图像资源准备好导出时调用。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_data | System.Byte | 资源数据。 |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype/) | 图像类型。 |
| suggested_file_name | string | 建议文件的名称。 |
| use_embedded_image | bool[] | 如果设置为 <c>true</c>，则必须使用嵌入的图像。 |

**Returns**

| Type | Description |
| :- | :- |
| string | 返回已保存资源的路径。路径应相对于目标 SVG 文档。 |


### Method: on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

当 SVG 文档准备好导出时调用。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| html_data | System.Byte | SVG 数据。 |
| suggested_file_name | string | 建议文件的名称。 |

**Returns**

| Type | Description |
| :- | :- |
| string | 返回已保存 SVG 文档的路径。 |


