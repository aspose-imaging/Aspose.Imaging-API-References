---
title: "PointF"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una coppia ordinata di coordinate in virgola mobile x e y che definisce un punto in un piano bidimensionale."
type: docs
weight: 87
url: /it/java/com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Rappresenta una coppia ordinata di coordinate in virgola mobile x e y che definisce un punto in un piano bidimensionale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Inizializza una nuova istanza della struttura `com.aspose.imaging.PointF` con le coordinate specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della struttura `com.aspose.imaging.PointF` che ha i valori `com.aspose.imaging.PointF.X` e `com.aspose.imaging.PointF.Y` impostati a zero. |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Trasla un `com.aspose.imaging.PointF` di una data `com.aspose.imaging.Size`. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Trasla un `com.aspose.imaging.PointF` del negativo di una data `com.aspose.imaging.Size`. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Trasla il `com.aspose.imaging.PointF` di una `com.aspose.imaging.SizeF` specificata. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Trasla un `com.aspose.imaging.PointF` del negativo di una `com.aspose.imaging.SizeF` specificata. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Confronta due strutture `com.aspose.imaging.PointF`. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Determina se le coordinate dei punti specificati non sono uguali. |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Trasla un dato `com.aspose.imaging.PointF` della `com.aspose.imaging.Size` specificata. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Trasla un `com.aspose.imaging.PointF` del negativo di una dimensione specificata. |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Trasla un dato `com.aspose.imaging.PointF` di una `com.aspose.imaging.SizeF` specificata. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Trasla un `com.aspose.imaging.PointF` del negativo di una dimensione specificata. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se questo `com.aspose.imaging.PointF` è vuoto. |
| [getX()](#getX--) | Ottiene o imposta la coordinata x di questo `com.aspose.imaging.PointF`. |
| [setX(float value)](#setX-float-) | Ottiene o imposta la coordinata x di questo `com.aspose.imaging.PointF`. |
| [getY()](#getY--) | Ottiene o imposta la coordinata y di questo `com.aspose.imaging.PointF`. |
| [setY(float value)](#setY-float-) | Ottiene o imposta la coordinata y di questo `com.aspose.imaging.PointF`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Specifica se questo `com.aspose.imaging.PointF` contiene le stesse coordinate dell'`System.Object` specificato. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa struttura `com.aspose.imaging.PointF`. |
| [toString()](#toString--) | Converte questo `com.aspose.imaging.PointF` in una stringa leggibile dall'uomo. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Inizializza una nuova istanza della struttura `com.aspose.imaging.PointF` con le coordinate specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La posizione orizzontale del punto. |
| y | float | La posizione verticale del punto. |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Ottiene una nuova istanza della struttura `com.aspose.imaging.PointF` che ha i valori `com.aspose.imaging.PointF.X` e `com.aspose.imaging.PointF.Y` impostati a zero.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Trasla un `com.aspose.imaging.PointF` di una data `com.aspose.imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `com.aspose.imaging.PointF` da tradurre. |
| size | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` che specifica la coppia di numeri da aggiungere alle coordinate di `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Trasla un `com.aspose.imaging.PointF` del negativo di una data `com.aspose.imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` da tradurre. |
| size | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` che specifica i numeri da sottrarre dalle coordinate x e y del `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Trasla il `com.aspose.imaging.PointF` di una `com.aspose.imaging.SizeF` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `com.aspose.imaging.PointF` da tradurre. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Il `com.aspose.imaging.SizeF` che specifica i numeri da aggiungere alle coordinate x e y del `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Trasla un `com.aspose.imaging.PointF` del negativo di una `com.aspose.imaging.SizeF` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `com.aspose.imaging.PointF` da tradurre. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Il `com.aspose.imaging.SizeF` che specifica i numeri da sottrarre dalle coordinate di `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Confronta due strutture `com.aspose.imaging.PointF`. Il risultato specifica se i valori delle proprietà `com.aspose.imaging.PointF.X` e `com.aspose.imaging.PointF.Y` delle due strutture `com.aspose.imaging.PointF` sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Un primo `com.aspose.imaging.PointF` da confrontare. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Un secondo `com.aspose.imaging.PointF` da confrontare. |

**Returns:**
boolean - True se i valori `com.aspose.imaging.PointF.X` e `com.aspose.imaging.PointF.Y` delle prime e seconde strutture `com.aspose.imaging.PointF` sono uguali; altrimenti, false.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Determina se le coordinate dei punti specificati non sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Un primo `com.aspose.imaging.PointF` da confrontare. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Un secondo `com.aspose.imaging.PointF` da confrontare. |

**Returns:**
boolean - True per indicare che i valori `com.aspose.imaging.PointF.X` e `com.aspose.imaging.PointF.Y` di `point1` e `point2` non sono uguali; altrimenti, false.
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


Trasla un dato `com.aspose.imaging.PointF` della `com.aspose.imaging.Size` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `com.aspose.imaging.PointF` da tradurre. |
| size | [Size](../../com.aspose.imaging/size) | Il `com.aspose.imaging.Size` che specifica i numeri da aggiungere alle coordinate di `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Trasla un `com.aspose.imaging.PointF` del negativo di una dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `com.aspose.imaging.PointF` da tradurre. |
| size | [Size](../../com.aspose.imaging/size) | Il `com.aspose.imaging.Size` che specifica i numeri da sottrarre dalle coordinate di `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Trasla un dato `com.aspose.imaging.PointF` di una `com.aspose.imaging.SizeF` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `com.aspose.imaging.PointF` da tradurre. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Il `com.aspose.imaging.SizeF` che specifica i numeri da aggiungere alle coordinate di `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Trasla un `com.aspose.imaging.PointF` del negativo di una dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `com.aspose.imaging.PointF` da tradurre. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Il `com.aspose.imaging.SizeF` che specifica i numeri da sottrarre dalle coordinate di `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ottiene un valore che indica se questo `com.aspose.imaging.PointF` è vuoto.

**Returns:**
boolean - True se entrambi `com.aspose.imaging.PointF.X` e `com.aspose.imaging.PointF.Y` sono 0; altrimenti, false.
### getX() {#getX--}
```
public float getX()
```


Ottiene o imposta la coordinata x di questo `com.aspose.imaging.PointF`.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Ottiene o imposta la coordinata x di questo `com.aspose.imaging.PointF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getY() {#getY--}
```
public float getY()
```


Ottiene o imposta la coordinata y di questo `com.aspose.imaging.PointF`.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Ottiene o imposta la coordinata y di questo `com.aspose.imaging.PointF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Specifica se questo `com.aspose.imaging.PointF` contiene le stesse coordinate dell'`System.Object` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se `obj` è un `com.aspose.imaging.PointF` e ha le stesse coordinate di questo `com.aspose.imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa struttura `com.aspose.imaging.PointF`.

**Returns:**
int - Un valore intero che specifica un valore hash per questa struttura `com.aspose.imaging.PointF`.
### toString() {#toString--}
```
public String toString()
```


Converte questo `com.aspose.imaging.PointF` in una stringa leggibile dall'uomo.

**Returns:**
java.lang.String - Una stringa che rappresenta questo `com.aspose.imaging.PointF`.
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
