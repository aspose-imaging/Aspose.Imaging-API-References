---
title: MultiPageOptions Class
type: docs
weight: 190
url: /python-net/aspose.imaging.imageoptions/multipageoptions/
---

Base class for multiple pages supported formats

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MultiPageOptions

**Aspose.Imaging Version:** 23.6

The MultiPageOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__0) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_1) | Initializes a new instance of the MultiPageOptions class |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_2) | Initializes a new instance of the MultiPageOptions class |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_3) | Initializes a new instance of the MultiPageOptions class |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_4) | Initializes a new instance of the MultiPageOptions class |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_5) | Initializes a new instance of the MultiPageOptions class |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_6) | Initializes a new instance of the MultiPageOptions class |
| [MultiPageOptions(range)](#MultiPageOptions_range_7) | Initializes a new instance of the MultiPageOptions class |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_8) | Initializes a new instance of the MultiPageOptions class |
| [MultiPageOptions(page)](#MultiPageOptions_page_9) | Initializes a new instance of the MultiPageOptions class |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_10) | Initializes a new instance of the MultiPageOptions class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| pages | int | r/w | Gets or sets the pages. |
| page_titles | string | r/w | Gets or sets the page titles. |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval) | r/w | Gets or sets the time interval. |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the page rasterization options. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets the export area. |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode) | r/w | Gets or sets the mode. |
| output_layers_names | string | r/w | Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd) |
| merge_layers | bool | r/w | Gets or sets a value indicating whether [merege layers]. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_11) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_12) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_13) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_14) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_15) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_16) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_int_range(range)](#create_with_int_range_range_17) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_18) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_number(page)](#create_with_page_number_page_19) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_20) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [init_pages(ranges)](#init_pages_ranges_21) | Initializes the pages from ranges array |

### MultiPageOptions() {#MultiPageOptions__0}


```
 MultiPageOptions() 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

### MultiPageOptions(pages) {#MultiPageOptions_pages_1}


```
 MultiPageOptions(pages) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pages | int |  |

### MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_2}


```
 MultiPageOptions(pages, export_area) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pages | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) |  |

### MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_3}


```
 MultiPageOptions(page_titles) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page_titles | string |  |

### MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_4}


```
 MultiPageOptions(page_titles, export_area) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page_titles | string |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) |  |

### MultiPageOptions(ranges) {#MultiPageOptions_ranges_5}


```
 MultiPageOptions(ranges) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange) |  |

### MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_6}


```
 MultiPageOptions(ranges, export_area) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange) |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) |  |

### MultiPageOptions(range) {#MultiPageOptions_range_7}


```
 MultiPageOptions(range) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange) |  |

### MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_8}


```
 MultiPageOptions(range, export_area) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange) |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) |  |

### MultiPageOptions(page) {#MultiPageOptions_page_9}


```
 MultiPageOptions(page) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | int |  |

### MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_10}


```
 MultiPageOptions(page, export_area) 
```

Initializes a new instance of the MultiPageOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) |  |

### create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_11}


```
 create_with_page_numbers(pages) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pages | int | The pages. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_12}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pages | int | The array of pages. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_13}


```
 create_with_page_titles(page_titles) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page_titles | string | The page titles. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_14}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page_titles | string | The page titles. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_15}


```
 create_with_int_ranges(ranges) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange) | The [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_16}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange) | The [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### create_with_int_range(range)  [static] {#create_with_int_range_range_17}


```
 create_with_int_range(range) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange) |  |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_18}


```
 create_with_int_range_rect(range, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange) | The [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### create_with_page_number(page)  [static] {#create_with_page_number_page_19}


```
 create_with_page_number(page) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_20}


```
 create_with_page_number_rect(page, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | int | The page index. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) |  |


### init_pages(ranges) {#init_pages_ranges_21}


```
 init_pages(ranges) 
```

Initializes the pages from ranges array

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange) | The ranges. |

