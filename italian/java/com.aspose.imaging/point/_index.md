---
title: "Point"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una coppia ordinata di coordinate intere x e y che definisce un punto in un piano bidimensionale."
type: docs
weight: 86
url: /it/java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Rappresenta una coppia ordinata di coordinate intere x e y che definisce un punto in un piano bidimensionale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Inizializza una nuova istanza della struttura `Aspose.Imaging.Point` con le coordinate specificate. |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | Inizializza una nuova istanza della struttura `Aspose.Imaging.Point` dalla struttura `Aspose.Imaging.Size`. |
| [Point(int dw)](#Point-int-) | Inizializza una nuova istanza della struttura `Aspose.Imaging.Point` usando coordinate specificate da un valore intero. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della struttura `Aspose.Imaging.Point` con i valori `Aspose.Imaging.Point.X` e `Aspose.Imaging.Point.Y` impostati a zero. |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Aggiunge la `Aspose.Imaging.Size` specificata al `Aspose.Imaging.Point` specificato. |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Restituisce il risultato della sottrazione della `Aspose.Imaging.Size` specificata dal `Aspose.Imaging.Point` specificato. |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | Converte il `Aspose.Imaging.PointF` specificato in un `Aspose.Imaging.Point` arrotondando i valori del `Aspose.Imaging.PointF` al prossimo intero superiore. |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | Converte il `Aspose.Imaging.PointF` specificato in un oggetto `Aspose.Imaging.Point` arrotondando i valori del `Aspose.Imaging.Point` all'intero più vicino. |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | Converte il `Aspose.Imaging.PointF` specificato in un `Aspose.Imaging.Point` troncando i valori del `Aspose.Imaging.Point`. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Trasla un `Aspose.Imaging.Point` di una data `Aspose.Imaging.Size`. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Trasla un `Aspose.Imaging.Point` del negativo di una data `Aspose.Imaging.Size`. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Confronta due oggetti `Aspose.Imaging.Point`. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Confronta due oggetti `Aspose.Imaging.Point`. |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | Converte la struttura `Aspose.Imaging.Point` specificata in una struttura `Aspose.Imaging.Size`. |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | Converte la struttura `Point` specificata nella struttura `PointF`. |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | Decompone un oggetto Point inserito in un oggetto long per separare i valori interi X e Y. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se questo `Aspose.Imaging.Point` è vuoto. |
| [getX()](#getX--) | Ottiene o imposta la coordinata x di questo `Aspose.Imaging.Point`. |
| [setX(int value)](#setX-int-) | Ottiene o imposta la coordinata x di questo `Aspose.Imaging.Point`. |
| [getY()](#getY--) | Ottiene o imposta la coordinata y di questo `Aspose.Imaging.Point`. |
| [setY(int value)](#setY-int-) | Ottiene o imposta la coordinata y di questo `Aspose.Imaging.Point`. |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | Trasla questo `Aspose.Imaging.Point` del `Aspose.Imaging.Point` specificato. |
| [offset(int dx, int dy)](#offset-int-int-) | Trasla questo `Aspose.Imaging.Point` della quantità specificata. |
| [equals(Object obj)](#equals-java.lang.Object-) | Specifica se questo `Aspose.Imaging.Point` contiene le stesse coordinate dell'`System.Object` specificato. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questo `Aspose.Imaging.Point`. |
| [toLong()](#toLong--) | Converte questo Point in un unico valore long, contenente le coordinate X e Y nei bit più alti e più bassi. |
| [toString()](#toString--) | Converte questo `Aspose.Imaging.Point` in una stringa leggibile dall'uomo. |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Inizializza una nuova istanza della struttura `Aspose.Imaging.Point` con le coordinate specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione orizzontale del punto. |
| y | int | La posizione verticale del punto. |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


Inizializza una nuova istanza della struttura `Aspose.Imaging.Point` dalla struttura `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Contiene le nuove coordinate del punto. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Inizializza una nuova istanza della struttura `Aspose.Imaging.Point` usando coordinate specificate da un valore intero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dw | int | Un intero a 32 bit che specifica le coordinate per il nuovo punto. |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Ottiene una nuova istanza della struttura `Aspose.Imaging.Point` con i valori `Aspose.Imaging.Point.X` e `Aspose.Imaging.Point.Y` impostati a zero.

**Returns:**
[Point](../../com.aspose.imaging/point)
### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


Aggiunge la `Aspose.Imaging.Size` specificata al `Aspose.Imaging.Point` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il `Aspose.Imaging.Point` a cui aggiungere. |
| size | [Size](../../com.aspose.imaging/size) | La `Aspose.Imaging.Size` da aggiungere al `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


Restituisce il risultato della sottrazione della `Aspose.Imaging.Size` specificata dal `Aspose.Imaging.Point` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il `Aspose.Imaging.Point` da cui sottrarre. |
| size | [Size](../../com.aspose.imaging/size) | Il `Aspose.Imaging.Size` da sottrarre dal `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


Converte il `Aspose.Imaging.PointF` specificato in un `Aspose.Imaging.Point` arrotondando i valori del `Aspose.Imaging.PointF` al prossimo intero superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `Aspose.Imaging.PointF` da convertire. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


Converte il `Aspose.Imaging.PointF` specificato in un oggetto `Aspose.Imaging.Point` arrotondando i valori del `Aspose.Imaging.Point` all'intero più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `Aspose.Imaging.PointF` da convertire. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


Converte il `Aspose.Imaging.PointF` specificato in un `Aspose.Imaging.Point` troncando i valori del `Aspose.Imaging.Point`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `Aspose.Imaging.PointF` da convertire. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Trasla un `Aspose.Imaging.Point` di una data `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il `Aspose.Imaging.Point` da traslare. |
| size | [Size](../../com.aspose.imaging/size) | Un `Aspose.Imaging.Size` che specifica la coppia di numeri da aggiungere alle coordinate di `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Trasla un `Aspose.Imaging.Point` del negativo di una data `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il `Aspose.Imaging.Point` da traslare. |
| size | [Size](../../com.aspose.imaging/size) | Un `Aspose.Imaging.Size` che specifica la coppia di numeri da sottrarre dalle coordinate di `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Confronta due oggetti `Aspose.Imaging.Point`. Il risultato specifica se i valori delle proprietà `Aspose.Imaging.Point.X` e `Aspose.Imaging.Point.Y` dei due oggetti `Aspose.Imaging.Point` sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Un primo `Aspose.Imaging.Point` da confrontare. |
| point2 | [Point](../../com.aspose.imaging/point) | Un secondo `Aspose.Imaging.Point` da confrontare. |

**Returns:**
boolean - True se i valori `Aspose.Imaging.Point.X` e `Aspose.Imaging.Point.Y` di `point1` e `point2` sono uguali; altrimenti, false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Confronta due oggetti `Aspose.Imaging.Point`. Il risultato specifica se i valori delle proprietà `Aspose.Imaging.Point.X` o `Aspose.Imaging.Point.Y` dei due oggetti `Aspose.Imaging.Point` sono diversi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Un primo `Aspose.Imaging.Point` da confrontare. |
| point2 | [Point](../../com.aspose.imaging/point) | Un secondo `Aspose.Imaging.Point` da confrontare. |

**Returns:**
boolean - True se i valori di una delle proprietà `Aspose.Imaging.Point.X` o `Aspose.Imaging.Point.Y` di `point1` e `point2` differiscono; altrimenti, false.
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


Converte la struttura `Aspose.Imaging.Point` specificata in una struttura `Aspose.Imaging.Size`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il `Aspose.Imaging.Point` da convertire. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


Converte la struttura `Point` specificata nella struttura `PointF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il `Point` da convertire. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


Decompone un oggetto Point inserito in un oggetto long per separare i valori interi X e Y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| packedPoint | long | L'oggetto Point impacchettato in un valore long. |
| x | int[] | Il valore X estratto dal Point impacchettato. |
| y | int[] | Il valore Y estratto dal Point impacchettato. |

### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ottiene un valore che indica se questo `Aspose.Imaging.Point` è vuoto.

**Returns:**
boolean - True se entrambi `Aspose.Imaging.Point.X` e `Aspose.Imaging.Point.Y` sono 0; altrimenti, false.
### getX() {#getX--}
```
public int getX()
```


Ottiene o imposta la coordinata x di questo `Aspose.Imaging.Point`.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Ottiene o imposta la coordinata x di questo `Aspose.Imaging.Point`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getY() {#getY--}
```
public int getY()
```


Ottiene o imposta la coordinata y di questo `Aspose.Imaging.Point`.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Ottiene o imposta la coordinata y di questo `Aspose.Imaging.Point`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


Trasla questo `Aspose.Imaging.Point` del `Aspose.Imaging.Point` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il `Aspose.Imaging.Point` usato per offsettare questo `Aspose.Imaging.Point`. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Trasla questo `Aspose.Imaging.Point` della quantità specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | int | La quantità per offsettare la coordinata x. |
| dy | int | La quantità per offsettare la coordinata y. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Specifica se questo `Aspose.Imaging.Point` contiene le stesse coordinate dell'`System.Object` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` da testare. |

**Returns:**
boolean - True se `obj` è un `Aspose.Imaging.Point` e ha le stesse coordinate di questo `Aspose.Imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questo `Aspose.Imaging.Point`.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### toLong() {#toLong--}
```
public final long toLong()
```


Converte questo Point in un unico valore long, contenente le coordinate X e Y nei bit più alti e più bassi.

**Returns:**
long - L'oggetto Point impacchettato in un valore long.
### toString() {#toString--}
```
public String toString()
```


Converte questo `Aspose.Imaging.Point` in una stringa leggibile dall'uomo.

**Returns:**
java.lang.String - Una `System.String` che rappresenta questa istanza.
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
