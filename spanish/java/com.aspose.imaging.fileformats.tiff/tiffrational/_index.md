---
title: "TiffRational"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo racional tiff."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.tiff/tiffrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffRational
```

El tipo racional tiff.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffRational()](#TiffRational--) | Inicializa una nueva instancia de la clase `TiffRational`. |
| [TiffRational(long value)](#TiffRational-long-) | Inicializa una nueva instancia de la clase `TiffRational`. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Inicializa una nueva instancia de la clase `TiffRational`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [EPSILON](#EPSILON) | El epsilon para el cálculo de fracciones |
## Métodos

| Método | Descripción |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Aproxima el valor proporcionado a una fracción. |
| [approximateFraction(double value)](#approximateFraction-double-) | Aproxima el valor proporcionado a una fracción. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Aproxima el valor proporcionado a una fracción. |
| [approximateFraction(float value)](#approximateFraction-float-) | Aproxima el valor proporcionado a una fracción. |
| [getDenominator()](#getDenominator--) | Obtiene el denominador. |
| [getNominator()](#getNominator--) | Obtiene el numerador. |
| [getValue()](#getValue--) | Obtiene el valor flotante. |
| [getValueD()](#getValueD--) | Obtiene el valor doble. |
| [toString()](#toString--) | Convierte a cadena. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `Object` especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Inicializa una nueva instancia de la clase `TiffRational`.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Inicializa una nueva instancia de la clase `TiffRational`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | long | El valor del numerador. |

El numerador se usará como el valor especificado y el denominador será igual a 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Inicializa una nueva instancia de la clase `TiffRational`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerador | long | El numerador. |
| denominador | long | El denominador. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


El epsilon para el cálculo de fracciones

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | El valor. |
| epsilon | double | El error permitido. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | El valor. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor. |
| epsilon | double | El error permitido. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Obtiene el denominador.

Valor: El denominador.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Obtiene el numerador.

Valor: El numerador.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Obtiene el valor flotante.

Valor: El valor flotante.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Obtiene el valor doble.

Valor: El valor doble.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Convierte a cadena.

**Returns:**
java.lang.String - Una cadena que representa esta instancia.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el `Object` especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `Object` para comparar con esta instancia. |

**Returns:**
boolean - `true` si el `Object` especificado es igual a esta instancia; de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
