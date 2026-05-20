---
title: "TiffRational"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo rationale TIFF."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.tiff/tiffrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffRational
```

Il tipo rationale TIFF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffRational()](#TiffRational--) | Inizializza una nuova istanza della classe `TiffRational`. |
| [TiffRational(long value)](#TiffRational-long-) | Inizializza una nuova istanza della classe `TiffRational`. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Inizializza una nuova istanza della classe `TiffRational`. |
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
| [toString()](#toString--) | Converte in stringa. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'`Object` specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Inizializza una nuova istanza della classe `TiffRational`.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Inizializza una nuova istanza della classe `TiffRational`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | long | Il valore del numeratore. |

Il numeratore sarà usato come valore specificato e il denominatore sarà uguale a 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Inizializza una nuova istanza della classe `TiffRational`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numeratore | long | Il numeratore. |
| denominatore | long | Il denominatore. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


L'epsilon per il calcolo della frazione

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Il valore. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Restituisce il denominatore.

Valore: il denominatore.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Restituisce il numeratore.

Valore: il numeratore.

**Returns:**
long
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


Converte in stringa.

**Returns:**
java.lang.String - Una stringa che rappresenta questa istanza.
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
