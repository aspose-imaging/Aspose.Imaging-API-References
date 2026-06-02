---
title: "TiffRational-klass"
type: docs
weight: 230
url: /sv/python-net/aspose.imaging.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffRational

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Initierar en ny instans av klassen [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Initierar en ny instans av klassen [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Initierar en ny instans av klassen [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [statisk] | float | r | Epsilon för bråkräkning |
| nämnare | int | r | Hämtar nämnaren. |
| täljare | int | r | Hämtar täljaren. |
| värde | float | r | Hämtar flyttalsvärdet. |
| value_d | float | r | Hämtar dubbelvärdet. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | Approximerar det angivna värdet till ett bråk. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | Approximerar det angivna värdet till ett bråk. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | Approximerar det angivna värdet till ett bråk. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | Approximerar det angivna värdet till ett bråk. |
| [approximate_fraction(value)](#approximate_fraction_value_5) | Approximerar det angivna värdet till ett bråk. |
| [approximate_fraction(value)](#approximate_fraction_value_6) | Approximerar det angivna värdet till ett bråk. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | Approximerar det angivna värdet till ett bråk. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | Approximerar det angivna värdet till ett bråk. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Initierar en ny instans av klassen [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Initierar en ny instans av klassen [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| täljare | int | Täljaren. |
| nämnare | int | Nämnaren. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Initierar en ny instans av klassen [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | int | Täljarvärdet. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

Approximerar det angivna värdet till ett bråk.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Ett rationellt tal med fel mindre än [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

Approximerar det angivna värdet till ett bråk.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |
| epsilon | float | Det tillåtna felet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Ett rationellt tal med fel mindre än _epsilon_. |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

Approximerar det angivna värdet till ett bråk.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Ett rationellt tal med fel mindre än [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

Approximerar det angivna värdet till ett bråk.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |
| epsilon | float | Det tillåtna felet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Ett rationellt tal med fel mindre än _epsilon_. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

Approximerar det angivna värdet till ett bråk.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Ett rationellt tal med fel mindre än [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

Approximerar det angivna värdet till ett bråk.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Ett rationellt tal med fel mindre än [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

Approximerar det angivna värdet till ett bråk.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |
| epsilon | float | Det tillåtna felet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Ett rationellt tal med fel mindre än _epsilon_. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

Approximerar det angivna värdet till ett bråk.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |
| epsilon | float | Det tillåtna felet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Ett rationellt tal med fel mindre än _epsilon_. |


