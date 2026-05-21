---
title: "Rettangolo"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo."
type: docs
weight: 93
url: /it/java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Inizializza una nuova istanza della struttura `com.aspose.imaging.Rectangle` con la posizione e le dimensioni specificate. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Inizializza una nuova istanza della struttura `com.aspose.imaging.Rectangle` con la posizione e le dimensioni specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della struttura `com.aspose.imaging.Rectangle` che ha i valori `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` e `com.aspose.imaging.Rectangle.Height` impostati a zero. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Crea un nuovo `Rectangle` a partire da due punti specificati. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | Converte la struttura `com.aspose.imaging.RectangleF` specificata in una struttura `com.aspose.imaging.Rectangle` arrotondando i valori di `com.aspose.imaging.RectangleF` al successivo valore intero più alto. |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | Converte il `com.aspose.imaging.RectangleF` specificato in un `com.aspose.imaging.Rectangle` troncando i valori di `com.aspose.imaging.RectangleF`. |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | Converte il `com.aspose.imaging.RectangleF` specificato in un `com.aspose.imaging.Rectangle` arrotondando i valori del `com.aspose.imaging.RectangleF` al valore intero più vicino. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | Crea e restituisce una copia gonfiata della struttura `com.aspose.imaging.Rectangle` specificata. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Restituisce una terza struttura `com.aspose.imaging.Rectangle` che rappresenta l'intersezione di due altre strutture `com.aspose.imaging.Rectangle`. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Ottiene una struttura `com.aspose.imaging.Rectangle` che contiene l'unione di due strutture `com.aspose.imaging.Rectangle`. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Verifica se due strutture `com.aspose.imaging.Rectangle` hanno la stessa posizione e dimensione. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Verifica se due strutture `com.aspose.imaging.Rectangle` differiscono per posizione o dimensione. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Crea una struttura `com.aspose.imaging.Rectangle` con le posizioni dei bordi specificate. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`. |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`. |
| [getSize()](#getSize--) | Ottiene o imposta la dimensione di questo `com.aspose.imaging.Rectangle`. |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | Ottiene o imposta la dimensione di questo `com.aspose.imaging.Rectangle`. |
| [getX()](#getX--) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`. |
| [setX(int value)](#setX-int-) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`. |
| [getY()](#getY--) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`. |
| [setY(int value)](#setY-int-) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`. |
| [getWidth()](#getWidth--) | Ottiene la larghezza di questa struttura `com.aspose.imaging.Rectangle`. |
| [setWidth(int value)](#setWidth-int-) | Imposta la larghezza di questa struttura `com.aspose.imaging.Rectangle`. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza di questa struttura `com.aspose.imaging.Rectangle`. |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta l'altezza di questa struttura `com.aspose.imaging.Rectangle`. |
| [getLeft()](#getLeft--) | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.Rectangle`. |
| [setLeft(int value)](#setLeft-int-) | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.Rectangle`. |
| [getTop()](#getTop--) | Ottiene o imposta la coordinata y del bordo superiore di questa struttura `com.aspose.imaging.Rectangle`. |
| [setTop(int value)](#setTop-int-) | Ottiene o imposta la coordinata y del bordo superiore di questa struttura `com.aspose.imaging.Rectangle`. |
| [getRight()](#getRight--) | Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà `com.aspose.imaging.Rectangle.X` e `com.aspose.imaging.Rectangle.Width` di questa struttura `com.aspose.imaging.Rectangle`. |
| [setRight(int value)](#setRight-int-) | Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà `com.aspose.imaging.Rectangle.X` e `com.aspose.imaging.Rectangle.Width` di questa struttura `com.aspose.imaging.Rectangle`. |
| [getBottom()](#getBottom--) | Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà `com.aspose.imaging.Rectangle.Y` e `com.aspose.imaging.Rectangle.Height` di questa struttura `com.aspose.imaging.Rectangle`. |
| [setBottom(int value)](#setBottom-int-) | Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà `com.aspose.imaging.Rectangle.Y` e `com.aspose.imaging.Rectangle.Height` di questa struttura `com.aspose.imaging.Rectangle`. |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se tutte le proprietà numeriche di questo `com.aspose.imaging.Rectangle` hanno valore zero. |
| [contains(int x, int y)](#contains-int-int-) | Determina se il punto specificato è contenuto all'interno di questa struttura `com.aspose.imaging.Rectangle`. |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | Determina se il punto specificato è contenuto all'interno di questa struttura `com.aspose.imaging.Rectangle`. |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questa struttura `com.aspose.imaging.Rectangle`. |
| [inflate(int width, int height)](#inflate-int-int-) | Ingrandisce questo `com.aspose.imaging.Rectangle` dell'importo specificato. |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | Ingrandisce questo `com.aspose.imaging.Rectangle` dell'importo specificato. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Sostituisce questo `com.aspose.imaging.Rectangle` con l'intersezione di sé stesso e del `com.aspose.imaging.Rectangle` specificato. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | Determina se questo rettangolo interseca `rect`. |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | Regola la posizione di questo rettangolo della quantità specificata. |
| [offset(int x, int y)](#offset-int-int-) | Regola la posizione di questo rettangolo della quantità specificata. |
| [normalize()](#normalize--) | Normalizza il rettangolo rendendo la sua larghezza e altezza positive, il lato sinistro minore del destro e il lato superiore minore del lato inferiore. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se `obj` è una struttura `com.aspose.imaging.Rectangle` con la stessa posizione e dimensione di questa struttura `com.aspose.imaging.Rectangle`. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa struttura `com.aspose.imaging.Rectangle`. |
| [toString()](#toString--) | Converte gli attributi di questa `com.aspose.imaging.Rectangle` in una stringa leggibile dall'uomo. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.imaging.Rectangle-) |  |
| [Clone()](#Clone--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Inizializza una nuova istanza della struttura `com.aspose.imaging.Rectangle` con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| width | int | La larghezza del rettangolo. |
| height | int | L'altezza del rettangolo. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


Inizializza una nuova istanza della struttura `com.aspose.imaging.Rectangle` con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` che rappresenta l'angolo in alto a sinistra della regione rettangolare. |
| size | [Size](../../com.aspose.imaging/size) | Una `com.aspose.imaging.Size` che rappresenta la larghezza e l'altezza della regione rettangolare. |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Ottiene una nuova istanza della struttura `com.aspose.imaging.Rectangle` che ha i valori `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` e `com.aspose.imaging.Rectangle.Height` impostati a zero.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Crea un nuovo `Rectangle` a partire da due punti specificati. I due lati verticali del `Rectangle` creato saranno uguali ai punti `point1` e `point2` passati. Questi sono tipicamente i vertici opposti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Il primo `Point` per il nuovo rettangolo. |
| point2 | [Point](../../com.aspose.imaging/point) | Il secondo `Point` per il nuovo rettangolo. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Converte la struttura `com.aspose.imaging.RectangleF` specificata in una struttura `com.aspose.imaging.Rectangle` arrotondando i valori di `com.aspose.imaging.RectangleF` al successivo valore intero più alto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` da convertire. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Converte il `com.aspose.imaging.RectangleF` specificato in un `com.aspose.imaging.Rectangle` troncando i valori di `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Il `com.aspose.imaging.RectangleF` da convertire. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Converte il `com.aspose.imaging.RectangleF` specificato in un `com.aspose.imaging.Rectangle` arrotondando i valori del `com.aspose.imaging.RectangleF` al valore intero più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Il `com.aspose.imaging.RectangleF` da convertire. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Crea e restituisce una copia ingrandita della struttura `com.aspose.imaging.Rectangle` specificata. La copia è ingrandita dell'importo specificato. La struttura originale `com.aspose.imaging.Rectangle` rimane invariata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Il `com.aspose.imaging.Rectangle` con cui iniziare. Questo rettangolo non viene modificato. |
| x | int | L'importo con cui ingrandire orizzontalmente questo `com.aspose.imaging.Rectangle`. |
| y | int | L'importo con cui ingrandire verticalmente questo `com.aspose.imaging.Rectangle`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Restituisce una terza struttura `com.aspose.imaging.Rectangle` che rappresenta l'intersezione di due altre strutture `com.aspose.imaging.Rectangle`. Se non c'è intersezione, viene restituita una `com.aspose.imaging.Rectangle` vuota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Un primo rettangolo da intersecare. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Un secondo rettangolo da intersecare. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Ottiene una struttura `com.aspose.imaging.Rectangle` che contiene l'unione di due strutture `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Un primo rettangolo da unire. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Un secondo rettangolo da unire. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Verifica se due strutture `com.aspose.imaging.Rectangle` hanno la stessa posizione e dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` che si trova a sinistra dell'operatore di uguaglianza. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` che si trova a destra dell'operatore di uguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se le due strutture `com.aspose.imaging.Rectangle` hanno proprietà `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` e `com.aspose.imaging.Rectangle.Height` uguali.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Verifica se due strutture `com.aspose.imaging.Rectangle` differiscono per posizione o dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` che si trova a sinistra dell'operatore di disuguaglianza. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` che si trova a destra dell'operatore di disuguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se una qualsiasi delle proprietà `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` o `com.aspose.imaging.Rectangle.Height` delle due strutture `com.aspose.imaging.Rectangle` è diversa; altrimenti false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Crea una struttura `com.aspose.imaging.Rectangle` con le posizioni dei bordi specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | int | La coordinata x dell'angolo in alto a sinistra di questa struttura `com.aspose.imaging.Rectangle`. |
| alto | int | La coordinata y dell'angolo in alto a sinistra di questa struttura `com.aspose.imaging.Rectangle`. |
| destra | int | La coordinata x dell'angolo in basso a destra di questa struttura `com.aspose.imaging.Rectangle`. |
| basso | int | La coordinata y dell'angolo in basso a destra di questa struttura `com.aspose.imaging.Rectangle`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | Un `Point` che rappresenta l'angolo in alto a sinistra di questa struttura `com.aspose.imaging.Rectangle`. |

### getSize() {#getSize--}
```
public Size getSize()
```


Ottiene o imposta la dimensione di questo `com.aspose.imaging.Rectangle`.

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


Ottiene o imposta la dimensione di questo `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | Una `com.aspose.imaging.Size` che rappresenta la larghezza e l'altezza di questa struttura `com.aspose.imaging.Rectangle`. |

### getX() {#getX--}
```
public int getX()
```


Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordinata x dell'angolo in alto a sinistra di questa struttura `com.aspose.imaging.Rectangle`.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata x dell'angolo in alto a sinistra di questa struttura `com.aspose.imaging.Rectangle`. |

### getY() {#getY--}
```
public int getY()
```


Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordinata y dell'angolo in alto a sinistra di questa struttura `com.aspose.imaging.Rectangle`.
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata y dell'angolo in alto a sinistra di questa struttura `com.aspose.imaging.Rectangle`. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene la larghezza di questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La larghezza di questa struttura `com.aspose.imaging.Rectangle`.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Imposta la larghezza di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La larghezza di questa struttura `com.aspose.imaging.Rectangle`. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene o imposta l'altezza di questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
int - L'altezza di questa struttura `com.aspose.imaging.Rectangle`.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ottiene o imposta l'altezza di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'altezza di questa struttura `com.aspose.imaging.Rectangle`. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Ottiene o imposta la coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.Rectangle`.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Ottiene o imposta la coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata x del bordo sinistro di questa struttura `com.aspose.imaging.Rectangle`. |

### getTop() {#getTop--}
```
public int getTop()
```


Ottiene o imposta la coordinata y del bordo superiore di questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordinata y del bordo superiore di questa struttura `com.aspose.imaging.Rectangle`.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Ottiene o imposta la coordinata y del bordo superiore di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata y del bordo superiore di questa struttura `com.aspose.imaging.Rectangle`. |

### getRight() {#getRight--}
```
public int getRight()
```


Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà `com.aspose.imaging.Rectangle.X` e `com.aspose.imaging.Rectangle.Width` di questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordinata x che è la somma di `com.aspose.imaging.Rectangle.X` e `com.aspose.imaging.Rectangle.Width` di questa `com.aspose.imaging.Rectangle`.
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà `com.aspose.imaging.Rectangle.X` e `com.aspose.imaging.Rectangle.Width` di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata x che è la somma di `com.aspose.imaging.Rectangle.X` e `com.aspose.imaging.Rectangle.Width` di questa `com.aspose.imaging.Rectangle`. |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà `com.aspose.imaging.Rectangle.Y` e `com.aspose.imaging.Rectangle.Height` di questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordinata y che è la somma di `com.aspose.imaging.Rectangle.Y` e `com.aspose.imaging.Rectangle.Height` di questa `com.aspose.imaging.Rectangle`.
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà `com.aspose.imaging.Rectangle.Y` e `com.aspose.imaging.Rectangle.Height` di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata y che è la somma di `com.aspose.imaging.Rectangle.Y` e `com.aspose.imaging.Rectangle.Height` di questa `com.aspose.imaging.Rectangle`. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ottiene un valore che indica se tutte le proprietà numeriche di questo `com.aspose.imaging.Rectangle` hanno valore zero.

**Returns:**
boolean - Questa proprietà restituisce true se le proprietà `com.aspose.imaging.Rectangle.Width`, `com.aspose.imaging.Rectangle.Height`, `com.aspose.imaging.Rectangle.X` e `com.aspose.imaging.Rectangle.Y` di questa `com.aspose.imaging.Rectangle` hanno tutti valore zero; altrimenti, false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determina se il punto specificato è contenuto all'interno di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto definito da `x` e `y` è contenuto all'interno di questa struttura `com.aspose.imaging.Rectangle`; altrimenti false.
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


Determina se il punto specificato è contenuto all'interno di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il `com.aspose.imaging.Point` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto rappresentato da `point` è contenuto all'interno di questa struttura `com.aspose.imaging.Rectangle`; altrimenti false.
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Il `com.aspose.imaging.Rectangle` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questa struttura `com.aspose.imaging.Rectangle`; altrimenti false.
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Ingrandisce questo `com.aspose.imaging.Rectangle` dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | L'importo con cui ingrandire orizzontalmente questo `com.aspose.imaging.Rectangle`. |
| height | int | L'importo con cui ingrandire verticalmente questo `com.aspose.imaging.Rectangle`. |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


Ingrandisce questo `com.aspose.imaging.Rectangle` dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | La quantità di espansione di questo rettangolo. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Sostituisce questo `com.aspose.imaging.Rectangle` con l'intersezione di sé stesso e del `com.aspose.imaging.Rectangle` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Il `com.aspose.imaging.Rectangle` con cui intersecare. |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Determina se questo rettangolo interseca `rect`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da testare. |

**Returns:**
boolean - Questo metodo restituisce true se esiste qualche intersezione, altrimenti false.
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


Regola la posizione di questo rettangolo della quantità specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | Quantità per spostare la posizione. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Regola la posizione di questo rettangolo della quantità specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | Lo spostamento orizzontale. |
| y | int | Lo spostamento verticale. |

### normalize() {#normalize--}
```
public void normalize()
```


Normalizza il rettangolo rendendo la sua larghezza e altezza positive, il lato sinistro minore del destro e il lato superiore minore del lato inferiore.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se `obj` è una struttura `com.aspose.imaging.Rectangle` con la stessa posizione e dimensione di questa struttura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se `obj` è una struttura `com.aspose.imaging.Rectangle` e le sue proprietà `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` e `com.aspose.imaging.Rectangle.Height` sono uguali alle corrispondenti proprietà di questa struttura `com.aspose.imaging.Rectangle`; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa struttura `com.aspose.imaging.Rectangle`.

**Returns:**
int - Un intero che rappresenta il codice hash per questo rettangolo.
### toString() {#toString--}
```
public String toString()
```


Converte gli attributi di questa `com.aspose.imaging.Rectangle` in una stringa leggibile dall'uomo.

**Returns:**
java.lang.String - Una stringa che contiene la posizione, la larghezza e l'altezza di questa struttura `com.aspose.imaging.Rectangle`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
