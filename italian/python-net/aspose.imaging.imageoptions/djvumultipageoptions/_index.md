---
title: "Classe DjvuMultiPageOptions"
type: docs
weight: 70
url: /it/python-net/aspose.imaging.imageoptions/djvumultipageoptions/
---

**Summary:** The API for DjVu graphics file format provides developers with seamless access<br/>            to DjVu documents, ideal for scanned documents and books. With image loading<br/>            options, developers can effortlessly integrate DjVu files into their applications,<br/>            unlocking the potential to work with multi-page content, including text,<br/>            drawings, and images, for versatile document processing solutions.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DjvuMultiPageOptions

**Inheritance:** MultiPageOptions

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [DjvuMultiPageOptions()](#DjvuMultiPageOptions__1) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page)](#DjvuMultiPageOptions_page_2) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page, export_area)](#DjvuMultiPageOptions_page_export_area_3) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages)](#DjvuMultiPageOptions_pages_4) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages, export_area)](#DjvuMultiPageOptions_pages_export_area_5) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range)](#DjvuMultiPageOptions_range_6) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range, export_area)](#DjvuMultiPageOptions_range_export_area_7) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges)](#DjvuMultiPageOptions_ranges_8) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges, export_area)](#DjvuMultiPageOptions_ranges_export_area_9) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
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
| [create_with_int_range(range)](#create_with_int_range_range_1) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Inizializza una nuova istanza della classe [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [init_pages(ranges)](#init_pages_ranges_11) | Inizializza le pagine dall'array di intervalli |


### Constructor: DjvuMultiPageOptions() {#DjvuMultiPageOptions__1}


```
 DjvuMultiPageOptions() 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

### Constructor: DjvuMultiPageOptions(page) {#DjvuMultiPageOptions_page_2}


```
 DjvuMultiPageOptions(page) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pagina | int |  |

### Constructor: DjvuMultiPageOptions(page, export_area) {#DjvuMultiPageOptions_page_export_area_3}


```
 DjvuMultiPageOptions(page, export_area) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pagina | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

### Constructor: DjvuMultiPageOptions(pages) {#DjvuMultiPageOptions_pages_4}


```
 DjvuMultiPageOptions(pages) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pages | int[] | Gli indici delle pagine. |

### Constructor: DjvuMultiPageOptions(pages, export_area) {#DjvuMultiPageOptions_pages_export_area_5}


```
 DjvuMultiPageOptions(pages, export_area) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pages | int[] | Gli indici delle pagine. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

### Constructor: DjvuMultiPageOptions(range) {#DjvuMultiPageOptions_range_6}


```
 DjvuMultiPageOptions(range) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | L'intervallo. |

### Constructor: DjvuMultiPageOptions(range, export_area) {#DjvuMultiPageOptions_range_export_area_7}


```
 DjvuMultiPageOptions(range, export_area) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | L'intervallo. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

### Constructor: DjvuMultiPageOptions(ranges) {#DjvuMultiPageOptions_ranges_8}


```
 DjvuMultiPageOptions(ranges) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | L'intervallo. |

### Constructor: DjvuMultiPageOptions(ranges, export_area) {#DjvuMultiPageOptions_ranges_export_area_9}


```
 DjvuMultiPageOptions(ranges, export_area) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | L'intervallo. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | L'intervallo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | L'intervallo. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | L'intervallo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | L'intervallo. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pagina | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pagina | int | L'indice della pagina. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pages | int[] | Gli indici delle pagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Inizializza una nuova istanza della classe [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pages | int[] | Gli indici delle pagine. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


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

