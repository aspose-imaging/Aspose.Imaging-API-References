---
title: "ISvgResourceKeeperCallback Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/
---

**Summary:** The svg callback interface

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_1) | Aufgerufen, wenn die Schriftartressource für den Export bereit ist. |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2) | Aufgerufen, wenn die Bildressource für den Export bereit ist. |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | Aufgerufen, wenn das SVG-Dokument für den Export bereit ist. |


### Method: on_font_resource_ready(args) {#on_font_resource_ready_args_1}


```
 on_font_resource_ready(args) 
```

Aufgerufen, wenn die Schriftartressource für den Export bereit ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs/) | Die Optionen zum Speichern von Schriftarten. |

### Method: on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

Aufgerufen, wenn die Bildressource für den Export bereit ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_data | System.Byte | Die Ressourcendaten. |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype/) | Typ des Bildes. |
| suggested_file_name | string | Name der vorgeschlagenen Datei. |
| use_embedded_image | bool[] | Wenn auf <c>true</c> gesetzt, muss das eingebettete Bild verwendet werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den Pfad zur gespeicherten Ressource zurück. Der Pfad sollte relativ zum Ziel-SVG-Dokument sein. |


### Method: on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

Aufgerufen, wenn das SVG-Dokument für den Export bereit ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| html_data | System.Byte | Die SVG-Daten. |
| suggested_file_name | string | Name der vorgeschlagenen Datei. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den Pfad zum gespeicherten SVG-Dokument zurück. |


