---
title: "Clase TiffRational"
type: docs
weight: 230
url: /es/python-net/aspose.imaging.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffRational

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Inicializa una nueva instancia de la clase [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Inicializa una nueva instancia de la clase [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Inicializa una nueva instancia de la clase [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| EPSILON [static] | float | r | El epsilon para el cálculo de fracciones |
| denominador | int | r | Obtiene el denominador. |
| numerador | int | r | Obtiene el numerador. |
| valor | float | r | Obtiene el valor flotante. |
| value_d | float | r | Obtiene el valor doble. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | Aproxima el valor proporcionado a una fracción. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | Aproxima el valor proporcionado a una fracción. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | Aproxima el valor proporcionado a una fracción. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value)](#approximate_fraction_value_5) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value)](#approximate_fraction_value_6) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | Aproxima el valor proporcionado a una fracción. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Inicializa una nueva instancia de la clase [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Inicializa una nueva instancia de la clase [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| numerador | int | El numerador. |
| denominador | int | El denominador. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Inicializa una nueva instancia de la clase [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | int | El valor del numerador. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | float | El valor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un número racional con un error menor que [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | float | El valor. |
| epsilon | float | El error permitido. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un número racional con un error menor que _epsilon_. |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | float | El valor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un número racional con un error menor que [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | float | El valor. |
| epsilon | float | El error permitido. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un número racional con un error menor que _epsilon_. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | float | El valor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un número racional con un error menor que [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | float | El valor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un número racional con un error menor que [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | float | El valor. |
| epsilon | float | El error permitido. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un número racional con un error menor que _epsilon_. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | float | El valor. |
| epsilon | float | El error permitido. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Un número racional con un error menor que _epsilon_. |


