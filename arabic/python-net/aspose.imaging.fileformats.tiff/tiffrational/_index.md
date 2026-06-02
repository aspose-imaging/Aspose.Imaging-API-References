---
title: "فئة TiffRational"
type: docs
weight: 230
url: /ar/python-net/aspose.imaging.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffRational

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | ينشئ مثيلاً جديدًا للفئة [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | ينشئ مثيلاً جديدًا للفئة [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) |
| [TiffRational(value)](#TiffRational_value_3) | ينشئ مثيلاً جديدًا للفئة [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| EPSILON [ثابت] | float | r | الإبسيلون لحساب الكسر |
| المقام | int | r | يحصل على المقام. |
| البسط | int | r | يحصل على البسط. |
| القيمة | float | r | يحصل على القيمة العائمة. |
| value_d | float | r | يحصل على القيمة المزدوجة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value)](#approximate_fraction_value_5) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value)](#approximate_fraction_value_6) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | يقرب القيمة المقدمة إلى كسر. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

ينشئ مثيلاً جديدًا للفئة [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/)

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

ينشئ مثيلاً جديدًا للفئة [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البسط | int | البسط. |
| المقام | int | المقام. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

ينشئ مثيلاً جديدًا للفئة [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | int | قيمة البسط. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | float | القيمة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | عدد نسبي له خطأ أقل من [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | float | القيمة. |
| epsilon | float | الخطأ المسموح به. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | عدد نسبي له خطأ أقل من _epsilon_. |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | float | القيمة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | عدد نسبي له خطأ أقل من [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | float | القيمة. |
| epsilon | float | الخطأ المسموح به. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | عدد نسبي له خطأ أقل من _epsilon_. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | float | القيمة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | عدد نسبي له خطأ أقل من [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | float | القيمة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | عدد نسبي له خطأ أقل من [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | float | القيمة. |
| epsilon | float | الخطأ المسموح به. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | عدد نسبي له خطأ أقل من _epsilon_. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | float | القيمة. |
| epsilon | float | الخطأ المسموح به. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | عدد نسبي له خطأ أقل من _epsilon_. |


