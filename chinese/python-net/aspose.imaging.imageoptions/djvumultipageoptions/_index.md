---
title: "DjvuMultiPageOptions 类"
type: docs
weight: 70
url: /zh/python-net/aspose.imaging.imageoptions/djvumultipageoptions/
---

**Summary:** The API for DjVu graphics file format provides developers with seamless access<br/>            to DjVu documents, ideal for scanned documents and books. With image loading<br/>            options, developers can effortlessly integrate DjVu files into their applications,<br/>            unlocking the potential to work with multi-page content, including text,<br/>            drawings, and images, for versatile document processing solutions.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DjvuMultiPageOptions

**Inheritance:** MultiPageOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [DjvuMultiPageOptions()](#DjvuMultiPageOptions__1) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [DjvuMultiPageOptions(page)](#DjvuMultiPageOptions_page_2) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [DjvuMultiPageOptions(page, export_area)](#DjvuMultiPageOptions_page_export_area_3) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [DjvuMultiPageOptions(pages)](#DjvuMultiPageOptions_pages_4) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [DjvuMultiPageOptions(pages, export_area)](#DjvuMultiPageOptions_pages_export_area_5) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [DjvuMultiPageOptions(range)](#DjvuMultiPageOptions_range_6) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [DjvuMultiPageOptions(range, export_area)](#DjvuMultiPageOptions_range_export_area_7) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [DjvuMultiPageOptions(ranges)](#DjvuMultiPageOptions_ranges_8) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [DjvuMultiPageOptions(ranges, export_area)](#DjvuMultiPageOptions_ranges_export_area_9) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
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
| [create_with_int_range(range)](#create_with_int_range_range_1) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [create_with_page_number(page)](#create_with_page_number_page_5) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | 初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。 |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | 初始化 [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) 类的新实例。 |
| [init_pages(ranges)](#init_pages_ranges_11) | 从范围数组初始化页面 |


### Constructor: DjvuMultiPageOptions() {#DjvuMultiPageOptions__1}


```
 DjvuMultiPageOptions() 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

### Constructor: DjvuMultiPageOptions(page) {#DjvuMultiPageOptions_page_2}


```
 DjvuMultiPageOptions(page) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 页面 | int |  |

### Constructor: DjvuMultiPageOptions(page, export_area) {#DjvuMultiPageOptions_page_export_area_3}


```
 DjvuMultiPageOptions(page, export_area) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 页面 | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

### Constructor: DjvuMultiPageOptions(pages) {#DjvuMultiPageOptions_pages_4}


```
 DjvuMultiPageOptions(pages) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pages | int[] | 页面索引。 |

### Constructor: DjvuMultiPageOptions(pages, export_area) {#DjvuMultiPageOptions_pages_export_area_5}


```
 DjvuMultiPageOptions(pages, export_area) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pages | int[] | 页面索引。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

### Constructor: DjvuMultiPageOptions(range) {#DjvuMultiPageOptions_range_6}


```
 DjvuMultiPageOptions(range) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | 范围。 |

### Constructor: DjvuMultiPageOptions(range, export_area) {#DjvuMultiPageOptions_range_export_area_7}


```
 DjvuMultiPageOptions(range, export_area) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | 范围。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

### Constructor: DjvuMultiPageOptions(ranges) {#DjvuMultiPageOptions_ranges_8}


```
 DjvuMultiPageOptions(ranges) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | 范围。 |

### Constructor: DjvuMultiPageOptions(ranges, export_area) {#DjvuMultiPageOptions_ranges_export_area_9}


```
 DjvuMultiPageOptions(ranges, export_area) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | 范围。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | 范围。 |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | 范围。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | 范围。 |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | 范围。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 页面 | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 页面 | int | 页面索引。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pages | int[] | 页面索引。 |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

初始化一个新的 [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pages | int[] | 页面索引。 |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 导出区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuMultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/djvumultipageoptions/) |  |


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

