---
title: "TiffSRational"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type rationnel TIFF."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.tiff/tiffsrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

Le type rationnel TIFF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Initialise une nouvelle instance de la classe `TiffSRational`. |
| [TiffSRational(int value)](#TiffSRational-int-) | Initialise une nouvelle instance de la classe [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational). |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Initialise une nouvelle instance de la classe `TiffSRational`. |
## Champs

| Champ | Description |
| --- | --- |
| [EPSILON](#EPSILON) | L'epsilon pour le calcul de fraction |
## Méthodes

| Méthode | Description |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Approxime la valeur fournie en une fraction. |
| [approximateFraction(double value)](#approximateFraction-double-) | Approxime la valeur fournie en une fraction. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Approxime la valeur fournie en une fraction. |
| [approximateFraction(float value)](#approximateFraction-float-) | Approxime la valeur fournie en une fraction. |
| [getDenominator()](#getDenominator--) | Obtient le dénominateur. |
| [getNominator()](#getNominator--) | Obtient le numérateur. |
| [getValue()](#getValue--) | Obtient la valeur flottante. |
| [getValueD()](#getValueD--) | Obtient la valeur double. |
| [toString()](#toString--) | Renvoie une `System.String` qui représente cette instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'`Object` spécifié est égal à cette instance. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Initialise une nouvelle instance de la classe `TiffSRational`.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Initialise une nouvelle instance de la classe [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La valeur du numérateur. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Initialise une nouvelle instance de la classe `TiffSRational`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| numérateur | int | Le numérateur. |
| dénominateur | int | Le dénominateur. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


L'epsilon pour le calcul de fraction

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Approxime la valeur fournie en une fraction.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La valeur. |
| epsilon | double | L'erreur autorisée. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Approxime la valeur fournie en une fraction.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La valeur. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Approxime la valeur fournie en une fraction.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur. |
| epsilon | double | L'erreur autorisée. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Approxime la valeur fournie en une fraction.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Obtient le dénominateur.

Valeur : le dénominateur.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Obtient le numérateur.

Valeur : le numérateur.

**Returns:**
int
### getValue() {#getValue--}
```
public float getValue()
```


Obtient la valeur flottante.

Valeur : la valeur flottante.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Obtient la valeur double.

Valeur : la valeur double.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Renvoie une `System.String` qui représente cette instance.

**Returns:**
java.lang.String - Une `System.String` qui représente cette instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'`Object` spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'`Object` à comparer avec cette instance. |

**Returns:**
booléen - `true` si l'`Object` spécifié est égal à cette instance ; sinon, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
