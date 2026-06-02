---
title: "Classe MultiPageOptions"
type: docs
weight: 190
url: /it/python-net/aspose.imaging.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MultiPageOptions

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta l'area di esportazione. |
| merge_layers | bool | r/w | Ottiene o imposta un valore che indica se [merege layers]. |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode/) | r/w | Ottiene o imposta la modalità. |
| output_layers_names | string[] | r/w | Ottiene o imposta i nomi dei livelli di output (Funziona se il formato di esportazione supporta la denominazione dei livelli, ad esempio per Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione della pagina. |
| page_titles | string[] | r/w | Ottiene o imposta i titoli della pagina. |
| pages | int[] | r/w | Ottiene o imposta le pagine. |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) | r/w | Ottiene o imposta l'intervallo di tempo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_with_int_range(range)](#create_with_int_range_range_1) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [init_pages(ranges)](#init_pages_ranges_11) | Inizializza le pagine dall'array di intervalli |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pagina | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pagina | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_titles | string[] | I titoli delle pagine. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_titles | string[] | I titoli delle pagine. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pages | int[] | Le pagine. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pages | int[] | L'array di pagine. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | L'[IntRange](/imaging/python-net/aspose.imaging/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | L'[IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | L'[IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | L'[IntRange](/imaging/python-net/aspose.imaging/intrange/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | L'[IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pagina | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pagina | int | L'indice della pagina. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pages | int[] | Le pagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pages | int[] | L'array di pagine. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_9}


```
 create_with_page_titles(page_titles) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_titles | string[] | I titoli delle pagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_10}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_titles | string[] | I titoli delle pagine. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: init_pages(ranges) {#init_pages_ranges_11}


```
 init_pages(ranges) 
```

Inizializza le pagine dall'array di intervalli

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Gli intervalli. |

