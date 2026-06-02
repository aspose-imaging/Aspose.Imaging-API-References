---
title: "Classe TiffRational"
type: docs
weight: 230
url: /fr/python-net/aspose.imaging.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffRational

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Initialise une nouvelle instance de la classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Initialise une nouvelle instance de la classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Initialise une nouvelle instance de la classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [statique] | float | r | L'epsilon pour le calcul des fractions. |
| dénominateur | int | r | Obtient le dénominateur. |
| numérateur | int | r | Obtient le numérateur. |
| value | float | r | Obtient la valeur flottante. |
| value_d | float | r | Obtient la valeur double. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | Approxime la valeur fournie en une fraction. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | Approxime la valeur fournie en une fraction. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | Approxime la valeur fournie en une fraction. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value)](#approximate_fraction_value_5) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value)](#approximate_fraction_value_6) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | Approxime la valeur fournie en une fraction. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Initialise une nouvelle instance de la classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Initialise une nouvelle instance de la classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| numérateur | int | Le numérateur. |
| dénominateur | int | Le dénominateur. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Initialise une nouvelle instance de la classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | int | La valeur du numérateur. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | float | La valeur. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un nombre rationnel dont l'erreur est inférieure à [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | float | La valeur. |
| epsilon | float | L'erreur autorisée. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un nombre rationnel dont l'erreur est inférieure à _epsilon_. |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | float | La valeur. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un nombre rationnel dont l'erreur est inférieure à [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | float | La valeur. |
| epsilon | float | L'erreur autorisée. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un nombre rationnel dont l'erreur est inférieure à _epsilon_. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | float | La valeur. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un nombre rationnel dont l'erreur est inférieure à [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | float | La valeur. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un nombre rationnel dont l'erreur est inférieure à [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | float | La valeur. |
| epsilon | float | L'erreur autorisée. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un nombre rationnel dont l'erreur est inférieure à _epsilon_. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | float | La valeur. |
| epsilon | float | L'erreur autorisée. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un nombre rationnel dont l'erreur est inférieure à _epsilon_. |


