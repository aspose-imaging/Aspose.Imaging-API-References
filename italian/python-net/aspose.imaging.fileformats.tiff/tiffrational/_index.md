---
title: "Classe TiffRational"
type: docs
weight: 230
url: /it/python-net/aspose.imaging.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffRational

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Inizializza una nuova istanza della classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Inizializza una nuova istanza della classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Inizializza una nuova istanza della classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| EPSILON [statico] | float | r | L'epsilon per il calcolo delle frazioni |
| denominatore | int | r | Ottiene il denominatore. |
| numeratore | int | r | Ottiene il numeratore. |
| valore | float | r | Ottiene il valore float. |
| value_d | float | r | Ottiene il valore double. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | Approssima il valore fornito a una frazione. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | Approssima il valore fornito a una frazione. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | Approssima il valore fornito a una frazione. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value)](#approximate_fraction_value_5) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value)](#approximate_fraction_value_6) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | Approssima il valore fornito a una frazione. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Inizializza una nuova istanza della classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Inizializza una nuova istanza della classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| numeratore | int | Il numeratore. |
| denominatore | int | Il denominatore. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Inizializza una nuova istanza della classe [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | int | Il valore del numeratore. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | float | Il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un numero razionale con errore inferiore a [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | float | Il valore. |
| epsilon | float | L'errore consentito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un numero razionale con errore inferiore a _epsilon_. |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | float | Il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un numero razionale con errore inferiore a [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | float | Il valore. |
| epsilon | float | L'errore consentito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un numero razionale con errore inferiore a _epsilon_. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | float | Il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un numero razionale con errore inferiore a [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | float | Il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un numero razionale con errore inferiore a [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | float | Il valore. |
| epsilon | float | L'errore consentito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un numero razionale con errore inferiore a _epsilon_. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | float | Il valore. |
| epsilon | float | L'errore consentito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un numero razionale con errore inferiore a _epsilon_. |


