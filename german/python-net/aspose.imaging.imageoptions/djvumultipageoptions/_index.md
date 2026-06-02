---
title: "DjvuMultiPageOptions Klasse"
type: docs
weight: 70
url: /de/python-net/aspose.imaging.imageoptions/djvumultipageoptions/
---

**Summary:** The API for DjVu graphics file format provides developers with seamless access<br/>            to DjVu documents, ideal for scanned documents and books. With image loading<br/>            options, developers can effortlessly integrate DjVu files into their applications,<br/>            unlocking the potential to work with multi-page content, including text,<br/>            drawings, and images, for versatile document processing solutions.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DjvuMultiPageOptions

**Inheritance:** MultiPageOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [DjvuMultiPageOptions()](#DjvuMultiPageOptions__1) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page)](#DjvuMultiPageOptions_page_2) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(page, export_area)](#DjvuMultiPageOptions_page_export_area_3) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages)](#DjvuMultiPageOptions_pages_4) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(pages, export_area)](#DjvuMultiPageOptions_pages_export_area_5) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range)](#DjvuMultiPageOptions_range_6) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(range, export_area)](#DjvuMultiPageOptions_range_export_area_7) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges)](#DjvuMultiPageOptions_ranges_8) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [DjvuMultiPageOptions(ranges, export_area)](#DjvuMultiPageOptions_ranges_export_area_9) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt den Exportbereich. |
| merge_layers | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [merege layers]. |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode/) | r/w | Liest oder setzt den Modus. |
| output_layers_names | string[] | r/w | Liest oder setzt die Namen der Ausgabelayer(Funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Liest oder setzt die Seitenrasterisierungsoptionen. |
| page_titles | string[] | r/w | Liest oder setzt die Seitentitel. |
| Seiten | int[] | r/w | Liest oder legt die Seiten fest. |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) | r/w | Liest oder legt das Zeitintervall fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_with_int_range(range)](#create_with_int_range_range_1) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/). |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [init_pages(ranges)](#init_pages_ranges_11) | Initialisiert die Seiten aus dem Bereichsarray. |


### Constructor: DjvuMultiPageOptions() {#DjvuMultiPageOptions__1}


```
 DjvuMultiPageOptions() 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

### Constructor: DjvuMultiPageOptions(page) {#DjvuMultiPageOptions_page_2}


```
 DjvuMultiPageOptions(page) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seite | int |  |

### Constructor: DjvuMultiPageOptions(page, export_area) {#DjvuMultiPageOptions_page_export_area_3}


```
 DjvuMultiPageOptions(page, export_area) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seite | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

### Constructor: DjvuMultiPageOptions(pages) {#DjvuMultiPageOptions_pages_4}


```
 DjvuMultiPageOptions(pages) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seiten | int[] | Die Seitenindizes. |

### Constructor: DjvuMultiPageOptions(pages, export_area) {#DjvuMultiPageOptions_pages_export_area_5}


```
 DjvuMultiPageOptions(pages, export_area) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seiten | int[] | Die Seitenindizes. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

### Constructor: DjvuMultiPageOptions(range) {#DjvuMultiPageOptions_range_6}


```
 DjvuMultiPageOptions(range) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Der Bereich. |

### Constructor: DjvuMultiPageOptions(range, export_area) {#DjvuMultiPageOptions_range_export_area_7}


```
 DjvuMultiPageOptions(range, export_area) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Der Bereich. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

### Constructor: DjvuMultiPageOptions(ranges) {#DjvuMultiPageOptions_ranges_8}


```
 DjvuMultiPageOptions(ranges) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Der Bereich. |

### Constructor: DjvuMultiPageOptions(ranges, export_area) {#DjvuMultiPageOptions_ranges_export_area_9}


```
 DjvuMultiPageOptions(ranges, export_area) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Der Bereich. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Der Bereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Der Bereich. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Der Bereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Der Bereich. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seite | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seite | int | Der Seitenindex. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seiten | int[] | Die Seitenindizes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Initialisiert eine neue Instanz der Klasse [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seiten | int[] | Die Seitenindizes. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_9}


```
 create_with_page_titles(page_titles) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_titles | string[] | Die Seitentitel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_10}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_titles | string[] | Die Seitentitel. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: init_pages(ranges) {#init_pages_ranges_11}


```
 init_pages(ranges) 
```

Initialisiert die Seiten aus dem Bereichsarray.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Die Bereiche. |

