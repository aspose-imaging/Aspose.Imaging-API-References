---
title: "MultiPageOptions Klasse"
type: docs
weight: 190
url: /de/python-net/aspose.imaging.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MultiPageOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
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
| [create_with_int_range(range)](#create_with_int_range_range_1) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse. |
| [init_pages(ranges)](#init_pages_ranges_11) | Initialisiert die Seiten aus dem Bereichsarray. |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seite | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seite | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_titles | string[] | Die Seitentitel. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_titles | string[] | Die Seitentitel. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seiten | int[] | Die Seiten. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seiten | int[] | Das Array von Seiten. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Der [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Der [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Der [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Der [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Der [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seite | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seite | int | Der Seitenindex. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seiten | int[] | Die Seiten. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Seiten | int[] | Das Array von Seiten. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Exportbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


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

