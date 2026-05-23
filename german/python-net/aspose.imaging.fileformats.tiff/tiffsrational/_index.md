---
title: "TiffSRational Klasse"
type: docs
weight: 280
url: /de/python-net/aspose.imaging.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffSRational

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initialisiert eine neue Instanz der [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) Klasse. |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initialisiert eine neue Instanz der [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) Klasse. |
| [TiffSRational(value)](#TiffSRational_value_3) | Initialisiert eine neue Instanz der [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) Klasse. |
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


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Initialisiert eine neue Instanz der [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) Klasse.

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Initialisiert eine neue Instanz der [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zähler | int | Der Zähler. |
| Nenner | int | Der Nenner. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Initialisiert eine neue Instanz der [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | int | Der Wert. |

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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Eine rationale Zahl mit einem Fehler kleiner als [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Eine rationale Zahl mit einem Fehler kleiner als _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Eine rationale Zahl mit einem Fehler kleiner als [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Eine rationale Zahl mit einem Fehler kleiner als _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Eine rationale Zahl mit einem Fehler kleiner als [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Eine rationale Zahl mit einem Fehler kleiner als [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Eine rationale Zahl mit einem Fehler kleiner als _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Eine rationale Zahl mit einem Fehler kleiner als _epsilon_. |


