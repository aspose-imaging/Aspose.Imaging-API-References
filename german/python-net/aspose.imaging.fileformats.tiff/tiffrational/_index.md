---
title: "TiffRational Klasse"
type: docs
weight: 230
url: /de/python-net/aspose.imaging.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffRational

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Initialisiert eine neue Instanz der [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) Klasse. |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Initialisiert eine neue Instanz der [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) Klasse. |
| [TiffRational(value)](#TiffRational_value_3) | Initialisiert eine neue Instanz der [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| EPSILON [statisch] | float | r | Das epsilon für die Bruchberechnung. |
| Nenner | int | r | Liest den Nenner. |
| Zähler | int | r | Liest den Zähler. |
| Wert | float | r | Liest den float-Wert. |
| value_d | float | r | Liest den double-Wert. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | Nähert den angegebenen Wert an einen Bruch an. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | Nähert den angegebenen Wert an einen Bruch an. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | Nähert den angegebenen Wert an einen Bruch an. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | Nähert den angegebenen Wert an einen Bruch an. |
| [approximate_fraction(value)](#approximate_fraction_value_5) | Nähert den angegebenen Wert an einen Bruch an. |
| [approximate_fraction(value)](#approximate_fraction_value_6) | Nähert den angegebenen Wert an einen Bruch an. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | Nähert den angegebenen Wert an einen Bruch an. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | Nähert den angegebenen Wert an einen Bruch an. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Initialisiert eine neue Instanz der [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) Klasse.

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Initialisiert eine neue Instanz der [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zähler | int | Der Zähler. |
| Nenner | int | Der Nenner. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Initialisiert eine neue Instanz der [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | int | Der Zählerwert. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

Nähert den angegebenen Wert an einen Bruch an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Eine rationale Zahl mit einem Fehler kleiner als [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

Nähert den angegebenen Wert an einen Bruch an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |
| epsilon | float | Der zulässige Fehler. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Eine rationale Zahl mit einem Fehler kleiner als _epsilon_. |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

Nähert den angegebenen Wert an einen Bruch an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Eine rationale Zahl mit einem Fehler kleiner als [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

Nähert den angegebenen Wert an einen Bruch an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |
| epsilon | float | Der zulässige Fehler. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Eine rationale Zahl mit einem Fehler kleiner als _epsilon_. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

Nähert den angegebenen Wert an einen Bruch an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Eine rationale Zahl mit einem Fehler kleiner als [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

Nähert den angegebenen Wert an einen Bruch an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Eine rationale Zahl mit einem Fehler kleiner als [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

Nähert den angegebenen Wert an einen Bruch an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |
| epsilon | float | Der zulässige Fehler. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Eine rationale Zahl mit einem Fehler kleiner als _epsilon_. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

Nähert den angegebenen Wert an einen Bruch an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |
| epsilon | float | Der zulässige Fehler. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Eine rationale Zahl mit einem Fehler kleiner als _epsilon_. |


