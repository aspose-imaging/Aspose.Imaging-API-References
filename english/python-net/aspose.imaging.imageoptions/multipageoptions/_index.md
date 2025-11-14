---
title: MultiPageOptions Class
type: docs
weight: 190
url: /python-net/aspose.imaging.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MultiPageOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets the export area. |
| merge_layers | bool | r/w | Gets or sets a value indicating whether [merege layers]. |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode/) | r/w | Gets or sets the mode. |
| output_layers_names | string[] | r/w | Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Gets or sets the page rasterization options. |
| page_titles | string[] | r/w | Gets or sets the page titles. |
| pages | int[] | r/w | Gets or sets the pages. |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) | r/w | Gets or sets the time interval. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_int_range(range)](#create_with_int_range_range_1) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class. |
| [init_pages(ranges)](#init_pages_ranges_11) | Initializes the pages from ranges array |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page_titles | string[] | The page titles. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page_titles | string[] | The page titles. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pages | int[] | The pages. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pages | int[] | The array of pages. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | The [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | The [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
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

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | The [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | The [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | The [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


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
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | int | The page index. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pages | int[] | The pages. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pages | int[] | The array of pages. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_9}


```
 create_with_page_titles(page_titles) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page_titles | string[] | The page titles. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_10}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

Initializes a new instance of the [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page_titles | string[] | The page titles. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The export area. |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: init_pages(ranges) {#init_pages_ranges_11}


```
 init_pages(ranges) 
```

Initializes the pages from ranges array

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | The ranges. |

