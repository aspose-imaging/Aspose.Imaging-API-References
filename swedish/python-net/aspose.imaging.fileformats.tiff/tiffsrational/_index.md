---
title: "TiffSRational-klass"
type: docs
weight: 280
url: /sv/python-net/aspose.imaging.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffSRational

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initierar en ny instans av klassen [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initierar en ny instans av klassen [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Initierar en ny instans av klassen [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |
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


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Initierar en ny instans av klassen [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Initierar en ny instans av klassen [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| täljare | int | Täljaren. |
| nämnare | int | Nämnaren. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Initierar en ny instans av klassen [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | int | Värdet. |

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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Ett rationellt tal med fel mindre än [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Ett rationellt tal med fel mindre än _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Ett rationellt tal med fel mindre än [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Ett rationellt tal med fel mindre än _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Ett rationellt tal med fel mindre än [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Ett rationellt tal med fel mindre än [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Ett rationellt tal med fel mindre än _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Ett rationellt tal med fel mindre än _epsilon_. |


