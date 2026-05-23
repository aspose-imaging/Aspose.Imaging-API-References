---
title: "RectangleF Sınıfı"
type: docs
weight: 7130
url: /tr/python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | RectangleF sınıfının yeni bir örneğini başlatır |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Belirtilen konum ve boyutla [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının yeni bir örneğini başlatır. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Belirtilen konum ve boyutla [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bottom | float | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) ve [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) toplamı olan y koordinatını alır veya ayarlar. |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Değerleri sıfır olarak ayarlanmış [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) ve [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) içeren [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının yeni bir örneğini alır. |
| height | float | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının yüksekliğini alır veya ayarlar. |
| is_empty | bool | r | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) veya [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) özelliğinin değeri sıfır olup olmadığını gösteren bir değeri alır. |
| left | float | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının sol kenarının x koordinatını alır veya ayarlar. |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| right | float | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) ve [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) toplamı olan x koordinatını alır veya ayarlar. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının boyutunu alır veya ayarlar. |
| top | float | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının üst kenarının y koordinatını alır veya ayarlar. |
| width | float | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının genişliğini alır veya ayarlar. |
| x | float | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| y | float | r/w | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [contains(point)](#contains_point_1) | Belirtilen noktanın bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler. |
| [contains(rect)](#contains_rect_2) | _rect_ tarafından temsil edilen dikdörtgen bölgenin tamamen bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler. |
| [contains(x, y)](#contains_x_y_3) | Belirtilen noktanın bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler. |
| [contains_point_f(point)](#contains_point_f_point_4) | Belirtilen noktanın bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler. |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | _rect_ tarafından temsil edilen dikdörtgen bölgenin tamamen bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | Belirtilen konumlardaki sol üst ve sağ alt köşelerle bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı oluşturur. |
| [from_points(point1, point2)](#from_points_point1_point2_7) | Belirtilen iki noktadan yeni bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) oluşturur. Oluşturulan [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) nin iki köşesi verilen _point1_ ve _point2_ değerlerine eşit olacaktır. Bunlar genellikle karşıt köşelerdir. |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değişmeden kalır. |
| [inflate(size)](#inflate_size_9) | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yi belirtilen miktarda şişirir. |
| [inflate(x, y)](#inflate_x_y_10) | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısını belirtilen miktarda şişirir. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değişmeden kalır. |
| [intersect(a, b)](#intersect_a_b_12) | İki dikdörtgenin kesişimini temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı döndürür. Eğer kesişim yoksa, boş bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) döndürülür. |
| [intersect(rect)](#intersect_rect_13) | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısını, kendisi ile belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının kesişimiyle değiştirir. |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | İki dikdörtgenin kesişimini temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı döndürür. Eğer kesişim yoksa, boş bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) döndürülür. |
| [intersects_with(rect)](#intersects_with_rect_15) | Bu dikdörtgenin _rect_ ile kesişip kesişmediğini belirler. |
| normalize() | Dikdörtgeni, genişliğini ve yüksekliğini pozitif yaparak, solun sağdan, üstün aşağıdan küçük olmasını sağlayarak normalleştirir. |
| [offset(pos)](#offset_pos_16) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [offset(x, y)](#offset_x_y_17) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [union(a, b)](#union_a_b_18) | Birleşim oluşturan iki dikdörtgeni de içinde tutabilecek en küçük üçüncü dikdörtgeni oluşturur. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

RectangleF sınıfının yeni bir örneğini başlatır

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Belirtilen konum ve boyutla [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Dikdörtgen bölgenin sol üst köşesini temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Dikdörtgen bölgenin genişliğini ve yüksekliğini temsil eden bir [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Belirtilen konum ve boyutla [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Dikdörtgenin genişliği. |
| height | float | Dikdörtgenin yüksekliği. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Belirtilen noktanın bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek [PointF](/imaging/python-net/aspose.imaging/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, _point_ parametresiyle temsil edilen nokta bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunuyorsa true, aksi takdirde false döndürür. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

_rect_ tarafından temsil edilen dikdörtgen bölgenin tamamen bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Test edilecek [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, _rect_ tarafından temsil edilen dikdörtgen bölgenin, bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) tarafından temsil edilen dikdörtgen bölge içinde tamamen bulunması durumunda true döndürür; aksi takdirde false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Belirtilen noktanın bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, _x_ ve _y_ ile tanımlanan noktanın bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunması durumunda true döndürür; aksi takdirde false. |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

Belirtilen noktanın bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Test edilecek [PointF](/imaging/python-net/aspose.imaging/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, _point_ parametresiyle temsil edilen nokta bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunuyorsa true, aksi takdirde false döndürür. |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

_rect_ tarafından temsil edilen dikdörtgen bölgenin tamamen bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı içinde bulunup bulunmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Test edilecek [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, _rect_ tarafından temsil edilen dikdörtgen bölgenin, bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) tarafından temsil edilen dikdörtgen bölge içinde tamamen bulunması durumunda true döndürür; aksi takdirde false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Belirtilen konumlardaki sol üst ve sağ alt köşelerle bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sol | float | Dikdörtgen bölgenin sol üst köşesinin x koordinatı. |
| üst | float | Dikdörtgen bölgenin sol üst köşesinin y koordinatı. |
| sağ | float | Dikdörtgen bölgenin sağ alt köşesinin x koordinatı. |
| alt | float | Dikdörtgen bölgenin sağ alt köşesinin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Bu yöntemin oluşturduğu yeni [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

Belirtilen iki noktadan yeni bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) oluşturur. Oluşturulan [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) nin iki köşesi verilen _point1_ ve _point2_ değerlerine eşit olacaktır. Bunlar genellikle karşıt köşelerdir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Yeni dikdörtgen için ilk [Point](/imaging/python-net/aspose.imaging/point/). |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Yeni dikdörtgen için ikinci [Point](/imaging/python-net/aspose.imaging/point/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Yeni oluşturulmuş bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değişmeden kalır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kopyalanacak [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). Bu dikdörtgen değiştirilmez. |
| x | float | Dikdörtgenin kopyasını yatay olarak şişirme miktarı. |
| y | float | Dikdörtgenin kopyasını dikey olarak şişirme miktarı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Şişirilmiş [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yi belirtilen miktarda şişirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Bu dikdörtgeni şişirme miktarı. |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısını belirtilen miktarda şişirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısını yatay olarak şişirme miktarı. |
| y | float | Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısını dikey olarak şişirme miktarı. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

Belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değişmeden kalır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kopyalanacak [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). Bu dikdörtgen değiştirilmez. |
| x | float | Dikdörtgenin kopyasını yatay olarak şişirme miktarı. |
| y | float | Dikdörtgenin kopyasını dikey olarak şişirme miktarı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Şişirilmiş [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

İki dikdörtgenin kesişimini temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı döndürür. Eğer kesişim yoksa, boş bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) döndürülür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kesişmek için birinci dikdörtgen. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kesişmek için ikinci dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | İki belirtilen dikdörtgenin üst üste gelen alanını temsil eden boyuta sahip üçüncü bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

Bu [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısını, kendisi ile belirtilen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısının kesişimiyle değiştirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kesişmesi gereken dikdörtgen. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

İki dikdörtgenin kesişimini temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı döndürür. Eğer kesişim yoksa, boş bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) döndürülür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kesişmek için birinci dikdörtgen. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kesişmek için ikinci dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | İki belirtilen dikdörtgenin üst üste gelen alanını temsil eden boyuta sahip üçüncü bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

Bu dikdörtgenin _rect_ ile kesişip kesişmediğini belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Test edilecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, herhangi bir kesişme varsa true döndürür. |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Konumu ofsetlemek için miktar. |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Konumu yatay olarak ofsetlemek için miktar. |
| y | float | Konumu dikey olarak ofsetlemek için miktar. |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

Birleşim oluşturan iki dikdörtgeni de içinde tutabilecek en küçük üçüncü dikdörtgeni oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Birleştirilecek ilk dikdörtgen. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Birleştirilecek ikinci dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Birleşimi oluşturan iki dikdörtgeni içeren üçüncü bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |


