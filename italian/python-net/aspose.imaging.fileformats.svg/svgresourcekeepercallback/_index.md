---
title: "Classe SvgResourceKeeperCallback"
type: docs
weight: 50
url: /it/python-net/aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---

**Summary:** The resource keeper callback.

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.SvgResourceKeeperCallback

**Inheritance:** ISvgResourceKeeperCallback

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback__1) | Inizializza una nuova istanza della classe SvgResourceKeeperCallback |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [on_font_resource_ready(args)](#on_font_resource_ready_args_1) | Chiamata quando la risorsa del font è pronta per l'esportazione. |
| [on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image)](#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2) | Chiamata quando la risorsa dell'immagine è pronta per l'esportazione. |
| [on_svg_document_ready(html_data, suggested_file_name)](#on_svg_document_ready_html_data_suggested_file_name_3) | Chiamata quando il documento SVG è pronto per l'esportazione. |


### Constructor: SvgResourceKeeperCallback() {#SvgResourceKeeperCallback__1}


```
 SvgResourceKeeperCallback() 
```

Inizializza una nuova istanza della classe SvgResourceKeeperCallback

### Method: on_font_resource_ready(args) {#on_font_resource_ready_args_1}


```
 on_font_resource_ready(args) 
```

Chiamata quando la risorsa del font è pronta per l'esportazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| args | [FontStoringArgs](/imaging/python-net/aspose.imaging.fileformats.svg/fontstoringargs/) | Le opzioni di memorizzazione del font. |

### Method: on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) {#on_image_resource_ready_image_data_image_type_suggested_file_name_use_embedded_image_2}


```
 on_image_resource_ready(image_data, image_type, suggested_file_name, use_embedded_image) 
```

Chiamata quando la risorsa dell'immagine è pronta per l'esportazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_data | System.Byte | I dati della risorsa. |
| image_type | [SvgImageType](/imaging/python-net/aspose.imaging.fileformats.svg/svgimagetype/) | Tipo dell'immagine. |
| suggested_file_name | string | Nome del file suggerito. |
| use_embedded_image | bool[] | se impostato su <c>true</c> l'immagine incorporata deve essere usata. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il percorso della risorsa salvata. Il percorso dovrebbe essere relativo al documento SVG di destinazione. |


### Method: on_svg_document_ready(html_data, suggested_file_name) {#on_svg_document_ready_html_data_suggested_file_name_3}


```
 on_svg_document_ready(html_data, suggested_file_name) 
```

Chiamata quando il documento SVG è pronto per l'esportazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| html_data | System.Byte | I dati SVG. |
| suggested_file_name | string | Nome del file suggerito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il percorso del documento SVG salvato. |


