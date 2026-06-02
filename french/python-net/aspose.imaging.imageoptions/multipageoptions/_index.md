---
title: "Classe MultiPageOptions"
type: docs
weight: 190
url: /fr/python-net/aspose.imaging.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MultiPageOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
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
| [create_with_int_range(range)](#create_with_int_range_range_1) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [init_pages(ranges)](#init_pages_ranges_11) | Initialise les pages à partir du tableau de plages |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page_titles | string[] | Les titres de page. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page_titles | string[] | Les titres de page. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int[] | Les pages. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int[] | Le tableau de pages. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Le [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Le [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Le [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Le [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Le [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int | L'index de page. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int[] | Les pages. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int[] | Le tableau de pages. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone d'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


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

