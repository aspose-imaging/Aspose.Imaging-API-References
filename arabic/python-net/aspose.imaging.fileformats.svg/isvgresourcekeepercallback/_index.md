---
title: "فئة ISvgResourceKeeperCallback"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/
---

**Summary:** The svg callback interface

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_1) | يتم الاستدعاء عندما يكون مورد الخط جاهزًا للتصدير. |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2) | يتم الاستدعاء عندما يكون مورد الصورة جاهزًا للتصدير. |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | يتم الاستدعاء عندما يكون مستند SVG جاهزًا للتصدير. |


### Method: on_font_resource_ready(args) {#on_font_resource_ready_args_1}


```
 on_font_resource_ready(args) 
```

يتم الاستدعاء عندما يكون مورد الخط جاهزًا للتصدير.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs/) | خيارات تخزين الخط. |

### Method: on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

يتم الاستدعاء عندما يكون مورد الصورة جاهزًا للتصدير.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_data | System.Byte | بيانات المورد. |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype/) | نوع الصورة. |
| suggested_file_name | string | اسم الملف المقترح. |
| use_embedded_image | bool[] | إذا تم تعيينها إلى <c>true</c> يجب استخدام الصورة المضمنة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يعيد المسار إلى المورد المحفوظ. يجب أن يكون المسار نسبيًا إلى مستند SVG الهدف. |


### Method: on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

يتم الاستدعاء عندما يكون مستند SVG جاهزًا للتصدير.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| html_data | System.Byte | بيانات SVG. |
| suggested_file_name | string | اسم الملف المقترح. |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يعيد المسار إلى مستند SVG المحفوظ. |


