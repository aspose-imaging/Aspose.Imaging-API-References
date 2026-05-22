---
title: "Classe DjvuMultiPageOptions"
type: docs
weight: 70
url: /fr/python-net/aspose.imaging.imageoptions/djvumultipageoptions/
---

**Summary:** The API for DjVu graphics file format provides developers with seamless access<br/>            to DjVu documents, ideal for scanned documents and books. With image loading<br/>            options, developers can effortlessly integrate DjVu files into their applications,<br/>            unlocking the potential to work with multi-page content, including text,<br/>            drawings, and images, for versatile document processing solutions.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DjvuMultiPageOptions

**Inheritance:** MultiPageOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DjvuMultiPageOptions()](#DjvuMultiPageOptions__1) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page)](#DjvuMultiPageOptions_page_2) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page, export_area)](#DjvuMultiPageOptions_page_export_area_3) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages)](#DjvuMultiPageOptions_pages_4) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages, export_area)](#DjvuMultiPageOptions_pages_export_area_5) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range)](#DjvuMultiPageOptions_range_6) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range, export_area)](#DjvuMultiPageOptions_range_export_area_7) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges)](#DjvuMultiPageOptions_ranges_8) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges, export_area)](#DjvuMultiPageOptions_ranges_export_area_9) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit la zone d'exportation. |
| merge_layers | bool | r/w | Obtient ou définit une valeur indiquant si [merege layers]. |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode/) | r/w | Obtient ou définit le mode. |
| output_layers_names | string[] | r/w | Obtient ou définit les noms des calques de sortie (fonctionne si le format d'exportation prend en charge le nommage des calques, par exemple pour Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rastérisation de la page. |
| page_titles | string[] | r/w | Obtient ou définit les titres de la page. |
| pages | int[] | r/w | Obtient ou définit les pages. |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) | r/w | Obtient ou définit l'intervalle de temps. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_int_range(range)](#create_with_int_range_range_1) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [init_pages(ranges)](#init_pages_ranges_11) | Initialise les pages à partir du tableau de plages |


### Constructor: DjvuMultiPageOptions() {#DjvuMultiPageOptions__1}


```
 DjvuMultiPageOptions() 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

### Constructor: DjvuMultiPageOptions(page) {#DjvuMultiPageOptions_page_2}


```
 DjvuMultiPageOptions(page) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int |  |

### Constructor: DjvuMultiPageOptions(page, export_area) {#DjvuMultiPageOptions_page_export_area_3}


```
 DjvuMultiPageOptions(page, export_area) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

### Constructor: DjvuMultiPageOptions(pages) {#DjvuMultiPageOptions_pages_4}


```
 DjvuMultiPageOptions(pages) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int[] | Les index des pages. |

### Constructor: DjvuMultiPageOptions(pages, export_area) {#DjvuMultiPageOptions_pages_export_area_5}


```
 DjvuMultiPageOptions(pages, export_area) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int[] | Les index des pages. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

### Constructor: DjvuMultiPageOptions(range) {#DjvuMultiPageOptions_range_6}


```
 DjvuMultiPageOptions(range) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | La plage. |

### Constructor: DjvuMultiPageOptions(range, export_area) {#DjvuMultiPageOptions_range_export_area_7}


```
 DjvuMultiPageOptions(range, export_area) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | La plage. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

### Constructor: DjvuMultiPageOptions(ranges) {#DjvuMultiPageOptions_ranges_8}


```
 DjvuMultiPageOptions(ranges) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | La plage. |

### Constructor: DjvuMultiPageOptions(ranges, export_area) {#DjvuMultiPageOptions_ranges_export_area_9}


```
 DjvuMultiPageOptions(ranges, export_area) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | La plage. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | La plage. |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | La plage. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | La plage. |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | La plage. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int | L'index de page. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int[] | Les index des pages. |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Initialise une nouvelle instance de la classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int[] | Les index des pages. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_9}


```
 create_with_page_titles(page_titles) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page_titles | string[] | Les titres de page. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_10}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page_titles | string[] | Les titres de page. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: init_pages(ranges) {#init_pages_ranges_11}


```
 init_pages(ranges) 
```

Initialise les pages à partir du tableau de plages

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Les plages. |

