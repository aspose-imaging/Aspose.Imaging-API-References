---
title: "Classe TiffSRational"
type: docs
weight: 280
url: /fr/python-net/aspose.imaging.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffSRational

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initialise une nouvelle instance de la classe [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initialise une nouvelle instance de la classe [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Initialise une nouvelle instance de la classe [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |
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


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Initialise une nouvelle instance de la classe [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Initialise une nouvelle instance de la classe [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| numérateur | int | Le numérateur. |
| dénominateur | int | Le dénominateur. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Initialise une nouvelle instance de la classe [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | int | La valeur. |

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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Un nombre rationnel dont l’erreur est inférieure à [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Un nombre rationnel dont l'erreur est inférieure à _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Un nombre rationnel dont l’erreur est inférieure à [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Un nombre rationnel dont l'erreur est inférieure à _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Un nombre rationnel dont l’erreur est inférieure à [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Un nombre rationnel dont l’erreur est inférieure à [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Un nombre rationnel dont l'erreur est inférieure à _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Un nombre rationnel dont l'erreur est inférieure à _epsilon_. |


