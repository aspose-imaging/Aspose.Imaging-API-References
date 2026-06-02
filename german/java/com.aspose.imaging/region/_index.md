---
title: "Region"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht."
type: docs
weight: 95
url: /de/java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht vererbt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Region()](#Region--) | Initialisiert eine neue Region. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | Initialisiert eine neue `T:Aspose.Imaging.Region` aus der angegebenen `T:Aspose.Imaging.RectangleF`-Struktur. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | Initialisiert eine neue `T:Aspose.Imaging.Region` aus der angegebenen `T:Aspose.Imaging.Rectangle`-Struktur. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | Initialisiert eine neue `T:Aspose.Imaging.Region` mit dem angegebenen `T:Aspose.Imaging.GraphicsPath`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine exakte Tiefenkopie dieses `com.aspose.imaging.region`. |
| [makeInfinite()](#makeInfinite--) | Initialisiert dieses `com.aspose.imaging.Region`-Objekt mit einem unendlichen Inneren. |
| [makeEmpty()](#makeEmpty--) | Initialisiert dieses `com.aspose.imaging.Region` mit einem leeren Inneren. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Schnittmenge mit der angegebenen `com.aspose.imaging.RectangleF`-Struktur. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Schnittmenge mit der angegebenen `com.aspose.imaging.Rectangle`-Struktur. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Schnittmenge mit dem angegebenen `com.aspose.imaging.graphicsPath`. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Schnittmenge mit dem angegebenen `com.aspose.imaging.region`. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung mit der angegebenen `com.aspose.imaging.RectangleF`-Struktur. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung mit der angegebenen `com.aspose.imaging.Rectangle`-Struktur. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung mit dem angegebenen `com.aspose.imaging.graphicsPath`. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung mit dem angegebenen `com.aspose.imaging.region`. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung minus der Schnittmenge mit der angegebenen `com.aspose.imaging.RectangleF`-Struktur. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen `com.aspose.imaging.Rectangle`-Struktur. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung abzüglich der Schnittmenge von sich selbst mit dem angegebenen `com.aspose.imaging.graphicsPath`. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung abzüglich der Schnittmenge von sich selbst mit dem angegebenen `com.aspose.imaging.region`. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | Aktualisiert dieses `com.aspose.imaging.Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen `com.aspose.imaging.RectangleF`-Struktur überschneidet. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | Aktualisiert dieses `com.aspose.imaging.Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen `com.aspose.imaging.Rectangle`-Struktur überschneidet. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | Aktualisiert dieses `com.aspose.imaging.Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen `com.aspose.imaging.graphicsPath` überschneidet. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | Aktualisiert dieses `com.aspose.imaging.Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen `com.aspose.imaging.region` überschneidet. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | Aktualisiert dieses `com.aspose.imaging.Region`, sodass es den Teil der angegebenen `com.aspose.imaging.RectangleF`-Struktur enthält, der nicht mit diesem `com.aspose.imaging.region` überschneidet. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | Aktualisiert dieses `com.aspose.imaging.Region`, sodass es den Teil der angegebenen `com.aspose.imaging.Rectangle`-Struktur enthält, der nicht mit diesem `com.aspose.imaging.region` überschneidet. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | Aktualisiert dieses `com.aspose.imaging.Region`, sodass es den Teil des angegebenen `com.aspose.imaging.GraphicsPath` enthält, der nicht mit diesem `com.aspose.imaging.region` überschneidet. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | Aktualisiert dieses `com.aspose.imaging.Region`, sodass es den Teil des angegebenen `com.aspose.imaging.Region` enthält, der nicht mit diesem `com.aspose.imaging.region` überschneidet. |
| [translate(float dx, float dy)](#translate-float-float-) | Verschiebt die Koordinaten dieses `com.aspose.imaging.Region` um den angegebenen Betrag. |
| [translate(int dx, int dy)](#translate-int-int-) | Verschiebt die Koordinaten dieses `com.aspose.imaging.Region` um den angegebenen Betrag. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | Transformiert dieses `com.aspose.imaging.Region` mit der angegebenen `com.aspose.imaging.matrix`. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | Prüft, ob dieses `com.aspose.imaging.Region` auf der angegebenen Zeichenfläche ein leeres Inneres hat. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | Prüft, ob dieses `com.aspose.imaging.Region` auf der angegebenen Zeichenfläche ein unendliches Inneres hat. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | Prüft, ob das angegebene `com.aspose.imaging.Region` auf der angegebenen Zeichenfläche mit diesem `com.aspose.imaging.Region` identisch ist. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Prüft, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.region` liegt. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Prüft, ob die angegebene `com.aspose.imaging.PointF`-Struktur innerhalb dieses `com.aspose.imaging.region` liegt. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Prüft, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.Region` liegt, wenn er mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Prüft, ob die angegebene `com.aspose.imaging.PointF`-Struktur innerhalb dieses `com.aspose.imaging.Region` liegt, wenn sie mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.region` liegt. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | Prüft, ob irgendein Teil der angegebenen `com.aspose.imaging.RectangleF`-Struktur innerhalb dieses `com.aspose.imaging.region` liegt. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.Region` liegt, wenn er mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | Prüft, ob irgendein Teil der angegebenen `com.aspose.imaging.RectangleF`-Struktur innerhalb dieses `com.aspose.imaging.Region` liegt, wenn sie mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Prüft, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.Region`-Objekts liegt, wenn er mit dem angegebenen `com.aspose.imaging.Graphics`-Objekt gezeichnet wird. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Prüft, ob die angegebene `com.aspose.imaging.Point` Struktur innerhalb dieses `com.aspose.imaging.region` enthalten ist. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Prüft, ob die angegebene `com.aspose.imaging.Point` Struktur innerhalb dieses `com.aspose.imaging.Region` enthalten ist, wenn sie mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.region` liegt. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | Prüft, ob irgendein Teil der angegebenen `com.aspose.imaging.Rectangle` Struktur in diesem `com.aspose.imaging.region` enthalten ist. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.Region` liegt, wenn er mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | Prüft, ob irgendein Teil der angegebenen `com.aspose.imaging.Rectangle` Struktur innerhalb dieses `com.aspose.imaging.Region` enthalten ist, wenn sie mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |
### Region() {#Region--}
```
public Region()
```


Initialisiert eine neue Region.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


Initialisiert eine neue `T:Aspose.Imaging.Region` aus der angegebenen `T:Aspose.Imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Eine `T:Aspose.Imaging.RectangleF` Struktur, die das Innere des neuen `T:Aspose.Imaging.Region` definiert. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


Initialisiert eine neue `T:Aspose.Imaging.Region` aus der angegebenen `T:Aspose.Imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Eine `T:Aspose.Imaging.Rectangle` Struktur, die das Innere des neuen `T:Aspose.Imaging.Region` definiert. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initialisiert eine neue `T:Aspose.Imaging.Region` mit dem angegebenen `T:Aspose.Imaging.GraphicsPath`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ein `T:Aspose.Imaging.GraphicsPath`, der das neue `T:Aspose.Imaging.Region` definiert. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Erstellt eine exakte Tiefenkopie dieses `com.aspose.imaging.region`.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initialisiert dieses `com.aspose.imaging.Region`-Objekt mit einem unendlichen Inneren.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initialisiert dieses `com.aspose.imaging.Region` mit einem leeren Inneren.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Schnittmenge mit der angegebenen `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF` Struktur, die mit diesem `com.aspose.imaging.region` geschnitten werden soll. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Schnittmenge mit der angegebenen `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle` Struktur, die mit diesem `com.aspose.imaging.region` geschnitten werden soll. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Schnittmenge mit dem angegebenen `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der `com.aspose.imaging.GraphicsPath`, der mit diesem `com.aspose.imaging.region` geschnitten werden soll. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Schnittmenge mit dem angegebenen `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Das `com.aspose.imaging.Region`, das mit diesem `com.aspose.imaging.region` geschnitten werden soll. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung mit der angegebenen `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF` Struktur, die mit diesem `com.aspose.imaging.region` vereinigt werden soll. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung mit der angegebenen `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle` Struktur, die mit diesem `com.aspose.imaging.region` vereinigt werden soll. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung mit dem angegebenen `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der `com.aspose.imaging.GraphicsPath`, der mit diesem `com.aspose.imaging.region` vereinigt werden soll. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung mit dem angegebenen `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Das `com.aspose.imaging.Region`, das mit diesem `com.aspose.imaging.region` vereinigt werden soll. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung minus der Schnittmenge mit der angegebenen `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF` Struktur, die mit diesem `com.aspose.imaging.region` exklusiv ODER verknüpft werden soll. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle` Struktur, die mit diesem `com.aspose.imaging.region` exklusiv ODER verknüpft werden soll. |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung abzüglich der Schnittmenge von sich selbst mit dem angegebenen `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der `com.aspose.imaging.GraphicsPath`, der mit diesem `com.aspose.imaging.region` exklusiv ODER verknüpft werden soll. |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


Aktualisiert dieses `com.aspose.imaging.Region` zur Vereinigung abzüglich der Schnittmenge von sich selbst mit dem angegebenen `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Das `com.aspose.imaging.Region`, das mit diesem `com.aspose.imaging.region` exklusiv ODER verknüpft werden soll. |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


Aktualisiert dieses `com.aspose.imaging.Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen `com.aspose.imaging.RectangleF`-Struktur überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF` Struktur, die von diesem `com.aspose.imaging.region` ausgeschlossen werden soll. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


Aktualisiert dieses `com.aspose.imaging.Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen `com.aspose.imaging.Rectangle`-Struktur überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle` Struktur, die von diesem `com.aspose.imaging.region` ausgeschlossen werden soll. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Aktualisiert dieses `com.aspose.imaging.Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen `com.aspose.imaging.graphicsPath` überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der `com.aspose.imaging.GraphicsPath`, der von diesem `com.aspose.imaging.region` ausgeschlossen werden soll. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


Aktualisiert dieses `com.aspose.imaging.Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen `com.aspose.imaging.region` überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Das `com.aspose.imaging.Region`, das von diesem `com.aspose.imaging.region` ausgeschlossen werden soll. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


Aktualisiert dieses `com.aspose.imaging.Region`, sodass es den Teil der angegebenen `com.aspose.imaging.RectangleF`-Struktur enthält, der nicht mit diesem `com.aspose.imaging.region` überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF` Struktur, die dieses `com.aspose.imaging.region` komplementiert. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


Aktualisiert dieses `com.aspose.imaging.Region`, sodass es den Teil der angegebenen `com.aspose.imaging.Rectangle`-Struktur enthält, der nicht mit diesem `com.aspose.imaging.region` überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle` Struktur, die dieses `com.aspose.imaging.region` komplementiert. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Aktualisiert dieses `com.aspose.imaging.Region`, sodass es den Teil des angegebenen `com.aspose.imaging.GraphicsPath` enthält, der nicht mit diesem `com.aspose.imaging.region` überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der `com.aspose.imaging.GraphicsPath` zur Ergänzung dieses `com.aspose.imaging.region`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


Aktualisiert dieses `com.aspose.imaging.Region`, sodass es den Teil des angegebenen `com.aspose.imaging.Region` enthält, der nicht mit diesem `com.aspose.imaging.region` überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Das `com.aspose.imaging.Region`-Objekt zur Ergänzung dieses `com.aspose.imaging.Region`-Objekts. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Verschiebt die Koordinaten dieses `com.aspose.imaging.Region` um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Betrag, um den dieses `com.aspose.imaging.Region` horizontal verschoben wird. |
| dy | float | Der Betrag, um den dieses `com.aspose.imaging.Region` vertikal verschoben wird. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Verschiebt die Koordinaten dieses `com.aspose.imaging.Region` um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | int | Der Betrag, um den dieses `com.aspose.imaging.Region` horizontal verschoben wird. |
| dy | int | Der Betrag, um den dieses `com.aspose.imaging.Region` vertikal verschoben wird. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


Transformiert dieses `com.aspose.imaging.Region` mit der angegebenen `com.aspose.imaging.matrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die `com.aspose.imaging.Matrix`, mit der dieses `com.aspose.imaging.region` transformiert wird. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Prüft, ob dieses `com.aspose.imaging.Region` auf der angegebenen Zeichenfläche ein leeres Inneres hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das eine Zeichenfläche darstellt. |

**Returns:**
boolean - true, wenn das Innere dieses `com.aspose.imaging.Region` leer ist, wenn die mit `g` verbundene Transformation angewendet wird; andernfalls false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Prüft, ob dieses `com.aspose.imaging.Region` auf der angegebenen Zeichenfläche ein unendliches Inneres hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das eine Zeichenfläche darstellt. |

**Returns:**
boolean - true, wenn das Innere dieses `com.aspose.imaging.Region` unendlich ist, wenn die mit `g` verbundene Transformation angewendet wird; andernfalls false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Prüft, ob das angegebene `com.aspose.imaging.Region` auf der angegebenen Zeichenfläche mit diesem `com.aspose.imaging.Region` identisch ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Das `com.aspose.imaging.Region` zum Testen. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das eine Zeichenfläche darstellt. |

**Returns:**
boolean - True, wenn das Innere der Region identisch mit dem Inneren dieses Regions ist, wenn die mit dem Parameter `g` verbundene Transformation angewendet wird; andernfalls false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Prüft, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.region` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolean - True, wenn der angegebene Punkt innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Prüft, ob die angegebene `com.aspose.imaging.PointF`-Struktur innerhalb dieses `com.aspose.imaging.region` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Die `com.aspose.imaging.PointF`-Struktur zum Testen. |

**Returns:**
boolean - true, wenn `point` innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Prüft, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.Region` liegt, wenn er mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - True, wenn der angegebene Punkt innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Prüft, ob die angegebene `com.aspose.imaging.PointF`-Struktur innerhalb dieses `com.aspose.imaging.Region` liegt, wenn sie mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Die `com.aspose.imaging.PointF`-Struktur zum Testen. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn `point` innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.region` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | float | Die Breite des zu testenden Rechtecks. |
| Höhe | float | Die Höhe des zu testenden Rechtecks. |

**Returns:**
boolean - true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.Region`-Objekts liegt; andernfalls false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Prüft, ob irgendein Teil der angegebenen `com.aspose.imaging.RectangleF`-Struktur innerhalb dieses `com.aspose.imaging.region` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF`-Struktur zum Testen. |

**Returns:**
boolean - true, wenn irgendein Teil von `rect` innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.Region` liegt, wenn er mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | float | Die Breite des zu testenden Rechtecks. |
| Höhe | float | Die Höhe des zu testenden Rechtecks. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Prüft, ob irgendein Teil der angegebenen `com.aspose.imaging.RectangleF`-Struktur innerhalb dieses `com.aspose.imaging.Region` liegt, wenn sie mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF`-Struktur zum Testen. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn `rect` innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Prüft, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.Region`-Objekts liegt, wenn er mit dem angegebenen `com.aspose.imaging.Graphics`-Objekt gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn der angegebene Punkt innerhalb dieser `com.aspose.imaging.Region` enthalten ist; andernfalls false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Prüft, ob die angegebene `com.aspose.imaging.Point` Struktur innerhalb dieses `com.aspose.imaging.region` enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Die `com.aspose.imaging.Point`-Struktur zum Testen. |

**Returns:**
boolean - true, wenn `point` innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Prüft, ob die angegebene `com.aspose.imaging.Point` Struktur innerhalb dieses `com.aspose.imaging.Region` enthalten ist, wenn sie mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Die `com.aspose.imaging.Point`-Struktur zum Testen. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn `point` innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.region` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | int | Die Breite des zu testenden Rechtecks. |
| Höhe | int | Die Höhe des zu testenden Rechtecks. |

**Returns:**
boolean - true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Prüft, ob irgendein Teil der angegebenen `com.aspose.imaging.Rectangle` Struktur in diesem `com.aspose.imaging.region` enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle`-Struktur zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn irgendein Teil von `rect` innerhalb dieser `com.aspose.imaging.Region` enthalten ist; andernfalls false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.Region` liegt, wenn er mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | int | Die Breite des zu testenden Rechtecks. |
| Höhe | int | Die Höhe des zu testenden Rechtecks. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses `com.aspose.imaging.Region` liegt; andernfalls false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Prüft, ob irgendein Teil der angegebenen `com.aspose.imaging.Rectangle` Struktur innerhalb dieses `com.aspose.imaging.Region` enthalten ist, wenn sie mit dem angegebenen `com.aspose.imaging.graphics` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle`-Struktur zum Testen. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ein `com.aspose.imaging.Graphics`, das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - true, wenn irgendein Teil des `rect` innerhalb dieser `com.aspose.imaging.Region` enthalten ist; andernfalls false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
