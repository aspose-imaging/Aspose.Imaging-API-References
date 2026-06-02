---
title: "Region"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Descrive l'interno di una forma grafica composta da rettangoli e percorsi."
type: docs
weight: 95
url: /it/java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

Descrive l'interno di una forma grafica composta da rettangoli e percorsi. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Region()](#Region--) | Inizializza una nuova Region. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | Inizializza una nuova `T:Aspose.Imaging.Region` dalla struttura `T:Aspose.Imaging.RectangleF` specificata. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | Inizializza una nuova `T:Aspose.Imaging.Region` dalla struttura `T:Aspose.Imaging.Rectangle` specificata. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | Inizializza una nuova `T:Aspose.Imaging.Region` con il `T:Aspose.Imaging.GraphicsPath` specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda esatta di questo `com.aspose.imaging.region`. |
| [makeInfinite()](#makeInfinite--) | Inizializza questo oggetto `com.aspose.imaging.Region` a un interno infinito. |
| [makeEmpty()](#makeEmpty--) | Inizializza questo `com.aspose.imaging.Region` a un interno vuoto. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Aggiorna questo `com.aspose.imaging.Region` all'intersezione di se stesso con la struttura `com.aspose.imaging.RectangleF` specificata. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Aggiorna questo `com.aspose.imaging.Region` all'intersezione di se stesso con la struttura `com.aspose.imaging.Rectangle` specificata. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | Aggiorna questo `com.aspose.imaging.Region` all'intersezione di se stesso con il `com.aspose.imaging.graphicsPath` specificato. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | Aggiorna questo `com.aspose.imaging.Region` all'intersezione di se stesso con il `com.aspose.imaging.region` specificato. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | Aggiorna questo `com.aspose.imaging.Region` all'unione di se stesso con la struttura `com.aspose.imaging.RectangleF` specificata. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | Aggiorna questo `com.aspose.imaging.Region` all'unione di se stesso con la struttura `com.aspose.imaging.Rectangle` specificata. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | Aggiorna questo `com.aspose.imaging.Region` all'unione di se stesso con il `com.aspose.imaging.graphicsPath` specificato. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | Aggiorna questo `com.aspose.imaging.Region` all'unione di se stesso con il `com.aspose.imaging.region` specificato. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | Aggiorna questo `com.aspose.imaging.Region` all'unione meno l'intersezione di se stesso con la struttura `com.aspose.imaging.RectangleF` specificata. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | Aggiorna questo `com.aspose.imaging.Region` all'unione meno l'intersezione di se stesso con la struttura `com.aspose.imaging.Rectangle` specificata. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | Aggiorna questo `com.aspose.imaging.Region` all'unione meno l'intersezione di se stesso con il `com.aspose.imaging.graphicsPath` specificato. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | Aggiorna questo `com.aspose.imaging.Region` all'unione meno l'intersezione di se stesso con il `com.aspose.imaging.region` specificato. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | Aggiorna questo `com.aspose.imaging.Region` per contenere solo la parte del suo interno che non interseca la struttura `com.aspose.imaging.RectangleF` specificata. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | Aggiorna questo `com.aspose.imaging.Region` per contenere solo la parte del suo interno che non interseca la struttura `com.aspose.imaging.Rectangle` specificata. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | Aggiorna questo `com.aspose.imaging.Region` per contenere solo la parte del suo interno che non interseca il `com.aspose.imaging.graphicsPath` specificato. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | Aggiorna questo `com.aspose.imaging.Region` per contenere solo la parte del suo interno che non interseca il `com.aspose.imaging.region` specificato. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | Aggiorna questo `com.aspose.imaging.Region` per contenere la parte della struttura `com.aspose.imaging.RectangleF` specificata che non interseca questo `com.aspose.imaging.region`. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | Aggiorna questo `com.aspose.imaging.Region` per contenere la parte della struttura `com.aspose.imaging.Rectangle` specificata che non interseca questo `com.aspose.imaging.region`. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | Aggiorna questo `com.aspose.imaging.Region` per contenere la parte del `com.aspose.imaging.GraphicsPath` specificato che non interseca questo `com.aspose.imaging.region`. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | Aggiorna questo `com.aspose.imaging.Region` per contenere la parte del `com.aspose.imaging.Region` specificato che non interseca questo `com.aspose.imaging.region`. |
| [translate(float dx, float dy)](#translate-float-float-) | Sposta le coordinate di questo `com.aspose.imaging.Region` dell'importo specificato. |
| [translate(int dx, int dy)](#translate-int-int-) | Sposta le coordinate di questo `com.aspose.imaging.Region` dell'importo specificato. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | Trasforma questo `com.aspose.imaging.Region` con la `com.aspose.imaging.matrix` specificata. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | Verifica se questo `com.aspose.imaging.Region` ha un interno vuoto sulla superficie di disegno specificata. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | Verifica se questo `com.aspose.imaging.Region` ha un interno infinito sulla superficie di disegno specificata. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | Verifica se il `com.aspose.imaging.Region` specificato è identico a questo `com.aspose.imaging.Region` sulla superficie di disegno specificata. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Verifica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.region`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Verifica se la struttura `com.aspose.imaging.PointF` specificata è contenuta all'interno di questo `com.aspose.imaging.region`. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Verifica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.Region` quando viene disegnato con il `com.aspose.imaging.graphics` specificato. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Verifica se la struttura `com.aspose.imaging.PointF` specificata è contenuta all'interno di questo `com.aspose.imaging.Region` quando viene disegnata con il `com.aspose.imaging.graphics` specificato. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Verifica se qualche parte del rettangolo specificato è contenuta all'interno di questo `com.aspose.imaging.region`. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | Verifica se qualche parte della struttura `com.aspose.imaging.RectangleF` specificata è contenuta all'interno di questo `com.aspose.imaging.region`. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | Verifica se qualche parte del rettangolo specificato è contenuta all'interno di questo `com.aspose.imaging.Region` quando viene disegnato con il `com.aspose.imaging.graphics` specificato. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | Verifica se qualche parte della struttura `com.aspose.imaging.RectangleF` specificata è contenuta all'interno di questo `com.aspose.imaging.Region` quando viene disegnata con il `com.aspose.imaging.graphics` specificato. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Verifica se il punto specificato è contenuto all'interno di questo oggetto `com.aspose.imaging.Region` quando viene disegnato con l'oggetto `com.aspose.imaging.Graphics` specificato. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Verifica se la struttura `com.aspose.imaging.Point` specificata è contenuta in questo `com.aspose.imaging.region`. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Verifica se la struttura `com.aspose.imaging.Point` specificata è contenuta in questo `com.aspose.imaging.Region` quando viene disegnata usando il `com.aspose.imaging.graphics` specificato. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Verifica se qualche parte del rettangolo specificato è contenuta all'interno di questo `com.aspose.imaging.region`. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | Verifica se qualche parte della struttura `com.aspose.imaging.Rectangle` specificata è contenuta in questo `com.aspose.imaging.region`. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | Verifica se qualche parte del rettangolo specificato è contenuta all'interno di questo `com.aspose.imaging.Region` quando viene disegnato con il `com.aspose.imaging.graphics` specificato. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | Verifica se qualche parte della struttura `com.aspose.imaging.Rectangle` specificata è contenuta in questo `com.aspose.imaging.Region` quando viene disegnata usando il `com.aspose.imaging.graphics` specificato. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
### Region() {#Region--}
```
public Region()
```


Inizializza una nuova Region.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


Inizializza una nuova `T:Aspose.Imaging.Region` dalla struttura `T:Aspose.Imaging.RectangleF` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Una struttura `T:Aspose.Imaging.RectangleF` che definisce l'interno del nuovo `T:Aspose.Imaging.Region`. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


Inizializza una nuova `T:Aspose.Imaging.Region` dalla struttura `T:Aspose.Imaging.Rectangle` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Una struttura `T:Aspose.Imaging.Rectangle` che definisce l'interno del nuovo `T:Aspose.Imaging.Region`. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Inizializza una nuova `T:Aspose.Imaging.Region` con il `T:Aspose.Imaging.GraphicsPath` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un `T:Aspose.Imaging.GraphicsPath` che definisce il nuovo `T:Aspose.Imaging.Region`. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Crea una copia profonda esatta di questo `com.aspose.imaging.region`.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Inizializza questo oggetto `com.aspose.imaging.Region` a un interno infinito.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Inizializza questo `com.aspose.imaging.Region` a un interno vuoto.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Aggiorna questo `com.aspose.imaging.Region` all'intersezione di se stesso con la struttura `com.aspose.imaging.RectangleF` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` da intersecare con questo `com.aspose.imaging.region`. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Aggiorna questo `com.aspose.imaging.Region` all'intersezione di se stesso con la struttura `com.aspose.imaging.Rectangle` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` da intersecare con questo `com.aspose.imaging.region`. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Aggiorna questo `com.aspose.imaging.Region` all'intersezione di se stesso con il `com.aspose.imaging.graphicsPath` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il `com.aspose.imaging.GraphicsPath` da intersecare con questo `com.aspose.imaging.region`. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


Aggiorna questo `com.aspose.imaging.Region` all'intersezione di se stesso con il `com.aspose.imaging.region` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Il `com.aspose.imaging.Region` da intersecare con questo `com.aspose.imaging.region`. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


Aggiorna questo `com.aspose.imaging.Region` all'unione di se stesso con la struttura `com.aspose.imaging.RectangleF` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` da unire a questo `com.aspose.imaging.region`. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


Aggiorna questo `com.aspose.imaging.Region` all'unione di se stesso con la struttura `com.aspose.imaging.Rectangle` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` da unire a questo `com.aspose.imaging.region`. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Aggiorna questo `com.aspose.imaging.Region` all'unione di se stesso con il `com.aspose.imaging.graphicsPath` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il `com.aspose.imaging.GraphicsPath` da unire a questo `com.aspose.imaging.region`. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


Aggiorna questo `com.aspose.imaging.Region` all'unione di se stesso con il `com.aspose.imaging.region` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Il `com.aspose.imaging.Region` da unire a questo `com.aspose.imaging.region`. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


Aggiorna questo `com.aspose.imaging.Region` all'unione meno l'intersezione di se stesso con la struttura `com.aspose.imaging.RectangleF` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` da xor con questo `com.aspose.imaging.region`. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


Aggiorna questo `com.aspose.imaging.Region` all'unione meno l'intersezione di se stesso con la struttura `com.aspose.imaging.Rectangle` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` da xor con questo `com.aspose.imaging.region`. |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Aggiorna questo `com.aspose.imaging.Region` all'unione meno l'intersezione di se stesso con il `com.aspose.imaging.graphicsPath` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il `com.aspose.imaging.GraphicsPath` da xor con questo `com.aspose.imaging.region`. |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


Aggiorna questo `com.aspose.imaging.Region` all'unione meno l'intersezione di se stesso con il `com.aspose.imaging.region` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Il `com.aspose.imaging.Region` da xor con questo `com.aspose.imaging.region`. |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


Aggiorna questo `com.aspose.imaging.Region` per contenere solo la parte del suo interno che non interseca la struttura `com.aspose.imaging.RectangleF` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` da escludere da questo `com.aspose.imaging.region`. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


Aggiorna questo `com.aspose.imaging.Region` per contenere solo la parte del suo interno che non interseca la struttura `com.aspose.imaging.Rectangle` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` da escludere da questo `com.aspose.imaging.region`. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Aggiorna questo `com.aspose.imaging.Region` per contenere solo la parte del suo interno che non interseca il `com.aspose.imaging.graphicsPath` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il `com.aspose.imaging.GraphicsPath` da escludere da questo `com.aspose.imaging.region`. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


Aggiorna questo `com.aspose.imaging.Region` per contenere solo la parte del suo interno che non interseca il `com.aspose.imaging.region` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Il `com.aspose.imaging.Region` da escludere da questo `com.aspose.imaging.region`. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


Aggiorna questo `com.aspose.imaging.Region` per contenere la parte della struttura `com.aspose.imaging.RectangleF` specificata che non interseca questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` da complementare a questo `com.aspose.imaging.region`. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


Aggiorna questo `com.aspose.imaging.Region` per contenere la parte della struttura `com.aspose.imaging.Rectangle` specificata che non interseca questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` da complementare a questo `com.aspose.imaging.region`. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Aggiorna questo `com.aspose.imaging.Region` per contenere la parte del `com.aspose.imaging.GraphicsPath` specificato che non interseca questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il `com.aspose.imaging.GraphicsPath` per completare questo `com.aspose.imaging.region`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


Aggiorna questo `com.aspose.imaging.Region` per contenere la parte del `com.aspose.imaging.Region` specificato che non interseca questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | L'oggetto `com.aspose.imaging.Region` per completare questo oggetto `com.aspose.imaging.Region`. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Sposta le coordinate di questo `com.aspose.imaging.Region` dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | La quantità per spostare orizzontalmente questo `com.aspose.imaging.Region`. |
| dy | float | La quantità per spostare verticalmente questo `com.aspose.imaging.Region`. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Sposta le coordinate di questo `com.aspose.imaging.Region` dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | int | La quantità per spostare orizzontalmente questo `com.aspose.imaging.Region`. |
| dy | int | La quantità per spostare verticalmente questo `com.aspose.imaging.Region`. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


Trasforma questo `com.aspose.imaging.Region` con la `com.aspose.imaging.matrix` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La `com.aspose.imaging.Matrix` con cui trasformare questo `com.aspose.imaging.region`. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Verifica se questo `com.aspose.imaging.Region` ha un interno vuoto sulla superficie di disegno specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta una superficie di disegno. |

**Returns:**
boolean - true se l'interno di questo `com.aspose.imaging.Region` è vuoto quando viene applicata la trasformazione associata a `g`; altrimenti, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Verifica se questo `com.aspose.imaging.Region` ha un interno infinito sulla superficie di disegno specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta una superficie di disegno. |

**Returns:**
boolean - true se l'interno di questo `com.aspose.imaging.Region` è infinito quando viene applicata la trasformazione associata a `g`; altrimenti, false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Verifica se il `com.aspose.imaging.Region` specificato è identico a questo `com.aspose.imaging.Region` sulla superficie di disegno specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Il `com.aspose.imaging.Region` da testare. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta una superficie di disegno. |

**Returns:**
boolean - True se l'interno della regione è identico all'interno di questa regione quando viene applicata la trasformazione associata al parametro `g`; altrimenti, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Verifica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns:**
boolean - True quando il punto specificato è contenuto all'interno di questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Verifica se la struttura `com.aspose.imaging.PointF` specificata è contenuta all'interno di questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | La struttura `com.aspose.imaging.PointF` da testare. |

**Returns:**
boolean - true quando `point` è contenuto all'interno di questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Verifica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.Region` quando viene disegnato con il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta un contesto grafico. |

**Returns:**
boolean - True quando il punto specificato è contenuto all'interno di questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Verifica se la struttura `com.aspose.imaging.PointF` specificata è contenuta all'interno di questo `com.aspose.imaging.Region` quando viene disegnata con il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | La struttura `com.aspose.imaging.PointF` da testare. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando `point` è contenuto all'interno di questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Verifica se qualche parte del rettangolo specificato è contenuta all'interno di questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| height | float | L'altezza del rettangolo da testare. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta in questo oggetto `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Verifica se qualche parte della struttura `com.aspose.imaging.RectangleF` specificata è contenuta all'interno di questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` da testare. |

**Returns:**
boolean - true quando qualsiasi parte di `rect` è contenuta in questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Verifica se qualche parte del rettangolo specificato è contenuta all'interno di questo `com.aspose.imaging.Region` quando viene disegnato con il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| height | float | L'altezza del rettangolo da testare. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta in questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Verifica se qualche parte della struttura `com.aspose.imaging.RectangleF` specificata è contenuta all'interno di questo `com.aspose.imaging.Region` quando viene disegnata con il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La struttura `com.aspose.imaging.RectangleF` da testare. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando `rect` è contenuto in questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Verifica se il punto specificato è contenuto all'interno di questo oggetto `com.aspose.imaging.Region` quando viene disegnato con l'oggetto `com.aspose.imaging.Graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta un contesto grafico. |

**Returns:**
boolean - vero quando il punto specificato è contenuto all'interno di questo `com.aspose.imaging.Region`; altrimenti, falso.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Verifica se la struttura `com.aspose.imaging.Point` specificata è contenuta in questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | La struttura `com.aspose.imaging.Point` da testare. |

**Returns:**
boolean - true quando `point` è contenuto all'interno di questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Verifica se la struttura `com.aspose.imaging.Point` specificata è contenuta in questo `com.aspose.imaging.Region` quando viene disegnata usando il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | La struttura `com.aspose.imaging.Point` da testare. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando `point` è contenuto all'interno di questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Verifica se qualche parte del rettangolo specificato è contenuta all'interno di questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| height | int | L'altezza del rettangolo da testare. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta in questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Verifica se qualche parte della struttura `com.aspose.imaging.Rectangle` specificata è contenuta in questo `com.aspose.imaging.region`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` da testare. |

**Returns:**
boolean - Questo metodo restituisce vero quando qualsiasi parte di `rect` è contenuta all'interno di questo `com.aspose.imaging.Region`; altrimenti, falso.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Verifica se qualche parte del rettangolo specificato è contenuta all'interno di questo `com.aspose.imaging.Region` quando viene disegnato con il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| height | int | L'altezza del rettangolo da testare. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta in questo `com.aspose.imaging.Region`; altrimenti, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Verifica se qualche parte della struttura `com.aspose.imaging.Rectangle` specificata è contenuta in questo `com.aspose.imaging.Region` quando viene disegnata usando il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La struttura `com.aspose.imaging.Rectangle` da testare. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` che rappresenta un contesto grafico. |

**Returns:**
boolean - vero quando qualsiasi parte di `rect` è contenuta all'interno di questo `com.aspose.imaging.Region`; altrimenti, falso.
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
