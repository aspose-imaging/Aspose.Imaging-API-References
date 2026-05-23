---
title: "Класс DjvuMultiPageOptions"
type: docs
weight: 70
url: /ru/python-net/aspose.imaging.imageoptions/djvumultipageoptions/
---

**Summary:** The API for DjVu graphics file format provides developers with seamless access<br/>            to DjVu documents, ideal for scanned documents and books. With image loading<br/>            options, developers can effortlessly integrate DjVu files into their applications,<br/>            unlocking the potential to work with multi-page content, including text,<br/>            drawings, and images, for versatile document processing solutions.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DjvuMultiPageOptions

**Inheritance:** MultiPageOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DjvuMultiPageOptions()](#DjvuMultiPageOptions__1) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [DjvuMultiPageOptions(page)](#DjvuMultiPageOptions_page_2) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [DjvuMultiPageOptions(page, export_area)](#DjvuMultiPageOptions_page_export_area_3) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [DjvuMultiPageOptions(pages)](#DjvuMultiPageOptions_pages_4) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [DjvuMultiPageOptions(pages, export_area)](#DjvuMultiPageOptions_pages_export_area_5) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [DjvuMultiPageOptions(range)](#DjvuMultiPageOptions_range_6) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [DjvuMultiPageOptions(range, export_area)](#DjvuMultiPageOptions_range_export_area_7) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [DjvuMultiPageOptions(ranges)](#DjvuMultiPageOptions_ranges_8) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [DjvuMultiPageOptions(ranges, export_area)](#DjvuMultiPageOptions_ranges_export_area_9) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает область экспорта. |
| merge_layers | bool | r/w | Получает или задает значение, указывающее, [merege layers]. |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode/) | r/w | Получает или задает режим. |
| output_layers_names | string[] | r/w | Получает или задает имена выходных слоев(Работает, если формат экспорта поддерживает именование слоев, например для Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Получает или задает параметры растеризации страницы. |
| page_titles | string[] | r/w | Получает или задает заголовки страниц. |
| страницы | int[] | r/w | Получает или задает страницы. |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) | r/w | Получает или задает временной интервал. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_int_range(range)](#create_with_int_range_range_1) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Инициализирует новый экземпляр класса [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Инициализирует новый экземпляр класса [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [init_pages(ranges)](#init_pages_ranges_11) | Инициализирует страницы из массива диапазонов |


### Constructor: DjvuMultiPageOptions() {#DjvuMultiPageOptions__1}


```
 DjvuMultiPageOptions() 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

### Constructor: DjvuMultiPageOptions(page) {#DjvuMultiPageOptions_page_2}


```
 DjvuMultiPageOptions(page) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| страница | int |  |

### Constructor: DjvuMultiPageOptions(page, export_area) {#DjvuMultiPageOptions_page_export_area_3}


```
 DjvuMultiPageOptions(page, export_area) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| страница | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область экспорта. |

### Constructor: DjvuMultiPageOptions(pages) {#DjvuMultiPageOptions_pages_4}


```
 DjvuMultiPageOptions(pages) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| страницы | int[] | Индексы страниц. |

### Constructor: DjvuMultiPageOptions(pages, export_area) {#DjvuMultiPageOptions_pages_export_area_5}


```
 DjvuMultiPageOptions(pages, export_area) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| страницы | int[] | Индексы страниц. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область экспорта. |

### Constructor: DjvuMultiPageOptions(range) {#DjvuMultiPageOptions_range_6}


```
 DjvuMultiPageOptions(range) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Диапазон. |

### Constructor: DjvuMultiPageOptions(range, export_area) {#DjvuMultiPageOptions_range_export_area_7}


```
 DjvuMultiPageOptions(range, export_area) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Диапазон. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область экспорта. |

### Constructor: DjvuMultiPageOptions(ranges) {#DjvuMultiPageOptions_ranges_8}


```
 DjvuMultiPageOptions(ranges) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Диапазон. |

### Constructor: DjvuMultiPageOptions(ranges, export_area) {#DjvuMultiPageOptions_ranges_export_area_9}


```
 DjvuMultiPageOptions(ranges, export_area) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Диапазон. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область экспорта. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Диапазон. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Диапазон. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область экспорта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Диапазон. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Диапазон. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область экспорта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| страница | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| страница | int | Индекс страницы. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область экспорта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| страницы | int[] | Индексы страниц. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Инициализирует новый экземпляр класса [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| страницы | int[] | Индексы страниц. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область экспорта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_9}


```
 create_with_page_titles(page_titles) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_titles | string[] | Заголовки страниц. |

**Returns**

| Тип | Описание |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_10}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_titles | string[] | Заголовки страниц. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область экспорта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: init_pages(ranges) {#init_pages_ranges_11}


```
 init_pages(ranges) 
```

Инициализирует страницы из массива диапазонов

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Диапазоны. |

