---
title: "TiffSRational Sınıfı"
type: docs
weight: 280
url: /tr/python-net/aspose.imaging.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffSRational

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Yeni bir [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) sınıf örneği başlatır. |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Yeni bir [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) sınıf örneği başlatır. |
| [TiffSRational(value)](#TiffSRational_value_3) | Yeni bir [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| EPSILON [statik] | float | r | Kesir hesaplaması için epsilon |
| payda | int | r | Paydayı alır. |
| pay | int | r | Payı alır. |
| değer | float | r | Float değerini alır. |
| value_d | float | r | Double değerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximate_fraction(value)](#approximate_fraction_value_5) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximate_fraction(value)](#approximate_fraction_value_6) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | Sağlanan değeri bir kesire yaklaştırır. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Yeni bir [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) sınıf örneği başlatır.

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Yeni bir [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) sınıf örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pay | int | Pay. |
| payda | int | Payda. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Yeni bir [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) sınıf örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | int | Değer. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Hatası [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) değerinden daha az olan bir rasyonel sayı. |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |
| epsilon | float | İzin verilen hata. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Hatası _epsilon_'den daha az olan bir rasyonel sayı. |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Hatası [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) değerinden daha az olan bir rasyonel sayı. |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |
| epsilon | float | İzin verilen hata. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Hatası _epsilon_'den daha az olan bir rasyonel sayı. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Hatası [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) değerinden daha az olan bir rasyonel sayı. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Hatası [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) değerinden daha az olan bir rasyonel sayı. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |
| epsilon | float | İzin verilen hata. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Hatası _epsilon_'den daha az olan bir rasyonel sayı. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |
| epsilon | float | İzin verilen hata. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Hatası _epsilon_'den daha az olan bir rasyonel sayı. |


