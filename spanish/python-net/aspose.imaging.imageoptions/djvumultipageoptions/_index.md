---
title: "DjvuMultiPageOptions Clase"
type: docs
weight: 70
url: /es/python-net/aspose.imaging.imageoptions/djvumultipageoptions/
---

**Summary:** The API for DjVu graphics file format provides developers with seamless access<br/>            to DjVu documents, ideal for scanned documents and books. With image loading<br/>            options, developers can effortlessly integrate DjVu files into their applications,<br/>            unlocking the potential to work with multi-page content, including text,<br/>            drawings, and images, for versatile document processing solutions.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DjvuMultiPageOptions

**Inheritance:** MultiPageOptions

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [DjvuMultiPageOptions()](#DjvuMultiPageOptions__1) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page)](#DjvuMultiPageOptions_page_2) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page, export_area)](#DjvuMultiPageOptions_page_export_area_3) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages)](#DjvuMultiPageOptions_pages_4) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages, export_area)](#DjvuMultiPageOptions_pages_export_area_5) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range)](#DjvuMultiPageOptions_range_6) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range, export_area)](#DjvuMultiPageOptions_range_export_area_7) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges)](#DjvuMultiPageOptions_ranges_8) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges, export_area)](#DjvuMultiPageOptions_ranges_export_area_9) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece el área de exportación. |
| merge_layers | bool | r/w | Obtiene o establece un valor que indica si [merege layers]. |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode/) | r/w | Obtiene o establece el modo. |
| output_layers_names | string[] | r/w | Obtiene o establece los nombres de capas de salida (Funciona si el formato de exportación admite la denominación de capas, por ejemplo para Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtiene o establece las opciones de rasterización de la página. |
| page_titles | string[] | r/w | Obtiene o establece los títulos de la página. |
| pages | int[] | r/w | Obtiene o establece las páginas. |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) | r/w | Obtiene o establece el intervalo de tiempo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_with_int_range(range)](#create_with_int_range_range_1) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Inicializa una nueva instancia de la clase [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Inicializa una nueva instancia de la clase [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [init_pages(ranges)](#init_pages_ranges_11) | Inicializa las páginas a partir del arreglo de rangos |


### Constructor: DjvuMultiPageOptions() {#DjvuMultiPageOptions__1}


```
 DjvuMultiPageOptions() 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

### Constructor: DjvuMultiPageOptions(page) {#DjvuMultiPageOptions_page_2}


```
 DjvuMultiPageOptions(page) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| página | int |  |

### Constructor: DjvuMultiPageOptions(page, export_area) {#DjvuMultiPageOptions_page_export_area_3}


```
 DjvuMultiPageOptions(page, export_area) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| página | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de exportación. |

### Constructor: DjvuMultiPageOptions(pages) {#DjvuMultiPageOptions_pages_4}


```
 DjvuMultiPageOptions(pages) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pages | int[] | Los índices de las páginas. |

### Constructor: DjvuMultiPageOptions(pages, export_area) {#DjvuMultiPageOptions_pages_export_area_5}


```
 DjvuMultiPageOptions(pages, export_area) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pages | int[] | Los índices de las páginas. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de exportación. |

### Constructor: DjvuMultiPageOptions(range) {#DjvuMultiPageOptions_range_6}


```
 DjvuMultiPageOptions(range) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | El rango. |

### Constructor: DjvuMultiPageOptions(range, export_area) {#DjvuMultiPageOptions_range_export_area_7}


```
 DjvuMultiPageOptions(range, export_area) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | El rango. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de exportación. |

### Constructor: DjvuMultiPageOptions(ranges) {#DjvuMultiPageOptions_ranges_8}


```
 DjvuMultiPageOptions(ranges) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | El rango. |

### Constructor: DjvuMultiPageOptions(ranges, export_area) {#DjvuMultiPageOptions_ranges_export_area_9}


```
 DjvuMultiPageOptions(ranges, export_area) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | El rango. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de exportación. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | El rango. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | El rango. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de exportación. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | El rango. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | El rango. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de exportación. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| página | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| página | int | El índice de página. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de exportación. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pages | int[] | Los índices de las páginas. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Inicializa una nueva instancia de la clase [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pages | int[] | Los índices de las páginas. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de exportación. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_9}


```
 create_with_page_titles(page_titles) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_titles | string[] | Los títulos de página. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_10}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_titles | string[] | Los títulos de página. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de exportación. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: init_pages(ranges) {#init_pages_ranges_11}


```
 init_pages(ranges) 
```

Inicializa las páginas a partir del arreglo de rangos

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Los rangos. |

