---
title: "MultiPageOptions 类"
type: docs
weight: 190
url: /zh/python-net/aspose.imaging.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MultiPageOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置导出区域。 |
| merge_layers | bool | r/w | 获取或设置一个值，指示是否 [merege layers]。 |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode/) | r/w | 获取或设置模式。 |
| output_layers_names | string[] | r/w | 获取或设置输出图层名称（如果导出格式支持图层命名，则有效，例如针对 Psd） |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置页面光栅化选项。 |
| page_titles | string[] | r/w | 获取或设置页面标题。 |
| pages | int[] | r/w | 获取或设置页面。 |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) | r/w | 获取或设置时间间隔。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_int_range(range)](#create_with_int_range_range_1) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_page_number(page)](#create_with_page_number_page_5) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [init_pages(ranges)](#init_pages_ranges_11) | 从范围数组初始化页面 |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 页面 | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 页面 | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| page_titles | string[] | 页面标题。 |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| page_titles | string[] | 页面标题。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pages | int[] | 页面。 |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pages | int[] | 页面数组。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | 该 [IntRange](/imaging/python-net/aspose.imaging/intrange/)。 |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | 该 [IntRange](/imaging/python-net/aspose.imaging/intrange/)。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
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

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | 该 [IntRange](/imaging/python-net/aspose.imaging/intrange/)。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | 该 [IntRange](/imaging/python-net/aspose.imaging/intrange/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | 该 [IntRange](/imaging/python-net/aspose.imaging/intrange/)。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 页面 | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 页面 | int | 页面索引。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pages | int[] | 页面。 |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pages | int[] | 页面数组。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_9}


```
 create_with_page_titles(page_titles) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| page_titles | string[] | 页面标题。 |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_10}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| page_titles | string[] | 页面标题。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: init_pages(ranges) {#init_pages_ranges_11}


```
 init_pages(ranges) 
```

从范围数组初始化页面

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | 范围。 |

