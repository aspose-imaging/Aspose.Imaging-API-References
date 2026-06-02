---
title: "Size Sınıfı"
type: docs
weight: 7280
url: /tr/python-net/aspose.imaging/size/
---

**Summary:** Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Size()](#Size__1) | Size sınıfının yeni bir örneğini başlatır |
| [Size(point)](#Size_point_2) | [Size](/imaging/python-net/aspose.imaging/size/) yapısının yeni bir örneğini, belirtilen [Point](/imaging/python-net/aspose.imaging/point/) üzerinden başlatır. |
| [Size(width, height)](#Size_width_height_3) | Belirtilen boyutlardan [Size](/imaging/python-net/aspose.imaging/size/) yapısının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size/) | r | [Size](/imaging/python-net/aspose.imaging/size/) yapısının, [Size.width](/imaging/python-net/aspose.imaging/size/) ve [Size.height](/imaging/python-net/aspose.imaging/size/) değerleri sıfıra ayarlanmış yeni bir örneğini alır. |
| height | int | r/w | Bu [Size](/imaging/python-net/aspose.imaging/size/) nesnesinin dikey bileşenini alır veya ayarlar. |
| is_empty | bool | r | Bu [Size](/imaging/python-net/aspose.imaging/size/) nesnesinin genişlik ve yüksekliğinin 0 olup olmadığını gösteren bir değeri alır. |
| width | int | r/w | Bu [Size](/imaging/python-net/aspose.imaging/size/) nesnesinin yatay bileşenini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Bir [Size](/imaging/python-net/aspose.imaging/size/) yapısının genişlik ve yüksekliğini, başka bir [Size](/imaging/python-net/aspose.imaging/size/) yapısının genişlik ve yüksekliğine ekler. |
| [ceiling(size)](#ceiling_size_2) | Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısını, [Size](/imaging/python-net/aspose.imaging/size/) yapısının değerlerini bir sonraki üst tam sayıya yuvarlayarak bir [Size](/imaging/python-net/aspose.imaging/size/) yapısına dönüştürür. |
| [round(size)](#round_size_3) | Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısını, [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının değerlerini en yakın tam sayıya yuvarlayarak bir [Size](/imaging/python-net/aspose.imaging/size/) yapısına dönüştürür. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Bir [Size](/imaging/python-net/aspose.imaging/size/) yapısının genişlik ve yüksekliğini, başka bir [Size](/imaging/python-net/aspose.imaging/size/) yapısının genişlik ve yüksekliğinden çıkarır. |
| [truncate(size)](#truncate_size_5) | Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısını, [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının değerlerini bir sonraki alt tam sayıya kırparak bir [Size](/imaging/python-net/aspose.imaging/size/) yapısına dönüştürür. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Size sınıfının yeni bir örneğini başlatır

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

[Size](/imaging/python-net/aspose.imaging/size/) yapısının yeni bir örneğini, belirtilen [Point](/imaging/python-net/aspose.imaging/point/) üzerinden başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Bu [Size](/imaging/python-net/aspose.imaging/size/) nesnesini başlatmak için kullanılacak [Point](/imaging/python-net/aspose.imaging/point/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Belirtilen boyutlardan [Size](/imaging/python-net/aspose.imaging/size/) yapısının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Yeni [Size](/imaging/python-net/aspose.imaging/size/) nesnesinin genişlik bileşeni. |
| height | int | Yeni [Size](/imaging/python-net/aspose.imaging/size/) nesnesinin yükseklik bileşeni. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Bir [Size](/imaging/python-net/aspose.imaging/size/) yapısının genişlik ve yüksekliğini, başka bir [Size](/imaging/python-net/aspose.imaging/size/) yapısının genişlik ve yüksekliğine ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Eklenecek ilk [Size](/imaging/python-net/aspose.imaging/size/). |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Eklenecek ikinci [Size](/imaging/python-net/aspose.imaging/size/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Toplama işleminin sonucu olan bir [Size](/imaging/python-net/aspose.imaging/size/) yapısı. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısını, [Size](/imaging/python-net/aspose.imaging/size/) yapısının değerlerini bir sonraki üst tam sayıya yuvarlayarak bir [Size](/imaging/python-net/aspose.imaging/size/) yapısına dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Dönüştürülecek [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Bu yöntemin dönüştürdüğü [Size](/imaging/python-net/aspose.imaging/size/) yapısı. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısını, [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının değerlerini en yakın tam sayıya yuvarlayarak bir [Size](/imaging/python-net/aspose.imaging/size/) yapısına dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Dönüştürülecek [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Bu yöntemin dönüştürdüğü [Size](/imaging/python-net/aspose.imaging/size/) yapısı. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Bir [Size](/imaging/python-net/aspose.imaging/size/) yapısının genişlik ve yüksekliğini, başka bir [Size](/imaging/python-net/aspose.imaging/size/) yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Çıkarma operatörünün sol tarafındaki [Size] yapısı. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Çıkarma operatörünün sağ tarafındaki [Size] yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Çıkarma işleminin sonucu olan [Size] yapısı. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Belirtilen [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısını, [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısının değerlerini bir sonraki alt tam sayıya kırparak bir [Size](/imaging/python-net/aspose.imaging/size/) yapısına dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Dönüştürülecek [SizeF](/imaging/python-net/aspose.imaging/sizef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Bu yöntemin dönüştürdüğü [Size](/imaging/python-net/aspose.imaging/size/) yapısı. |


