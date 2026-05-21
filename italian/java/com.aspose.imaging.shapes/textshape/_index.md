---
title: "TextShape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una forma di testo."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.shapes/textshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Rappresenta una forma di testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextShape()](#TextShape--) | Inizializza una nuova istanza della classe `TextShape`. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-) | Inizializza una nuova istanza della classe `TextShape`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) | Ottiene o imposta il testo disegnato. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo disegnato. |
| [getFont()](#getFont--) | Ottiene o imposta il carattere usato per disegnare il testo. |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | Ottiene o imposta il carattere usato per disegnare il testo. |
| [getTextFormat()](#getTextFormat--) | Ottiene o imposta il formato del testo. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.imaging.StringFormat-) | Ottiene o imposta il formato del testo. |
| [getCenter()](#getCenter--) | Ottiene il centro della forma. |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'oggetto. |
| [getSegments()](#getSegments--) | Ottiene i segmenti della forma. |
| [hasSegments()](#hasSegments--) | Ottiene un valore che indica se la forma ha segmenti. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ottiene i limiti dell'oggetto. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applica la trasformazione specificata alla forma. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
### TextShape() {#TextShape--}
```
public TextShape()
```


Inizializza una nuova istanza della classe `TextShape`.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Inizializza una nuova istanza della classe `TextShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Il testo da disegnare. |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo di testo. |
| font | [Font](../../com.aspose.imaging/font) | Il carattere da utilizzare. |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | Il formato della stringa. |

### getText() {#getText--}
```
public String getText()
```


Ottiene o imposta il testo disegnato.

Valore: Il testo disegnato.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ottiene o imposta il testo disegnato.

Valore: Il testo disegnato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Ottiene o imposta il carattere usato per disegnare il testo.

Valore: Il carattere usato per disegnare il testo.

**Returns:**
[Font](../../com.aspose.imaging/font)
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public void setFont(Font value)
```


Ottiene o imposta il carattere usato per disegnare il testo.

Valore: Il carattere usato per disegnare il testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) |  |

### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Ottiene o imposta il formato del testo.

Valore: Il formato del testo.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat)
### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.imaging.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Ottiene o imposta il formato del testo.

Valore: Il formato del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.imaging/stringformat) |  |

### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Ottiene il centro della forma.

Valore: Il centro della forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ottiene i limiti dell'oggetto.

Valore: I limiti dell'oggetto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Ottiene i segmenti della forma.

Valore: I segmenti della forma.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Ottiene un valore che indica se la forma ha segmenti.

Valore: `True` se la forma ha segmenti; altrimenti, `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna da usare per l'oggetto. Questo può influenzare le dimensioni dei limiti dell'oggetto. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applica la trasformazione specificata alla forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La trasformazione da applicare. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifica se gli oggetti sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object | L'altro oggetto. |

**Returns:**
boolean - Il risultato del confronto di uguaglianza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int - Il codice hash.
