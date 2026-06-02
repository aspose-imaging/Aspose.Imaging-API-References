---
title: "Size"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta le dimensioni."
type: docs
weight: 104
url: /it/java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Rappresenta le dimensioni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | Inizializza una nuova istanza della struttura `Aspose.Imaging.Size` dal `Aspose.Imaging.Point` specificato. |
| [Size(int width, int height)](#Size-int-int-) | Inizializza una nuova istanza della struttura `Aspose.Imaging.Size` dalle dimensioni specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della struttura `Aspose.Imaging.Size` con i valori `Aspose.Imaging.Size.Width` e `Aspose.Imaging.Size.Height` impostati a zero. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | Converte il `Aspose.Imaging.Size` specificato in un `Aspose.Imaging.SizeF`. |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Aggiunge la larghezza e l'altezza di una struttura `Aspose.Imaging.Size` alla larghezza e all'altezza di un'altra struttura `Aspose.Imaging.Size`. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Sottrae la larghezza e l'altezza di una struttura `Aspose.Imaging.Size` dalla larghezza e dall'altezza di un'altra struttura `Aspose.Imaging.Size`. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Verifica se due strutture `Aspose.Imaging.Size` sono uguali. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Verifica se due strutture `Aspose.Imaging.Size` sono diverse. |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | Converte il `Aspose.Imaging.Size` specificato in un `Aspose.Imaging.Point`. |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Aggiunge la larghezza e l'altezza di una struttura `Aspose.Imaging.Size` alla larghezza e all'altezza di un'altra struttura `Aspose.Imaging.Size`. |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | Converte la struttura `Aspose.Imaging.SizeF` specificata in una struttura `Aspose.Imaging.Size` arrotondando i valori della struttura `Aspose.Imaging.Size` al prossimo intero superiore. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Sottrae la larghezza e l'altezza di una struttura `Aspose.Imaging.Size` dalla larghezza e dall'altezza di un'altra struttura `Aspose.Imaging.Size`. |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | Converte la struttura `Aspose.Imaging.SizeF` specificata in una struttura `Aspose.Imaging.Size` troncando i valori della struttura `Aspose.Imaging.SizeF` al prossimo intero inferiore. |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | Converte la struttura `Aspose.Imaging.SizeF` specificata in una struttura `Aspose.Imaging.Size` arrotondando i valori della struttura `Aspose.Imaging.SizeF` al valore intero più vicino. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se questo `Aspose.Imaging.Size` ha larghezza e altezza pari a 0. |
| [getWidth()](#getWidth--) | Ottiene o imposta la componente orizzontale di questo `Aspose.Imaging.Size`. |
| [setWidth(int value)](#setWidth-int-) | Ottiene o imposta la componente orizzontale di questo `Aspose.Imaging.Size`. |
| [getHeight()](#getHeight--) | Ottiene o imposta la componente verticale di questo `Aspose.Imaging.Size`. |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta la componente verticale di questo `Aspose.Imaging.Size`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se l'oggetto specificato è un `Aspose.Imaging.Size` con le stesse dimensioni di questo `Aspose.Imaging.Size`. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa struttura `Aspose.Imaging.Size`. |
| [toString()](#toString--) | Crea una stringa leggibile dall'uomo che rappresenta questo `Aspose.Imaging.Size`. |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


Inizializza una nuova istanza della struttura `Aspose.Imaging.Size` dal `Aspose.Imaging.Point` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il `Aspose.Imaging.Point` da cui inizializzare questo `Aspose.Imaging.Size`. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Inizializza una nuova istanza della struttura `Aspose.Imaging.Size` dalle dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La componente di larghezza del nuovo `Aspose.Imaging.Size`. |
| height | int | La componente di altezza del nuovo `Aspose.Imaging.Size`. |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Ottiene una nuova istanza della struttura `Aspose.Imaging.Size` con i valori `Aspose.Imaging.Size.Width` e `Aspose.Imaging.Size.Height` impostati a zero.

**Returns:**
[Size](../../com.aspose.imaging/size)
### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


Converte il `Aspose.Imaging.Size` specificato in un `Aspose.Imaging.SizeF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Il `Aspose.Imaging.Size` da convertire. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Aggiunge la larghezza e l'altezza di una struttura `Aspose.Imaging.Size` alla larghezza e all'altezza di un'altra struttura `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Il primo `Aspose.Imaging.Size` da aggiungere. |
| size2 | [Size](../../com.aspose.imaging/size) | Il secondo `Aspose.Imaging.Size` da aggiungere. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Sottrae la larghezza e l'altezza di una struttura `Aspose.Imaging.Size` dalla larghezza e dall'altezza di un'altra struttura `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La struttura `Aspose.Imaging.Size` sul lato sinistro dell'operatore di sottrazione. |
| size2 | [Size](../../com.aspose.imaging/size) | La struttura `Aspose.Imaging.Size` sul lato destro dell'operatore di sottrazione. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Verifica se due strutture `Aspose.Imaging.Size` sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La struttura `Aspose.Imaging.Size` sul lato sinistro dell'operatore di uguaglianza. |
| size2 | [Size](../../com.aspose.imaging/size) | La struttura `Aspose.Imaging.Size` sul lato destro dell'operatore di uguaglianza. |

**Returns:**
boolean - True se `size1` e `size2` hanno larghezza e altezza uguali; altrimenti, false.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Verifica se due strutture `Aspose.Imaging.Size` sono diverse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La struttura `Aspose.Imaging.Size` sul lato sinistro dell'operatore di disuguaglianza. |
| size2 | [Size](../../com.aspose.imaging/size) | La struttura `Aspose.Imaging.Size` sul lato destro dell'operatore di disuguaglianza. |

**Returns:**
boolean - True se `size1` e `size2` differiscono in larghezza o altezza; false se `size1` e `size2` sono uguali.
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


Converte il `Aspose.Imaging.Size` specificato in un `Aspose.Imaging.Point`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Il `Aspose.Imaging.Size` da convertire. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


Aggiunge la larghezza e l'altezza di una struttura `Aspose.Imaging.Size` alla larghezza e all'altezza di un'altra struttura `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Il primo `Aspose.Imaging.Size` da aggiungere. |
| size2 | [Size](../../com.aspose.imaging/size) | Il secondo `Aspose.Imaging.Size` da aggiungere. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


Converte la struttura `Aspose.Imaging.SizeF` specificata in una struttura `Aspose.Imaging.Size` arrotondando i valori della struttura `Aspose.Imaging.Size` al prossimo intero superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` da convertire. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Sottrae la larghezza e l'altezza di una struttura `Aspose.Imaging.Size` dalla larghezza e dall'altezza di un'altra struttura `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La struttura `Aspose.Imaging.Size` sul lato sinistro dell'operatore di sottrazione. |
| size2 | [Size](../../com.aspose.imaging/size) | La struttura `Aspose.Imaging.Size` sul lato destro dell'operatore di sottrazione. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


Converte la struttura `Aspose.Imaging.SizeF` specificata in una struttura `Aspose.Imaging.Size` troncando i valori della struttura `Aspose.Imaging.SizeF` al prossimo intero inferiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` da convertire. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


Converte la struttura `Aspose.Imaging.SizeF` specificata in una struttura `Aspose.Imaging.Size` arrotondando i valori della struttura `Aspose.Imaging.SizeF` al valore intero più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` da convertire. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ottiene un valore che indica se questo `Aspose.Imaging.Size` ha larghezza e altezza pari a 0.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene o imposta la componente orizzontale di questo `Aspose.Imaging.Size`.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ottiene o imposta la componente orizzontale di questo `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene o imposta la componente verticale di questo `Aspose.Imaging.Size`.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ottiene o imposta la componente verticale di questo `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se l'oggetto specificato è un `Aspose.Imaging.Size` con le stesse dimensioni di questo `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` da testare. |

**Returns:**
boolean - True se `obj` è un `Aspose.Imaging.Size` e ha la stessa larghezza e altezza di questo `Aspose.Imaging.Size`; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa struttura `Aspose.Imaging.Size`.

**Returns:**
int - Un valore intero che specifica un valore hash per questa struttura `Aspose.Imaging.Size`.
### toString() {#toString--}
```
public String toString()
```


Crea una stringa leggibile dall'uomo che rappresenta questo `Aspose.Imaging.Size`.

**Returns:**
java.lang.String - Una stringa che rappresenta questo `Aspose.Imaging.Size`.
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
