---
title: "Rectangle Sınıfı"
type: docs
weight: 7120
url: /tr/python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Rectangle sınıfının yeni bir örneğini başlatır |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Belirtilen konum ve boyutla [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının yeni bir örneğini başlatır. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Belirtilen konum ve boyutla [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bottom | int | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) ve [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar. |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) ve [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) değerleri sıfıra ayarlanmış [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının yeni bir örneğini alır. |
| height | int | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının yüksekliğini alır veya ayarlar. |
| is_empty | bool | r | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) nesnesinin tüm sayısal özelliklerinin sıfır değerine sahip olup olmadığını gösteren bir değer alır. |
| left | int | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının sol kenarının x-koordinatını alır veya ayarlar. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| right | int | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) ve [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) özellik değerlerinin toplamı olan x-koordinatını alır veya ayarlar. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının boyutunu alır veya ayarlar. |
| top | int | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının üst kenarının y-koordinatını alır veya ayarlar. |
| width | int | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının genişliğini alır veya ayarlar. |
| x | int | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının sol üst köşesinin x-koordinatını alır veya ayarlar. |
| y | int | r/w | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının sol üst köşesinin y-koordinatını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısını, [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) değerlerini bir sonraki üst tam sayıya yuvarlayarak bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısına dönüştürür. |
| [contains(point)](#contains_point_2) | Belirtilen noktanın bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler. |
| [contains(rect)](#contains_rect_3) | _rect_ tarafından temsil edilen dikdörtgen bölgenin tamamen bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler. |
| [contains(x, y)](#contains_x_y_4) | Belirtilen noktanın bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler. |
| [contains_point(point)](#contains_point_point_5) | Belirtilen noktanın bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler. |
| [contains_rect(rect)](#contains_rect_rect_6) | _rect_ tarafından temsil edilen dikdörtgen bölgenin tamamen bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | Belirtilen kenar konumlarıyla bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı oluşturur. |
| [from_points(point1, point2)](#from_points_point1_point2_8) | Belirtilen iki noktadan yeni bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) oluşturur. Oluşturulan [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) iki köşesi, verilen _point1_ ve _point2_ değerlerine eşit olacaktır. Bunlar genellikle karşıt köşeler olur. |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | Belirtilen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya, belirtilen miktarda şişirilir. Orijinal [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı değiştirilmez. |
| [inflate(size)](#inflate_size_10) | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını belirtilen miktarda şişirir. |
| [inflate(width, height)](#inflate_width_height_11) | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını belirtilen miktarda şişirir. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | Belirtilen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya, belirtilen miktarda şişirilir. Orijinal [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı değiştirilmez. |
| [intersect(a, b)](#intersect_a_b_13) | İki diğer [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının kesişimini temsil eden üçüncü bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını döndürür. Kesişme yoksa, boş bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) döndürülür. |
| [intersect(rect)](#intersect_rect_14) | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını, kendisi ile belirtilen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının kesişimiyle değiştirir. |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | İki diğer [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının kesişimini temsil eden üçüncü bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını döndürür. Kesişme yoksa, boş bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) döndürülür. |
| [intersects_with(rect)](#intersects_with_rect_16) | Bu dikdörtgenin _rect_ ile kesişip kesişmediğini belirler. |
| normalize() | Dikdörtgeni, genişliğini ve yüksekliğini pozitif yaparak, solun sağdan, üstün aşağıdan küçük olmasını sağlayarak normalleştirir. |
| [offset(pos)](#offset_pos_17) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [offset(x, y)](#offset_x_y_18) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [round(value)](#round_value_19) | Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) değerlerini en yakın tam sayıya yuvarlayarak bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısına dönüştürür. |
| [truncate(value)](#truncate_value_20) | Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) değerlerini kırparak bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısına dönüştürür. |
| [union(a, b)](#union_a_b_21) | İki [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının birleşimini içeren bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını alır. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Rectangle sınıfının yeni bir örneğini başlatır

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Belirtilen konum ve boyutla [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Dikdörtgen bölgenin sol üst köşesini temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/). |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Dikdörtgen bölgenin genişliğini ve yüksekliğini temsil eden bir [Size](/imaging/python-net/aspose.imaging/size/). |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Belirtilen konum ve boyutla [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Dikdörtgenin genişliği. |
| height | int | Dikdörtgenin yüksekliği. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısını, [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) değerlerini bir sonraki üst tam sayıya yuvarlayarak bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısına dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dönüştürülecek [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) döndürür. |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Belirtilen noktanın bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek [Point](/imaging/python-net/aspose.imaging/point/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | This method returns true if the point represented by _point_ is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

_rect_ tarafından temsil edilen dikdörtgen bölgenin tamamen bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Test edilecek [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, _rect_ tarafından temsil edilen dikdörtgen bölge bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı içinde tamamen bulunuyorsa true döndürür; aksi takdirde false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Belirtilen noktanın bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, _x_ ve _y_ tarafından tanımlanan nokta bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı içinde bulunuyorsa true döndürür; aksi takdirde false. |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

Belirtilen noktanın bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Test edilecek [Point](/imaging/python-net/aspose.imaging/point/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | This method returns true if the point represented by _point_ is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

_rect_ tarafından temsil edilen dikdörtgen bölgenin tamamen bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının içinde olup olmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Test edilecek [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, _rect_ tarafından temsil edilen dikdörtgen bölge bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı içinde tamamen bulunuyorsa true döndürür; aksi takdirde false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Belirtilen kenar konumlarıyla bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| left | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının sol üst köşesinin x koordinatı. |
| top | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının sol üst köşesinin y koordinatı. |
| right | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının sağ alt köşesinin x koordinatı. |
| bottom | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının sağ alt köşesinin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Bu yöntemin oluşturduğu yeni [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

Belirtilen iki noktadan yeni bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) oluşturur. Oluşturulan [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) iki köşesi, verilen _point1_ ve _point2_ değerlerine eşit olacaktır. Bunlar genellikle karşıt köşeler olur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Yeni dikdörtgen için ilk [Point](/imaging/python-net/aspose.imaging/point/). |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Yeni dikdörtgen için ikinci [Point](/imaging/python-net/aspose.imaging/point/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Yeni oluşturulmuş bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

Belirtilen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya, belirtilen miktarda şişirilir. Orijinal [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı değiştirilmez.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Başlangıç için kullanılacak [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Bu dikdörtgen değiştirilemez. |
| x | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yatay olarak şişirilecek miktar. |
| y | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dikey olarak şişirilecek miktar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Şişirilmiş [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını belirtilen miktarda şişirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Bu dikdörtgeni şişirme miktarı. |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını belirtilen miktarda şişirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yatay olarak şişirilecek miktar. |
| height | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dikey olarak şişirilecek miktar. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

Belirtilen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya, belirtilen miktarda şişirilir. Orijinal [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı değiştirilmez.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Başlangıç için kullanılacak [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Bu dikdörtgen değiştirilemez. |
| x | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yatay olarak şişirilecek miktar. |
| y | int | Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dikey olarak şişirilecek miktar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Şişirilmiş [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

İki diğer [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının kesişimini temsil eden üçüncü bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını döndürür. Kesişme yoksa, boş bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) döndürülür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kesişmek için birinci dikdörtgen. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kesişmek için ikinci dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | _a_ ve _b_ kesişimini temsil eden bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

Bu [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını, kendisi ile belirtilen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının kesişimiyle değiştirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kesişmek için kullanılacak [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

İki diğer [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının kesişimini temsil eden üçüncü bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını döndürür. Kesişme yoksa, boş bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) döndürülür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kesişmek için birinci dikdörtgen. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kesişmek için ikinci dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | _a_ ve _b_ kesişimini temsil eden bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

Bu dikdörtgenin _rect_ ile kesişip kesişmediğini belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Test edilecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, herhangi bir kesişim varsa true, aksi takdirde false döndürür. |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | Konumu ofsetlemek için miktar. |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Yatay ofset. |
| y | int | Dikey ofset. |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) değerlerini en yakın tam sayıya yuvarlayarak bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısına dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dönüştürülecek [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Yeni bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) değerlerini kırparak bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısına dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dönüştürülecek [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Yeni bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

İki [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının birleşimini içeren bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Birleştirilecek ilk dikdörtgen. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Birleştirilecek ikinci dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | İki [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısının birleşimini sınırlayan bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı. |


