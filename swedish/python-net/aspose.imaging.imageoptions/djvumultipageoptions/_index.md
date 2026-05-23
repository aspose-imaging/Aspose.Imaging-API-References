---
title: "DjvuMultiPageOptions klass"
type: docs
weight: 70
url: /sv/python-net/aspose.imaging.imageoptions/djvumultipageoptions/
---

**Summary:** The API for DjVu graphics file format provides developers with seamless access<br/>            to DjVu documents, ideal for scanned documents and books. With image loading<br/>            options, developers can effortlessly integrate DjVu files into their applications,<br/>            unlocking the potential to work with multi-page content, including text,<br/>            drawings, and images, for versatile document processing solutions.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DjvuMultiPageOptions

**Inheritance:** MultiPageOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DjvuMultiPageOptions()](#DjvuMultiPageOptions__1) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page)](#DjvuMultiPageOptions_page_2) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page, export_area)](#DjvuMultiPageOptions_page_export_area_3) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages)](#DjvuMultiPageOptions_pages_4) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages, export_area)](#DjvuMultiPageOptions_pages_export_area_5) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range)](#DjvuMultiPageOptions_range_6) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range, export_area)](#DjvuMultiPageOptions_range_export_area_7) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges)](#DjvuMultiPageOptions_ranges_8) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges, export_area)](#DjvuMultiPageOptions_ranges_export_area_9) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger exportområdet. |
| merge_layers | bool | r/w | Hämtar eller anger ett värde som indikerar om [merege layers]. |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode/) | r/w | Hämtar eller anger läget. |
| output_layers_names | string[] | r/w | Hämtar eller anger namn på utdata lager (Fungerar om exportformatet stödjer lagernamngivning, till exempel för Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger sidans rasteriseringsalternativ. |
| page_titles | string[] | r/w | Hämtar eller anger sidtitlar. |
| pages | int[] | r/w | Hämtar eller anger sidorna. |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) | r/w | Hämtar eller anger tidsintervallet. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_int_range(range)](#create_with_int_range_range_1) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [init_pages(ranges)](#init_pages_ranges_11) | Initierar sidorna från intervallarrayen |


### Constructor: DjvuMultiPageOptions() {#DjvuMultiPageOptions__1}


```
 DjvuMultiPageOptions() 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

### Constructor: DjvuMultiPageOptions(page) {#DjvuMultiPageOptions_page_2}


```
 DjvuMultiPageOptions(page) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sida | int |  |

### Constructor: DjvuMultiPageOptions(page, export_area) {#DjvuMultiPageOptions_page_export_area_3}


```
 DjvuMultiPageOptions(page, export_area) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sida | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

### Constructor: DjvuMultiPageOptions(pages) {#DjvuMultiPageOptions_pages_4}


```
 DjvuMultiPageOptions(pages) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int[] | Sidornas index. |

### Constructor: DjvuMultiPageOptions(pages, export_area) {#DjvuMultiPageOptions_pages_export_area_5}


```
 DjvuMultiPageOptions(pages, export_area) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int[] | Sidornas index. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

### Constructor: DjvuMultiPageOptions(range) {#DjvuMultiPageOptions_range_6}


```
 DjvuMultiPageOptions(range) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Intervallet. |

### Constructor: DjvuMultiPageOptions(range, export_area) {#DjvuMultiPageOptions_range_export_area_7}


```
 DjvuMultiPageOptions(range, export_area) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Intervallet. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

### Constructor: DjvuMultiPageOptions(ranges) {#DjvuMultiPageOptions_ranges_8}


```
 DjvuMultiPageOptions(ranges) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Intervallet. |

### Constructor: DjvuMultiPageOptions(ranges, export_area) {#DjvuMultiPageOptions_ranges_export_area_9}


```
 DjvuMultiPageOptions(ranges, export_area) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Intervallet. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Intervallet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Intervallet. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Intervallet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Intervallet. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sida | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sida | int | Sidindexet. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int[] | Sidornas index. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Initierar en ny instans av klassen [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int[] | Sidornas index. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_9}


```
 create_with_page_titles(page_titles) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_titles | string[] | Sidtitlar. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_10}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_titles | string[] | Sidtitlar. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: init_pages(ranges) {#init_pages_ranges_11}


```
 init_pages(ranges) 
```

Initierar sidorna från intervallarrayen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Intervallen. |

