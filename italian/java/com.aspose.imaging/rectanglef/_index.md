---
title: "RectangleF"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Memorizza un insieme di quattro numeri in virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo."
type: docs
weight: 94
url: /it/java/com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Memorizza un insieme di quattro numeri in virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Inizializza una nuova istanza della struttura `com.aspose.imaging.RectangleF` con la posizione e le dimensioni specificate. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Inizializza una nuova istanza della struttura `com.aspose.imaging.RectangleF` con la posizione e le dimensioni specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della struttura `com.aspose.imaging.RectangleF` con i valori `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` e `com.aspose.imaging.RectangleF.Height` impostati a zero. |
| [getLocation()](#getLocation--) | Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`. |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`. |
| [getSize()](#getSize--) | Ottiene o imposta le dimensioni di questo `com.aspose.imaging.RectangleF`. |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | Ottiene o imposta le dimensioni di questo `com.aspose.imaging.RectangleF`. |
| [getX()](#getX--) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`. |
| [setX(float value)](#setX-float-) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`. |
| [getY()](#getY--) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`. |
| [setY(float value)](#setY-float-) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza di questa struttura `com.aspose.imaging.RectangleF`. |
| [setWidth(float value)](#setWidth-float-) | Ottiene o imposta la larghezza di questa struttura `com.aspose.imaging.RectangleF`. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza di questa struttura `com.aspose.imaging.RectangleF`. |
| [setHeight(float value)](#setHeight-float-) | Ottiene o imposta l'altezza di questa struttura `com.aspose.imaging.RectangleF`. |
| [getLeft()](#getLeft--) | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.RectangleF`. |
| [setLeft(float value)](#setLeft-float-) | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.RectangleF`. |
| [getTop()](#getTop--) | Ottiene o imposta la coordinata y del bordo superiore di questa struttura `com.aspose.imaging.RectangleF`. |
| [setTop(float value)](#setTop-float-) | Ottiene o imposta la coordinata y del bordo superiore di questa struttura `com.aspose.imaging.RectangleF`. |
| [getRight()](#getRight--) | Ottiene o imposta la coordinata x che è la somma di `com.aspose.imaging.RectangleF.X` e `com.aspose.imaging.RectangleF.Width` di questa struttura `com.aspose.imaging.RectangleF`. |
| [setRight(float value)](#setRight-float-) | Ottiene o imposta la coordinata x che è la somma di `com.aspose.imaging.RectangleF.X` e `com.aspose.imaging.RectangleF.Width` di questa struttura `com.aspose.imaging.RectangleF`. |
| [getBottom()](#getBottom--) | Ottiene o imposta la coordinata y che è la somma di `com.aspose.imaging.RectangleF.Y` e `com.aspose.imaging.RectangleF.Height` di questa struttura `com.aspose.imaging.RectangleF`. |
| [setBottom(float value)](#setBottom-float-) | Ottiene o imposta la coordinata y che è la somma di `com.aspose.imaging.RectangleF.Y` e `com.aspose.imaging.RectangleF.Height` di questa struttura `com.aspose.imaging.RectangleF`. |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se la proprietà `com.aspose.imaging.RectangleF.Width` o `com.aspose.imaging.RectangleF.Height` di questo `com.aspose.imaging.RectangleF` ha valore zero. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Crea un nuovo `Rectangle` a partire da due punti specificati. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | Crea e restituisce una copia ingrandita della struttura `com.aspose.imaging.RectangleF` specificata. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Restituisce una struttura `com.aspose.imaging.RectangleF` che rappresenta l'intersezione di due rettangoli. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Verifica se due strutture `com.aspose.imaging.RectangleF` hanno posizione e dimensioni uguali. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Verifica se due strutture `com.aspose.imaging.RectangleF` differiscono per posizione o dimensione. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | Implementa l'operatore \*. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | Implementa l'operatore /. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | Converte la struttura `com.aspose.imaging.Rectangle` specificata in una struttura `com.aspose.imaging.RectangleF`. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Crea una struttura `com.aspose.imaging.RectangleF` con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate. |
| [normalize()](#normalize--) | Normalizza il rettangolo rendendo la larghezza e l'altezza positive, il lato sinistro minore di quello destro e il lato superiore minore di quello inferiore. |
| [contains(float x, float y)](#contains-float-float-) | Determina se il punto specificato è contenuto all'interno di questa struttura `com.aspose.imaging.RectangleF`. |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | Determina se il punto specificato è contenuto all'interno di questa struttura `com.aspose.imaging.RectangleF`. |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questa struttura `com.aspose.imaging.RectangleF`. |
| [inflate(float x, float y)](#inflate-float-float-) | Ingrandisce questa struttura `com.aspose.imaging.RectangleF` della quantità specificata. |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | Ingrandisce questo `com.aspose.imaging.RectangleF` della quantità specificata. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Sostituisce questa struttura `com.aspose.imaging.RectangleF` con l'intersezione di essa stessa e della struttura `com.aspose.imaging.RectangleF` specificata. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | Determina se questo rettangolo interseca `rect`. |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | Regola la posizione di questo rettangolo della quantità specificata. |
| [offset(float x, float y)](#offset-float-float-) | Regola la posizione di questo rettangolo della quantità specificata. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se `obj` è un `com.aspose.imaging.RectangleF` con la stessa posizione e dimensione di questo `com.aspose.imaging.RectangleF`. |
| [hashCode()](#hashCode--) | Ottiene il codice hash per questa struttura `com.aspose.imaging.RectangleF`. |
| [toString()](#toString--) | Converte gli attributi di questo `com.aspose.imaging.RectangleF` in una stringa leggibile dall'uomo. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.imaging.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Inizializza una nuova istanza della struttura `com.aspose.imaging.RectangleF` con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| width | float | La larghezza del rettangolo. |
| height | float | L'altezza del rettangolo. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Inizializza una nuova istanza della struttura `com.aspose.imaging.RectangleF` con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` che rappresenta l'angolo superiore sinistro della regione rettangolare. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Un `com.aspose.imaging.SizeF` che rappresenta la larghezza e l'altezza della regione rettangolare. |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Ottiene una nuova istanza della struttura `com.aspose.imaging.RectangleF` con i valori `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` e `com.aspose.imaging.RectangleF.Height` impostati a zero.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


Ottiene o imposta le dimensioni di questo `com.aspose.imaging.RectangleF`.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


Ottiene o imposta le dimensioni di questo `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordinata x dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`.
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getY() {#getY--}
```
public float getY()
```


Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordinata y dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`.
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Ottiene o imposta la larghezza di questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La larghezza di questa struttura `com.aspose.imaging.RectangleF`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Ottiene o imposta la larghezza di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Ottiene o imposta l'altezza di questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
float - L'altezza di questa struttura `com.aspose.imaging.RectangleF`.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Ottiene o imposta l'altezza di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


Ottiene o imposta la coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.RectangleF`.
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Ottiene o imposta la coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


Ottiene o imposta la coordinata y del bordo superiore di questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordinata y del bordo superiore di questa struttura `com.aspose.imaging.RectangleF`.
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Ottiene o imposta la coordinata y del bordo superiore di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


Ottiene o imposta la coordinata x che è la somma di `com.aspose.imaging.RectangleF.X` e `com.aspose.imaging.RectangleF.Width` di questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordinata x che è la somma di `com.aspose.imaging.RectangleF.X` e `com.aspose.imaging.RectangleF.Width` di questa struttura `com.aspose.imaging.RectangleF`.
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Ottiene o imposta la coordinata x che è la somma di `com.aspose.imaging.RectangleF.X` e `com.aspose.imaging.RectangleF.Width` di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


Ottiene o imposta la coordinata y che è la somma di `com.aspose.imaging.RectangleF.Y` e `com.aspose.imaging.RectangleF.Height` di questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordinata y che è la somma di `com.aspose.imaging.RectangleF.Y` e `com.aspose.imaging.RectangleF.Height` di questa struttura `com.aspose.imaging.RectangleF`.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Ottiene o imposta la coordinata y che è la somma di `com.aspose.imaging.RectangleF.Y` e `com.aspose.imaging.RectangleF.Height` di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ottiene un valore che indica se la proprietà `com.aspose.imaging.RectangleF.Width` o `com.aspose.imaging.RectangleF.Height` di questo `com.aspose.imaging.RectangleF` ha valore zero.

**Returns:**
boolean - Questa proprietà restituisce true se la proprietà `com.aspose.imaging.RectangleF.Width` o `com.aspose.imaging.RectangleF.Height` di questo `com.aspose.imaging.RectangleF` ha valore zero; altrimenti, false.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Crea un nuovo `Rectangle` a partire da due punti specificati. I due vertici del `Rectangle` creato saranno uguali ai `point1` e `point2` passati. Questi sono tipicamente i vertici opposti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Il primo `Point` per il nuovo rettangolo. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Il secondo `Point` per il nuovo rettangolo. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Crea e restituisce una copia ingrandita della struttura `com.aspose.imaging.RectangleF` specificata. La copia è ingrandita dell'importo specificato. Il rettangolo originale rimane invariato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Il `com.aspose.imaging.RectangleF` da copiare. Questo rettangolo non viene modificato. |
| x | float | L'importo per ingrandire orizzontalmente la copia del rettangolo. |
| y | float | L'importo per ingrandire verticalmente la copia del rettangolo. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Restituisce una struttura `com.aspose.imaging.RectangleF` che rappresenta l'intersezione di due rettangoli. Se non c'è intersezione, viene restituito un `com.aspose.imaging.RectangleF` vuoto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Un primo rettangolo da intersecare. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Un secondo rettangolo da intersecare. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Un primo rettangolo da unire. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Un secondo rettangolo da unire. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Verifica se due strutture `com.aspose.imaging.RectangleF` hanno posizione e dimensioni uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` che si trova a sinistra dell'operatore di uguaglianza. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` che si trova a destra dell'operatore di uguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se le due strutture `com.aspose.imaging.RectangleF` specificate hanno le proprietà `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` e `com.aspose.imaging.RectangleF.Height` uguali.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Verifica se due strutture `com.aspose.imaging.RectangleF` differiscono per posizione o dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` che si trova a sinistra dell'operatore di disuguaglianza. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` che si trova a destra dell'operatore di disuguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se una qualsiasi delle proprietà `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` o `com.aspose.imaging.RectangleF.Height` delle due strutture `com.aspose.imaging.RectangleF` è diversa; altrimenti false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implementa l'operatore \*.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo. |
| moltiplicatore | float | Il moltiplicatore. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implementa l'operatore /.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo. |
| divisore | float | Il divisore. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Converte la struttura `com.aspose.imaging.Rectangle` specificata in una struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` da convertire. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Crea una struttura `com.aspose.imaging.RectangleF` con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | float | La coordinata x dell'angolo superiore sinistro della regione rettangolare. |
| alto | float | La coordinata y dell'angolo superiore sinistro della regione rettangolare. |
| destra | float | La coordinata x dell'angolo inferiore destro della regione rettangolare. |
| basso | float | La coordinata y dell'angolo inferiore destro della regione rettangolare. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


Normalizza il rettangolo rendendo la larghezza e l'altezza positive, il lato sinistro minore di quello destro e il lato superiore minore di quello inferiore.

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Determina se il punto specificato è contenuto all'interno di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto definito da `x` e `y` è contenuto all'interno di questa struttura `com.aspose.imaging.RectangleF`; altrimenti false.
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


Determina se il punto specificato è contenuto all'interno di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `com.aspose.imaging.PointF` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto rappresentato dal parametro `point` è contenuto all'interno di questa struttura `com.aspose.imaging.RectangleF`; altrimenti false.
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questa struttura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Il `com.aspose.imaging.RectangleF` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se la regione rettangolare rappresentata da `rect` è interamente contenuta nella regione rettangolare rappresentata da questa `com.aspose.imaging.RectangleF`; altrimenti false.
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Ingrandisce questa struttura `com.aspose.imaging.RectangleF` della quantità specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La quantità di espansione orizzontale di questa struttura `com.aspose.imaging.RectangleF`. |
| y | float | La quantità di espansione verticale di questa struttura `com.aspose.imaging.RectangleF`. |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


Ingrandisce questo `com.aspose.imaging.RectangleF` della quantità specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La quantità di espansione di questo rettangolo. |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Sostituisce questa struttura `com.aspose.imaging.RectangleF` con l'intersezione di essa stessa e della struttura `com.aspose.imaging.RectangleF` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo da intersecare. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Determina se questo rettangolo interseca `rect`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo da testare. |

**Returns:**
boolean - Questo metodo restituisce true se esiste una qualsiasi intersezione.
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


Regola la posizione di questo rettangolo della quantità specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | La quantità di spostamento della posizione. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Regola la posizione di questo rettangolo della quantità specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La quantità di spostamento orizzontale della posizione. |
| y | float | La quantità di spostamento verticale della posizione. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se `obj` è un `com.aspose.imaging.RectangleF` con la stessa posizione e dimensione di questo `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se `obj` è un `com.aspose.imaging.RectangleF` e le sue proprietà X, Y, Width e Height sono uguali alle corrispondenti proprietà di questo `com.aspose.imaging.RectangleF`; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottiene il codice hash per questa struttura `com.aspose.imaging.RectangleF`.

**Returns:**
int - Il codice hash per questo `com.aspose.imaging.RectangleF`.
### toString() {#toString--}
```
public String toString()
```


Converte gli attributi di questo `com.aspose.imaging.RectangleF` in una stringa leggibile dall'uomo.

**Returns:**
java.lang.String - Una stringa che contiene la posizione, la larghezza e l'altezza di questa struttura `com.aspose.imaging.RectangleF`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
