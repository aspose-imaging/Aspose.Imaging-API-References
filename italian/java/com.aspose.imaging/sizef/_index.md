---
title: "SizeF"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Memorizza una coppia ordinata di numeri a virgola mobile tipicamente la larghezza e l'altezza di un rettangolo."
type: docs
weight: 105
url: /it/java/com.aspose.imaging/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class SizeF extends Struct<SizeF>
```

Memorizza una coppia ordinata di numeri a virgola mobile, tipicamente la larghezza e l'altezza di un rettangolo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(SizeF size)](#SizeF-com.aspose.imaging.SizeF-) | Inizializza una nuova istanza della struttura `Aspose.Imaging.SizeF` dal `Aspose.Imaging.SizeF` specificato. |
| [SizeF(PointF point)](#SizeF-com.aspose.imaging.PointF-) | Inizializza una nuova istanza della struttura `Aspose.Imaging.SizeF` dal `Aspose.Imaging.PointF` specificato. |
| [SizeF(float width, float height)](#SizeF-float-float-) | Inizializza una nuova istanza della struttura `Aspose.Imaging.SizeF` dalle dimensioni specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della struttura `Aspose.Imaging.SizeF` che ha i valori `Aspose.Imaging.SizeF.Width` e `Aspose.Imaging.SizeF.Height` impostati a zero. |
| [op_Addition(SizeF size1, SizeF size2)](#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Aggiunge la larghezza e l'altezza di una struttura `Aspose.Imaging.SizeF` alla larghezza e all'altezza di un'altra struttura `Aspose.Imaging.SizeF`. |
| [op_Subtraction(SizeF size1, SizeF size2)](#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Sottrae la larghezza e l'altezza di una struttura `Aspose.Imaging.SizeF` dalla larghezza e dall'altezza di un'altra struttura `Aspose.Imaging.SizeF`. |
| [op_Equality(SizeF size1, SizeF size2)](#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Verifica se due strutture `Aspose.Imaging.SizeF` sono uguali. |
| [op_Inequality(SizeF size1, SizeF size2)](#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Verifica se due strutture `Aspose.Imaging.SizeF` sono diverse. |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.imaging.SizeF-) | Converte il `Aspose.Imaging.SizeF` specificato in un `Aspose.Imaging.PointF`. |
| [add(SizeF size1, SizeF size2)](#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Aggiunge la larghezza e l'altezza di una struttura `Aspose.Imaging.SizeF` alla larghezza e all'altezza di un'altra struttura `Aspose.Imaging.SizeF`. |
| [subtract(SizeF size1, SizeF size2)](#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Sottrae la larghezza e l'altezza di una struttura `Aspose.Imaging.SizeF` dalla larghezza e dall'altezza di un'altra struttura `Aspose.Imaging.SizeF`. |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) |  |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se questo `Aspose.Imaging.SizeF` ha larghezza e altezza pari a zero. |
| [getWidth()](#getWidth--) | Ottiene o imposta la componente orizzontale di questo `Aspose.Imaging.SizeF`. |
| [setWidth(float value)](#setWidth-float-) | Ottiene o imposta la componente orizzontale di questo `Aspose.Imaging.SizeF`. |
| [getHeight()](#getHeight--) | Ottiene o imposta la componente verticale di questo `Aspose.Imaging.SizeF`. |
| [setHeight(float value)](#setHeight-float-) | Ottiene o imposta la componente verticale di questo `Aspose.Imaging.SizeF`. |
| [toPointF()](#toPointF--) | Converte un `Aspose.Imaging.SizeF` in un `Aspose.Imaging.PointF`. |
| [toSize()](#toSize--) | Converte un `Aspose.Imaging.SizeF` in una struttura `Aspose.Imaging.Size` con valori di dimensione troncati. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se l'oggetto specificato è un `Aspose.Imaging.SizeF` con le stesse dimensioni di questo `Aspose.Imaging.SizeF`. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa struttura `Aspose.Imaging.Size`. |
| [toString()](#toString--) | Crea una stringa leggibile dall'uomo che rappresenta questo `Aspose.Imaging.SizeF`. |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.imaging.SizeF-) |  |
| [Clone()](#Clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(SizeF size) {#SizeF-com.aspose.imaging.SizeF-}
```
public SizeF(SizeF size)
```


Inizializza una nuova istanza della struttura `Aspose.Imaging.SizeF` dal `Aspose.Imaging.SizeF` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Il `Aspose.Imaging.SizeF` da cui creare il nuovo `Aspose.Imaging.SizeF`. |

### SizeF(PointF point) {#SizeF-com.aspose.imaging.PointF-}
```
public SizeF(PointF point)
```


Inizializza una nuova istanza della struttura `Aspose.Imaging.SizeF` dal `Aspose.Imaging.PointF` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `Aspose.Imaging.PointF` da cui inizializzare questo `Aspose.Imaging.SizeF`. |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Inizializza una nuova istanza della struttura `Aspose.Imaging.SizeF` dalle dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | float | La componente di larghezza del nuovo `Aspose.Imaging.SizeF`. |
| height | float | La componente di altezza del nuovo `Aspose.Imaging.SizeF`. |

### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```


