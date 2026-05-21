---
title: "TiffSRational"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo rationale TIFF."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.tiff/tiffsrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

Il tipo rationale TIFF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Inizializza una nuova istanza della classe `TiffSRational`. |
| [TiffSRational(int value)](#TiffSRational-int-) | Inizializza una nuova istanza della classe [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational). |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Inizializza una nuova istanza della classe `TiffSRational`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EPSILON](#EPSILON) | L'epsilon per il calcolo della frazione |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Approssima il valore fornito a una frazione. |
| [approximateFraction(double value)](#approximateFraction-double-) | Approssima il valore fornito a una frazione. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Approssima il valore fornito a una frazione. |
| [approximateFraction(float value)](#approximateFraction-float-) | Approssima il valore fornito a una frazione. |
| [getDenominator()](#getDenominator--) | Restituisce il denominatore. |
| [getNominator()](#getNominator--) | Restituisce il numeratore. |
| [getValue()](#getValue--) | Restituisce il valore float. |
| [getValueD()](#getValueD--) | Restituisce il valore double. |
| [toString()](#toString--) | Restituisce una `System.String` che rappresenta questa istanza. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'`Object` specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Inizializza una nuova istanza della classe `TiffSRational`.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Inizializza una nuova istanza della classe [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il valore del numeratore. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Inizializza una nuova istanza della classe `TiffSRational`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numeratore | int | Il numeratore. |
| denominatore | int | Il denominatore. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


L'epsilon per il calcolo della frazione

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Il valore. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Restituisce il denominatore.

Valore: il denominatore.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Restituisce il numeratore.

Valore: il numeratore.

**Returns:**
int
### getValue() {#getValue--}
```
public float getValue()
```


Restituisce il valore float.

Valore: il valore float.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Restituisce il valore double.

Valore: il valore double.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Restituisce una `System.String` che rappresenta questa istanza.

**Returns:**
java.lang.String - Una `System.String` che rappresenta questa istanza.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'`Object` specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`Object` da confrontare con questa istanza. |

**Returns:**
boolean - `true` se l'`Object` specificato è uguale a questa istanza; altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
