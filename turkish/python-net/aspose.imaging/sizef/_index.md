---
title: "SizeF Sınıfı"
type: docs
weight: 7290
url: /tr/python-net/aspose.imaging/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SizeF

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [SizeF()](#SizeF__1) | SizeF sınıfının yeni bir örneğini başlatır |
| [SizeF(point)](#SizeF_point_2) | Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) üzerinden yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı örneği başlatır. |
| [SizeF(size)](#SizeF_size_3) | Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısından yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) örneği başlatır. |
| [SizeF(width, height)](#SizeF_width_height_4) | Belirtilen boyutlardan yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Sıfır olarak ayarlanmış [SizeF.width](/imaging/python-net/aspose.imaging/sizef/) ve [SizeF.height](/imaging/python-net/aspose.imaging/sizef/) değerlerine sahip yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı örneği alır. |
| height | float | r/w | Bu [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesinin dikey bileşenini alır veya ayarlar. |
| is_empty | bool | r | Bu [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesinin sıfır genişlik ve yüksekliğe sahip olup olmadığını gösteren bir değer alır. |
| width | float | r/w | Bu [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesinin yatay bileşenini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının genişlik ve yüksekliğini başka bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının genişlik ve yüksekliğine ekler. |
| [create_from_point_f(point)](#create_from_point_f_point_2) | Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) üzerinden yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı örneği başlatır. |
| [create_from_size_f(size)](#create_from_size_f_size_3) | Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısından yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) örneği başlatır. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının genişlik ve yüksekliğini başka bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının genişlik ve yüksekliğinden çıkarır. |
| [to_point_f()](#to_point_f__5) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesini bir [PointF](/imaging/python-net/aspose.imaging/pointf/) öğesine dönüştürür. |
| [to_size()](#to_size__6) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesini kesirli olmayan boyut değerlerine sahip bir [Size](/imaging/python-net/aspose.imaging/size/) yapısına dönüştürür. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

SizeF sınıfının yeni bir örneğini başlatır

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) üzerinden yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Bu [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesini başlatmak için kullanılacak [PointF](/imaging/python-net/aspose.imaging/pointf/) . |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısından yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Yeni [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesini oluşturmak için kullanılacak [SizeF](/imaging/python-net/aspose.imaging/sizef/) . |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Belirtilen boyutlardan yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | float | Yeni [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesinin genişlik bileşeni. |
| height | float | Yeni [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesinin yükseklik bileşeni. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının genişlik ve yüksekliğini başka bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının genişlik ve yüksekliğine ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Eklenecek ilk [SizeF](/imaging/python-net/aspose.imaging/sizef/) . |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Eklenecek ikinci [SizeF](/imaging/python-net/aspose.imaging/sizef/) . |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Toplama işleminin sonucu olan bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı. |


### Method: create_from_point_f(point)  [static] {#create_from_point_f_point_2}


```
 create_from_point_f(point) 
```

Belirtilen [PointF](/imaging/python-net/aspose.imaging/pointf/) üzerinden yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Bu [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesini başlatmak için kullanılacak [PointF](/imaging/python-net/aspose.imaging/pointf/) . |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: create_from_size_f(size)  [static] {#create_from_size_f_size_3}


```
 create_from_size_f(size) 
```

Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısından yeni bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Yeni [SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesini oluşturmak için kullanılacak [SizeF](/imaging/python-net/aspose.imaging/sizef/) . |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının genişlik ve yüksekliğini başka bir [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Çıkarma operatörünün sol tarafındaki [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Çıkarma operatörünün sağ tarafındaki [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Çıkarma işleminin sonucu olan [SizeF](/imaging/python-net/aspose.imaging/sizef/) . |


### Method: to_point_f() {#to_point_f__5}


```
 to_point_f() 
```

[SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesini bir [PointF](/imaging/python-net/aspose.imaging/pointf/) öğesine dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı döndürür. |


### Method: to_size() {#to_size__6}


```
 to_size() 
```

[SizeF](/imaging/python-net/aspose.imaging/sizef/) öğesini kesirli olmayan boyut değerlerine sahip bir [Size](/imaging/python-net/aspose.imaging/size/) yapısına dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Bir [Size](/imaging/python-net/aspose.imaging/size/) yapısı döndürür. |


