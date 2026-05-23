---
title: "MultiPageOptions-klass"
type: docs
weight: 190
url: /sv/python-net/aspose.imaging.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MultiPageOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
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
| [create_with_int_range(range)](#create_with_int_range_range_1) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/). |
| [init_pages(ranges)](#init_pages_ranges_11) | Initierar sidorna från intervallarrayen |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sida | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sida | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_titles | string[] | Sidtitlar. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_titles | string[] | Sidtitlar. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int[] | Sidorna. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int[] | Arrayen av sidor. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Det [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Det [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Det [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Det [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Det [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sida | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sida | int | Sidindexet. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int[] | Sidorna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int[] | Arrayen av sidor. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Exportområdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


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

