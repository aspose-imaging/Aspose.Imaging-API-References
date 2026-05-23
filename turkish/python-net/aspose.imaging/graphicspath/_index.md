---
title: "GraphicsPath Sınıfı"
type: docs
weight: 5040
url: /tr/python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Yeni bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) sınıfı örneği başlatır. |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Yeni bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) sınıfı örneği başlatır. |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Yeni bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) sınıfı örneği başlatır. |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Yeni bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Nesnenin sınırlarını alır veya ayarlar. |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | r | Yol şekillerini alır. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | r/w | Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirleyen bir [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumerasyonunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Yeni bir şekil ekler. |
| [add_figures(figures)](#add_figures_figures_2) | Yeni şekiller ekler. |
| [add_path(adding_path)](#add_path_adding_path_3) | Belirtilen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) yoluna ekler. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Belirtilen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) yoluna ekler. |
| [deep_clone()](#deep_clone__5) | Bu grafik yolunun derin bir klonunu oluşturur. |
| flatten() | Bu yoldaki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [flatten(matrix)](#flatten_matrix_6) | Belirtilen dönüşümü uygular ve ardından bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Nesnenin sınırlarını alır. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir. |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir. |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir. |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir. |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir. |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir. |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir. |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir. |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir. |
| [is_visible(point)](#is_visible_point_26) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(point)](#is_visible_point_27) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(x, y)](#is_visible_x_y_30) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(x, y)](#is_visible_x_y_31) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | Belirtilen noktanın, belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | Belirtilen noktanın, belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible_point(point)](#is_visible_point_point_34) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | Belirtilen noktanın, belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanılarak bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | Belirtilen noktanın, belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir. |
| [remove_figure(figure)](#remove_figure_figure_42) | Bir şekli kaldırır. |
| [remove_figures(figures)](#remove_figures_figures_43) | Figürleri kaldırır. |
| reset() | Grafik yolunu boşaltır ve [FillMode](/imaging/python-net/aspose.imaging/fillmode/) öğesini [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) olarak ayarlar. |
| reverse() | Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içindeki her şeklin figür, şekil ve nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_44) | Belirtilen dönüşümü şekle uygular. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümü uygular. |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümü uygular. |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümü uygular. |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümü uygular. |
| [widen(pen)](#widen_pen_49) | Yola ek bir kontur ekler. |
| [widen(pen, matrix)](#widen_pen_matrix_50) | Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesine ek bir kontur ekler. |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesini, belirtilen kalemle çizildiğinde doldurulan alanı çevreleyen eğrilerle değiştirir. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Yeni bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) sınıfı örneği başlatır.


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Yeni bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Başlatılacak figürler. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Yeni bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Başlatılacak figürler. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Dolgu modu. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Yeni bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Dolgu modu. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Yeni bir şekil ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | Eklenecek figür. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Yeni şekiller ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Eklenecek figürler. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Belirtilen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) yoluna ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Eklenecek [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Belirtilen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) yoluna ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Eklenecek [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| bağla | bool | Eklenen yoldaki ilk figürün bu yoldaki son figürün bir parçası olup olmadığını belirten bir Boolean değer. true değeri, eklenen yoldaki ilk figürün bu yoldaki son figürün bir parçası olduğunu belirtir. false değeri, eklenen yoldaki ilk figürün bu yoldaki son figürden ayrı olduğunu belirtir. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Bu grafik yolunun derin bir klonunu oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Grafik yolunun derin bir kopyası. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Belirtilen dönüşümü uygular ve ardından bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Düzleştirmeden önce bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesini dönüştürmek için bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) kullanılır. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Düzleştirmeden önce bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesini dönüştürmek için bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) kullanılır. |
| düzlük | float | Eğri ile onun düzleştirilmiş yaklaşıklığı arasındaki izin verilen maksimum hatayı belirtir. Varsayılan değer 0.25'tir. Düzlük değerini azaltmak, yaklaşıklıktaki çizgi segmenti sayısını artırır. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Sınırlar hesaplanmadan önce uygulanacak matris. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Tahmini nesne sınırları. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Sınırlar hesaplanmadan önce uygulanacak matris. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Tahmini nesne sınırları. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek konumu belirten bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek konumu belirten bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek konumu belirten bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin (under) konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek konumu belirten bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin (under) konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin (under) konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin (under) konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek konumu belirten bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek konumu belirten bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek konumu belirten bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin (under) konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek konumu belirten bir [Point](/imaging/python-net/aspose.imaging/point/). |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

Belirtilen noktanın, bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dış hattının (altında) belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde ve belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanıldığında içeride olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Test edilecek [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizildiğinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesinin (under) konturu içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek noktayı temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek noktayı temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek noktayı temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu nesnenin içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek noktayı temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu nesnenin içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

Belirtilen noktanın, belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

Belirtilen noktanın, belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek noktayı temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek noktayı temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek noktayı temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu nesnenin içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek noktayı temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

Belirtilen noktanın, belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) kullanılarak bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

Belirtilen noktanın bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

Belirtilen noktanın, belirtilen [Graphics](/imaging/python-net/aspose.imaging/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Görünürlüğü test edilecek [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) içinde bulunuyorsa bu yöntem true döndürür; aksi takdirde false. |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

Bir şekli kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | Kaldırılacak şekil. |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

Figürleri kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Kaldırılacak şekiller. |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

Belirtilen dönüşümü şekle uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Uygulanacak dönüşüm. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümü uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren bir dizi, _srcRect_ ile tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç ya da dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | _destPoints_ ile tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümü uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren bir dizi, _srcRect_ ile tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç ya da dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | _destPoints_ ile tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Yola uygulanacak geometrik dönüşümü belirten bir [Matrix](/imaging/python-net/aspose.imaging/matrix/). |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümü uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren bir dizi, _srcRect_ ile tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç ya da dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | _destPoints_ ile tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Yola uygulanacak geometrik dönüşümü belirten bir [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Bu bükme işleminin perspektif mi yoksa çift doğrusal (bilinear) modda mı çalıştığını belirten bir [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) enumarasyonu. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümü uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren bir dizi, _srcRect_ ile tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç ya da dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | _destPoints_ ile tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Yola uygulanacak geometrik dönüşümü belirten bir [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Bu bükme işleminin perspektif mi yoksa çift doğrusal (bilinear) modda mı çalıştığını belirten bir [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) enumarasyonu. |
| flatness | float | 0 ile 1 arasında bir değer, ortaya çıkan yolun ne kadar düz olduğunu belirtir. Daha fazla bilgi için [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/) yöntemlerine bakın. |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

Yola ek bir kontur ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Yolun orijinal konturu ile bu yöntemin oluşturduğu yeni kontur arasındaki genişliği belirten bir [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesine ek bir kontur ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Yolun orijinal konturu ile bu yöntemin oluşturduğu yeni kontur arasındaki genişliği belirten bir [Pen](/imaging/python-net/aspose.imaging/pen/). |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Yolun genişletilmeden önce uygulanacak dönüşümünü belirten bir [Matrix](/imaging/python-net/aspose.imaging/matrix/). |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

Bu [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) öğesini, belirtilen kalemle çizildiğinde doldurulan alanı çevreleyen eğrilerle değiştirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Yolun orijinal konturu ile bu yöntemin oluşturduğu yeni kontur arasındaki genişliği belirten bir [Pen](/imaging/python-net/aspose.imaging/pen/). |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Yolun genişletilmeden önce uygulanacak dönüşümünü belirten bir [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| düzlük | float | Eğrilerin düzlüğünü belirten bir değer. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Bir dosya akışı örneği oluştur
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# TiffOptions sınıfının bir örneğini oluşturun ve çeşitli özelliklerini ayarlayın
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# ImageOptions örneği için kaynağı ayarlayın
	tiffOptions.source = StreamSource(stream)
	# Image sınıfının bir örneğini oluşturun
	with Image.create(tiffOptions, 500, 500) as image:
		# Graphics sınıfının bir örneğini oluştur ve başlat.
		graphics = Graphics(image)
		# Graphics yüzeyini temizle.
		graphics.clear(Color.wheat);
		# GraphicsPath sınıfının bir örneğini oluşturun
		graphics_path = GraphicsPath()
		# Figure sınıfının bir örneğini oluşturun
		figure = Figure()
		# Figure nesnesine Şekiller ekleyin
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Figure nesnesini GraphicsPath'e ekleyin
		graphics_path.add_figure(figure)
		# Siyah renkli Pen nesnesiyle yolu çizin
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Tüm değişiklikleri kaydedin.
		image.save()


```

### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#BmpOptions sınıfının bir örneğini oluşturur ve çeşitli özelliklerini ayarlar            
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#FileCreateSource sınıfının bir örneğini oluşturun ve BmpOptions örneği için Kaynak olarak atayın
	#İkinci Boolean parametresi, oluşturulacak dosyanın Geçici olup olmadığını belirler
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Image bir örnek oluştur.
	with Image.create(bmpOptions, 500, 500) as image:
		# Graphics sınıfının bir örneğini oluştur ve başlat.
		graphics = Graphics(image)
		# Graphics yüzeyini temizle.
		graphics.clear(Color.wheat)
		# GraphicsPath sınıfının bir örneğini oluşturun
		graphicspath = GraphicsPath()
		#Figure sınıfının bir örneğini oluşturun
		figure1 = Figure()
		# Figure nesnesine Şekil ekleyin
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Figure sınıfının bir örneğini oluşturun
		figure2 = Figure()
		# Figure nesnesine Şekil ekleyin
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Figure nesnesini GraphicsPath'e ekleyin
		graphicspath.add_figures([figure1, figure2])
		# Siyah renkli Pen nesnesiyle yolu çizin
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# Tüm değişiklikleri kaydedin.
		image.save()


```

