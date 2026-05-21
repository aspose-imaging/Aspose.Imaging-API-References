---
title: "TiffSRational"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo racional tiff."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.tiff/tiffsrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

El tipo racional tiff.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Inicializa una nueva instancia de la clase `TiffSRational`. |
| [TiffSRational(int value)](#TiffSRational-int-) | Inicializa una nueva instancia de la clase [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational). |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Inicializa una nueva instancia de la clase `TiffSRational`. |
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
| [toString()](#toString--) | Devuelve una `System.String` que representa esta instancia. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `Object` especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Inicializa una nueva instancia de la clase `TiffSRational`.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Inicializa una nueva instancia de la clase [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El valor del numerador. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Inicializa una nueva instancia de la clase `TiffSRational`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerador | int | El numerador. |
| denominador | int | El denominador. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


El epsilon para el cálculo de fracciones

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | El valor. |
| epsilon | double | El error permitido. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | El valor. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor. |
| epsilon | double | El error permitido. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Aproxima el valor proporcionado a una fracción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Obtiene el denominador.

Valor: El denominador.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Obtiene el numerador.

Valor: El numerador.

**Returns:**
int
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


Devuelve una `System.String` que representa esta instancia.

**Returns:**
java.lang.String - Un `System.String` que representa esta instancia.
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
