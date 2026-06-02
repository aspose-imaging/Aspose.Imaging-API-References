---
title: "Point Sınıfı"
type: docs
weight: 6960
url: /tr/python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Point()](#Point__1) | Point sınıfının yeni bir örneğini başlatır |
| [Point(dw)](#Point_dw_2) | Koordinatları tam sayı değeriyle belirtilen yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır. |
| [Point(size)](#Point_size_3) | [Size](/imaging/python-net/aspose.imaging/size/) yapısından yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır. |
| [Point(x, y)](#Point_x_y_4) | Belirtilen koordinatlarla yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | [Point.x](/imaging/python-net/aspose.imaging/point/) ve [Point.y](/imaging/python-net/aspose.imaging/point/) değerleri sıfıra ayarlanmış yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini alır. |
| is_empty | bool | r | Bu [Point](/imaging/python-net/aspose.imaging/point/) boş mu olduğunu gösteren bir değeri alır. |
| x | int | r/w | Bu [Point](/imaging/python-net/aspose.imaging/point/) nesnesinin x koordinatını alır veya ayarlar. |
| y | int | r/w | Bu [Point](/imaging/python-net/aspose.imaging/point/) nesnesinin y koordinatını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Belirtilen [Size](/imaging/python-net/aspose.imaging/size/) değerini belirtilen [Point](/imaging/python-net/aspose.imaging/point/) üzerine ekler. |
| [ceiling(point)](#ceiling_point_2) | Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) değerlerini bir sonraki daha yüksek tam sayı değerlerine yuvarlayarak bir [Point](/imaging/python-net/aspose.imaging/point/) nesnesine dönüştürür. |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | Koordinatları tam sayı değeriyle belirtilen yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır. |
| [create_from_size(size)](#create_from_size_size_4) | [Size](/imaging/python-net/aspose.imaging/size/) yapısından yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır. |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | Bir uzun nesneye paketlenmiş Point nesnesini ayrı X ve Y tam sayı değerlerine ayırır. |
| [offset(dx, dy)](#offset_dx_dy_6) | Bu [Point](/imaging/python-net/aspose.imaging/point/) nesnesini belirtilen miktarda kaydırır. |
| [offset(point)](#offset_point_7) | Bu [Point](/imaging/python-net/aspose.imaging/point/) nesnesini belirtilen [Point](/imaging/python-net/aspose.imaging/point/) ile kaydırır. |
| [round(point)](#round_point_8) | Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) değerlerini en yakın tam sayıya yuvarlayarak bir [Point](/imaging/python-net/aspose.imaging/point/) nesnesine dönüştürür. |
| [subtract(point, size)](#subtract_point_size_9) | Belirtilen [Size](/imaging/python-net/aspose.imaging/size/) değerini belirtilen [Point](/imaging/python-net/aspose.imaging/point/) değerinden çıkararak sonucu döndürür. |
| [to_long()](#to_long__10) | Bu Point nesnesini X ve Y koordinatlarını yüksek ve düşük bitlerde içeren tek bir uzun değere dönüştür. |
| [truncate(point)](#truncate_point_11) | Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) değerlerini [Point](/imaging/python-net/aspose.imaging/point/) değerlerini kırparak bir [Point](/imaging/python-net/aspose.imaging/point/) nesnesine dönüştürür. |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Point sınıfının yeni bir örneğini başlatır

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Koordinatları tam sayı değeriyle belirtilen yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dw | int | Yeni nokta için koordinatları belirten 32 bitlik bir tam sayı. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

[Size](/imaging/python-net/aspose.imaging/size/) yapısından yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Yeni nokta koordinatlarını içerir. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Belirtilen koordinatlarla yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Noktanın yatay konumu. |
| y | int | Noktanın dikey konumu. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Belirtilen [Size](/imaging/python-net/aspose.imaging/size/) değerini belirtilen [Point](/imaging/python-net/aspose.imaging/point/) üzerine ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Eklenecek [Point](/imaging/python-net/aspose.imaging/point/). |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Nokta _point_ üzerine eklenecek [Size](/imaging/python-net/aspose.imaging/size/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Toplama işleminin sonucu olan [Point](/imaging/python-net/aspose.imaging/point/). |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) değerlerini bir sonraki daha yüksek tam sayı değerlerine yuvarlayarak bir [Point](/imaging/python-net/aspose.imaging/point/) nesnesine dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Dönüştürülecek [PointF](/imaging/python-net/aspose.imaging/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Bu yöntemin dönüştürdüğü [Point](/imaging/python-net/aspose.imaging/point/). |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


```
 create_from_d_word(dw) 
```

Koordinatları tam sayı değeriyle belirtilen yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dw | int | Yeni nokta için koordinatları belirten 32 bitlik bir tam sayı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

[Size](/imaging/python-net/aspose.imaging/size/) yapısından yeni bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Yeni nokta koordinatlarını içerir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

Bir uzun nesneye paketlenmiş Point nesnesini ayrı X ve Y tam sayı değerlerine ayırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| packed_point | int | Bir uzun değer içinde paketlenmiş Point nesnesi. |
| x | int[] | Paketlenmiş Point X değerinden çıkarılan. |
| y | int[] | Paketlenmiş Point Y değerinden çıkarılan. |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

Bu [Point](/imaging/python-net/aspose.imaging/point/) nesnesini belirtilen miktarda kaydırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | int | x-koordinatını kaydırmak için miktar. |
| dy | int | y-koordinatını kaydırmak için miktar. |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

Bu [Point](/imaging/python-net/aspose.imaging/point/) nesnesini belirtilen [Point](/imaging/python-net/aspose.imaging/point/) ile kaydırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Bu [Point](/imaging/python-net/aspose.imaging/point/) kaydırmak için kullanılan [Point](/imaging/python-net/aspose.imaging/point/). |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) değerlerini en yakın tam sayıya yuvarlayarak bir [Point](/imaging/python-net/aspose.imaging/point/) nesnesine dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Dönüştürülecek [PointF](/imaging/python-net/aspose.imaging/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Bu yöntemin dönüştürdüğü [Point](/imaging/python-net/aspose.imaging/point/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

Belirtilen [Size](/imaging/python-net/aspose.imaging/size/) değerini belirtilen [Point](/imaging/python-net/aspose.imaging/point/) değerinden çıkararak sonucu döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Çıkarma yapılacak [Point](/imaging/python-net/aspose.imaging/point/). |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | [Size](/imaging/python-net/aspose.imaging/size/) _point_'dan çıkarılacak. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Çıkarma işleminin sonucu olan [Point](/imaging/python-net/aspose.imaging/point/). |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

Bu Point nesnesini X ve Y koordinatlarını yüksek ve düşük bitlerde içeren tek bir uzun değere dönüştür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Bir uzun değer içinde paketlenmiş Point nesnesi. |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) değerlerini [Point](/imaging/python-net/aspose.imaging/point/) değerlerini kırparak bir [Point](/imaging/python-net/aspose.imaging/point/) nesnesine dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Dönüştürülecek [PointF](/imaging/python-net/aspose.imaging/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Bu yöntemin dönüştürdüğü [Point](/imaging/python-net/aspose.imaging/point/). |