Ottiene una nuova istanza della struttura `Aspose.Imaging.SizeF` che ha i valori `Aspose.Imaging.SizeF.Width` e `Aspose.Imaging.SizeF.Height` impostati a zero.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
### op_Addition(SizeF size1, SizeF size2) {#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Addition(SizeF size1, SizeF size2)
```


Aggiunge la larghezza e l'altezza di una struttura `Aspose.Imaging.SizeF` alla larghezza e all'altezza di un'altra struttura `Aspose.Imaging.SizeF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Il primo `Aspose.Imaging.SizeF` da aggiungere. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Il secondo `Aspose.Imaging.SizeF` da aggiungere. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### op_Subtraction(SizeF size1, SizeF size2) {#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Subtraction(SizeF size1, SizeF size2)
```


Sottrae la larghezza e l'altezza di una struttura `Aspose.Imaging.SizeF` dalla larghezza e dall'altezza di un'altra struttura `Aspose.Imaging.SizeF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Il `Aspose.Imaging.SizeF` sul lato sinistro dell'operatore di sottrazione. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Il `Aspose.Imaging.SizeF` sul lato destro dell'operatore di sottrazione. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` that is the result of the subtraction operation.
### op_Equality(SizeF size1, SizeF size2) {#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Equality(SizeF size1, SizeF size2)
```


Verifica se due strutture `Aspose.Imaging.SizeF` sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` sul lato sinistro dell'operatore di uguaglianza. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` sul lato destro dell'operatore di uguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se `size1` e `size2` hanno larghezza e altezza uguali; altrimenti, false.
### op_Inequality(SizeF size1, SizeF size2) {#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Inequality(SizeF size1, SizeF size2)
```


Verifica se due strutture `Aspose.Imaging.SizeF` sono diverse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` sul lato sinistro dell'operatore di disuguaglianza. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` sul lato destro dell'operatore di disuguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se `size1` e `size2` differiscono per larghezza o altezza; false se `size1` e `size2` sono uguali.
### to_PointF(SizeF size) {#to-PointF-com.aspose.imaging.SizeF-}
```
public static PointF to_PointF(SizeF size)
```


Converte il `Aspose.Imaging.SizeF` specificato in un `Aspose.Imaging.PointF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` da convertire |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `Aspose.Imaging.PointF` structure to which this operator converts.
### add(SizeF size1, SizeF size2) {#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF add(SizeF size1, SizeF size2)
```


Aggiunge la larghezza e l'altezza di una struttura `Aspose.Imaging.SizeF` alla larghezza e all'altezza di un'altra struttura `Aspose.Imaging.SizeF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Il primo `Aspose.Imaging.SizeF` da aggiungere. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Il secondo `Aspose.Imaging.SizeF` da aggiungere. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### subtract(SizeF size1, SizeF size2) {#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF subtract(SizeF size1, SizeF size2)
```


Sottrae la larghezza e l'altezza di una struttura `Aspose.Imaging.SizeF` dalla larghezza e dall'altezza di un'altra struttura `Aspose.Imaging.SizeF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` sul lato sinistro dell'operatore di sottrazione. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | La struttura `Aspose.Imaging.SizeF` sul lato destro dell'operatore di sottrazione. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` that is a result of the subtraction operation.
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.imaging/sizef) |  |
| obj2 | [SizeF](../../com.aspose.imaging/sizef) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ottiene un valore che indica se questo `Aspose.Imaging.SizeF` ha larghezza e altezza pari a zero.

**Returns:**
boolean - Questa proprietà restituisce true quando questo `Aspose.Imaging.SizeF` ha sia larghezza che altezza pari a zero; altrimenti, false.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Ottiene o imposta la componente orizzontale di questo `Aspose.Imaging.SizeF`.

**Returns:**
float - La componente orizzontale di questo `Aspose.Imaging.SizeF`, tipicamente misurata in pixel.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Ottiene o imposta la componente orizzontale di questo `Aspose.Imaging.SizeF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Ottiene o imposta la componente verticale di questo `Aspose.Imaging.SizeF`.

**Returns:**
float - La componente verticale di questo `Aspose.Imaging.SizeF`, tipicamente misurata in pixel.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Ottiene o imposta la componente verticale di questo `Aspose.Imaging.SizeF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### toPointF() {#toPointF--}
```
public PointF toPointF()
```


Converte un `Aspose.Imaging.SizeF` in un `Aspose.Imaging.PointF`.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns a `Aspose.Imaging.PointF` structure.
### toSize() {#toSize--}
```
public Size toSize()
```


Converte un `Aspose.Imaging.SizeF` in una struttura `Aspose.Imaging.Size` con valori di dimensione troncati.

**Returns:**
[Size](../../com.aspose.imaging/size) - Returns a `Aspose.Imaging.Size` structure.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se l'oggetto specificato è un `Aspose.Imaging.SizeF` con le stesse dimensioni di questo `Aspose.Imaging.SizeF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se `obj` è un `Aspose.Imaging.SizeF` e ha la stessa larghezza e altezza di questo `Aspose.Imaging.SizeF`; altrimenti, false.
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


Crea una stringa leggibile dall'uomo che rappresenta questo `Aspose.Imaging.SizeF`.

**Returns:**
java.lang.String - Una stringa che rappresenta questo `Aspose.Imaging.SizeF`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.imaging.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.imaging/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
