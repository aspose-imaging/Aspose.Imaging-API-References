---
title: "MultiPageOptions Sınıfı"
type: docs
weight: 190
url: /tr/python-net/aspose.imaging.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MultiPageOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Dışa aktarma alanını alır veya ayarlar. |
| merge_layers | bool | r/w | Bir değeri alır veya ayarlar; bu değer [merege layers] olup olmadığını gösterir. |
| mode | [MultiPageMode](/imaging/python-net/aspose.imaging.imageoptions/multipagemode/) | r/w | Modu alır veya ayarlar. |
| output_layers_names | string[] | r/w | Çıktı katman adlarını alır veya ayarlar(Çıktı formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için). |
| page_rasterization_options | [VectorRasterizationOptions[]](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Sayfa rasterleştirme seçeneklerini alır veya ayarlar. |
| page_titles | string[] | r/w | Sayfa başlıklarını alır veya ayarlar. |
| sayfalar | int[] | r/w | Sayfaları alır veya ayarlar. |
| time_interval | [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) | r/w | Zaman aralığını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_int_range(range)](#create_with_int_range_range_1) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [create_with_int_range_rect(range, export_area)](#create_with_int_range_rect_range_export_area_2) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [create_with_int_ranges(ranges)](#create_with_int_ranges_ranges_3) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [create_with_int_ranges_rect(ranges, export_area)](#create_with_int_ranges_rect_ranges_export_area_4) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [create_with_page_number(page)](#create_with_page_number_page_5) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [create_with_page_number_rect(page, export_area)](#create_with_page_number_rect_page_export_area_6) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [create_with_page_numbers(pages)](#create_with_page_numbers_pages_7) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [create_with_page_numbers_rect(pages, export_area)](#create_with_page_numbers_rect_pages_export_area_8) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [create_with_page_titles(page_titles)](#create_with_page_titles_page_titles_9) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [create_with_page_titles_rect(page_titles, export_area)](#create_with_page_titles_rect_page_titles_export_area_10) | Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır. |
| [init_pages(ranges)](#init_pages_ranges_11) | Sayfaları aralıklar dizisinden başlatır |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sayfa | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sayfa | int |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| page_titles | string[] | Sayfa başlıkları. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| page_titles | string[] | Sayfa başlıkları. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sayfalar | int[] | Sayfalar. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sayfalar | int[] | Sayfalar dizisi. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Bu [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Bu [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

### Method: create_with_int_range(range)  [static] {#create_with_int_range_range_1}


```
 create_with_int_range(range) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_range_rect(range, export_area)  [static] {#create_with_int_range_rect_range_export_area_2}


```
 create_with_int_range_rect(range, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| range | [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Bu [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges(ranges)  [static] {#create_with_int_ranges_ranges_3}


```
 create_with_int_ranges(ranges) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Bu [IntRange](/imaging/python-net/aspose.imaging/intrange/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_int_ranges_rect(ranges, export_area)  [static] {#create_with_int_ranges_rect_ranges_export_area_4}


```
 create_with_int_ranges_rect(ranges, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Bu [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number(page)  [static] {#create_with_page_number_page_5}


```
 create_with_page_number(page) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sayfa | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_number_rect(page, export_area)  [static] {#create_with_page_number_rect_page_export_area_6}


```
 create_with_page_number_rect(page, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sayfa | int | Sayfa indeksi. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers(pages)  [static] {#create_with_page_numbers_pages_7}


```
 create_with_page_numbers(pages) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sayfalar | int[] | Sayfalar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_numbers_rect(pages, export_area)  [static] {#create_with_page_numbers_rect_pages_export_area_8}


```
 create_with_page_numbers_rect(pages, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sayfalar | int[] | Sayfalar dizisi. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles(page_titles)  [static] {#create_with_page_titles_page_titles_9}


```
 create_with_page_titles(page_titles) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| page_titles | string[] | Sayfa başlıkları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: create_with_page_titles_rect(page_titles, export_area)  [static] {#create_with_page_titles_rect_page_titles_export_area_10}


```
 create_with_page_titles_rect(page_titles, export_area) 
```

Yeni bir [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| page_titles | string[] | Sayfa başlıkları. |
| export_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dışa aktarma alanı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) |  |


### Method: init_pages(ranges) {#init_pages_ranges_11}


```
 init_pages(ranges) 
```

Sayfaları aralıklar dizisinden başlatır

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| ranges | [IntRange[]](/imaging/python-net/aspose.imaging/intrange/) | Aralıklar. |

