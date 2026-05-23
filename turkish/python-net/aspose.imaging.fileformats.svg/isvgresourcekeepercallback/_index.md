---
title: "ISvgResourceKeeperCallback Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/
---

**Summary:** The svg callback interface

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_1) | Yazı tipi kaynağı dışa aktarma için hazır olduğunda çağrılır. |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2) | Görüntü kaynağı dışa aktarma için hazır olduğunda çağrılır. |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | SVG belgesi dışa aktarma için hazır olduğunda çağrılır. |


### Method: on_font_resource_ready(args) {#on_font_resource_ready_args_1}


```
 on_font_resource_ready(args) 
```

Yazı tipi kaynağı dışa aktarma için hazır olduğunda çağrılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs/) | Yazı tipi depolama seçenekleri. |

### Method: on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

Görüntü kaynağı dışa aktarma için hazır olduğunda çağrılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_data | System.Byte | Kaynak verileri. |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype/) | Görüntünün türü. |
| suggested_file_name | string | Önerilen dosyanın adı. |
| use_embedded_image | bool[] | eğer <c>true</c> olarak ayarlanırsa gömülü görüntü kullanılmalıdır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Kaydedilen kaynağın yolunu döndürür. Yol, hedef SVG belgesine göreceli olmalıdır. |


### Method: on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

SVG belgesi dışa aktarma için hazır olduğunda çağrılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| html_data | System.Byte | SVG verisi. |
| suggested_file_name | string | Önerilen dosyanın adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Kaydedilen SVG belgesinin yolunu döndürür. |


