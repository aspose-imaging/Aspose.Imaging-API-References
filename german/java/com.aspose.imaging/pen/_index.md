---
title: "Pen"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert ein Objekt, das zum Zeichnen von Linien, Kurven und Figuren verwendet wird."
type: docs
weight: 81
url: /de/java/com.aspose.imaging/pen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.TransparencySupporter](../../com.aspose.imaging/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Definiert ein Objekt, das zum Zeichnen von Linien, Kurven und Figuren verwendet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.imaging.Color-) | Initialisiert eine neue Instanz der `Pen`-Klasse mit der angegebenen Farbe. |
| [Pen(Color color, float width)](#Pen-com.aspose.imaging.Color-float-) | Initialisiert eine neue Instanz der `Pen`-Klasse mit den angegebenen Eigenschaften `Color` und `Pen.Width`. |
| [Pen(Brush brush)](#Pen-com.aspose.imaging.Brush-) | Initialisiert eine neue Instanz der `Pen`-Klasse mit dem angegebenen `Brush`. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.imaging.Brush-float-) | Initialisiert eine neue Instanz der `Pen`-Klasse mit dem angegebenen `Brush` und `Pen.Width`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Liefert die Breite dieses `Pen`, in Einheiten des zum Zeichnen verwendeten Graphics-Objekts. |
| [setWidth(float value)](#setWidth-float-) | Setzt die Breite dieses `Pen`, in Einheiten des zum Zeichnen verwendeten Graphics-Objekts. |
| [getStartCap()](#getStartCap--) | Liefert den Cap-Stil, der am Anfang von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [setStartCap(int value)](#setStartCap-int-) | Setzt den Cap-Stil, der am Anfang von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [getEndCap()](#getEndCap--) | Liefert den Cap-Stil, der am Ende von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [setEndCap(int value)](#setEndCap-int-) | Setzt den Cap-Stil, der am Ende von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [getDashCap()](#getDashCap--) | Liefert den Cap-Stil, der am Ende der Striche verwendet wird, aus denen mit diesem `Pen` gezeichnete Strichlinien bestehen. |
| [setDashCap(int value)](#setDashCap-int-) | Setzt den Cap-Stil, der am Ende der Striche verwendet wird, aus denen mit diesem `Pen` gezeichnete Strichlinien bestehen. |
| [getLineJoin()](#getLineJoin--) | Liefert den Join-Stil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem `Pen` gezeichnet wurden. |
| [setLineJoin(int value)](#setLineJoin-int-) | Setzt den Join-Stil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem `Pen` gezeichnet wurden. |
| [getCustomStartCap()](#getCustomStartCap--) | Liefert einen benutzerdefinierten Cap, der am Anfang von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.imaging.CustomLineCap-) | Setzt einen benutzerdefinierten Cap, der am Anfang von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [getCustomEndCap()](#getCustomEndCap--) | Liefert einen benutzerdefinierten Cap, der am Ende von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.imaging.CustomLineCap-) | Setzt einen benutzerdefinierten Cap, der am Ende von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [getMiterLimit()](#getMiterLimit--) | Liefert die Grenze der Dicke der Verbindung an einer Gehrungsecke. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Legt die Begrenzung der Dicke der Verbindung an einer Gehrungsecke fest. |
| [getAlignment()](#getAlignment--) | Ermittelt die Ausrichtung für diesen `Pen`. |
| [setAlignment(int value)](#setAlignment-int-) | Legt die Ausrichtung für diesen `Pen` fest. |
| [getTransform()](#getTransform--) | Ermittelt eine Kopie der geometrischen Transformation für diesen `Pen`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Legt eine Kopie der geometrischen Transformation für diesen `Pen` fest. |
| [getPenType()](#getPenType--) | Ermittelt den Stil der mit diesem `Pen` gezeichneten Linien. |
| [getColor()](#getColor--) | Ermittelt die Farbe dieses `Pen`. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Legt die Farbe dieses `Pen` fest. |
| [getBrush()](#getBrush--) | Ermittelt den `Brush`, der die Attribute dieses `Pen` bestimmt. |
| [setBrush(Brush value)](#setBrush-com.aspose.imaging.Brush-) | Legt den `Brush` fest, der die Attribute dieses `Pen` bestimmt. |
| [getDashStyle()](#getDashStyle--) | Ermittelt den Stil, der für mit diesem `Pen` gezeichnete Strichlinien verwendet wird. |
| [setDashStyle(int value)](#setDashStyle-int-) | Legt den Stil fest, der für mit diesem `Pen` gezeichnete Strichlinien verwendet wird. |
| [getDashOffset()](#getDashOffset--) | Ermittelt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters. |
| [setDashOffset(float value)](#setDashOffset-float-) | Legt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters fest. |
| [getDashPattern()](#getDashPattern--) | Ermittelt ein Array benutzerdefinierter Striche und Lücken. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Legt ein Array benutzerdefinierter Striche und Lücken fest. |
| [getCompoundArray()](#getCompoundArray--) | Ermittelt ein Array von Werten, das einen Compound-Pen spezifiziert. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Legt ein Array von Werten fest, das einen Compound-Pen spezifiziert. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Legt die Werte fest, die den Stil der Endkappe bestimmen, die zum Abschluss von Linien verwendet wird, die von diesem `Pen` gezeichnet werden. |
| [resetTransform()](#resetTransform--) | Setzt die geometrische Transformationsmatrix für diesen `Pen` auf die Identität zurück. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multipliziert die Transformationsmatrix für diesen `Pen` mit der angegebenen `Matrix`. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multipliziert die Transformationsmatrix für diesen `Pen` mit der angegebenen `Matrix` in der angegebenen Reihenfolge. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Abmessungen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Abmessungen in der angegebenen Reihenfolge. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Dreht die lokale geometrische Transformation um den angegebenen Winkel. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) |  |

## Example: This example shows the creation and usage Pen objects.
Dieses Beispiel zeigt die Erstellung und Verwendung von Pen-Objekten. Das Beispiel erstellt ein neues Image und zeichnet Rechtecke auf der Image-Oberfläche.
``` java

// Erstellen Sie eine Instanz von BmpOptions und setzen Sie deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von BmpOptions zu
// Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei IsTemporal ist oder nicht
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Erstelle eine Instanz von Image am angegebenen Pfad
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Erstelle eine Instanz von Graphics und initialisiere sie mit dem Image-Objekt
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Leere die Graphics-Oberfläche mit weißer Farbe
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Erstelle eine Instanz von Pen mit der Farbe Rot und einer Breite von 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Erstelle eine Instanz von HatchBrush und setze deren Eigenschaften
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Erstelle eine Instanz von Pen und initialisiere sie mit dem HatchBrush-Objekt und einer Breite
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Zeichne Rechtecke, indem du das Pen-Objekt angibst
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Zeichne Rechtecke, indem du das Pen-Objekt angibst
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Speichere alle Änderungen.
    image.save();
} finally {
    image.dispose();
}
```

### Pen(Color color) {#Pen-com.aspose.imaging.Color-}
```
public Pen(Color color)
```


Initialisiert eine neue Instanz der `Pen`-Klasse mit der angegebenen Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Eine `Color`-Struktur, die die Farbe dieses `Pen` angibt. |

### Pen(Color color, float width) {#Pen-com.aspose.imaging.Color-float-}
```
public Pen(Color color, float width)
```


Initialisiert eine neue Instanz der `Pen`-Klasse mit den angegebenen Eigenschaften `Color` und `Pen.Width`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Eine `Color`-Struktur, die die Farbe dieses `Pen` angibt. |
| Breite | float | Ein Wert, der die Breite dieses `Pen` angibt. |

### Pen(Brush brush) {#Pen-com.aspose.imaging.Brush-}
```
public Pen(Brush brush)
```


Initialisiert eine neue Instanz der `Pen`-Klasse mit dem angegebenen `Brush`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Ein `Brush`, der die Fülleigenschaften dieses `Pen` bestimmt. |

### Pen(Brush brush, float width) {#Pen-com.aspose.imaging.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initialisiert eine neue Instanz der `Pen`-Klasse mit dem angegebenen `Brush` und `Pen.Width`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Ein `Brush`, der die Merkmale dieses `Pen` bestimmt. |
| Breite | float | Die Breite des neuen `Pen`. |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Liefert die Breite dieses `Pen`, in Einheiten des zum Zeichnen verwendeten Graphics-Objekts.

**Returns:**
float - Die Breite dieses `Pen`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Setzt die Breite dieses `Pen`, in Einheiten des zum Zeichnen verwendeten Graphics-Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Die Breite dieses `Pen`. |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Liefert den Cap-Stil, der am Anfang von mit diesem `Pen` gezeichneten Linien verwendet wird.

**Returns:**
int - Einer der `LineCap`-Werte, der den Kap-Stil am Anfang von Linien darstellt, die mit diesem `Pen` gezeichnet werden.
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Setzt den Cap-Stil, der am Anfang von mit diesem `Pen` gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Einer der `LineCap`-Werte, der den Kap-Stil am Anfang von Linien darstellt, die mit diesem `Pen` gezeichnet werden. |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Liefert den Cap-Stil, der am Ende von mit diesem `Pen` gezeichneten Linien verwendet wird.

**Returns:**
int - Einer der `LineCap`-Werte, der den Kap-Stil am Ende von Linien darstellt, die mit diesem `Pen` gezeichnet werden.
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Setzt den Cap-Stil, der am Ende von mit diesem `Pen` gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Einer der `LineCap`-Werte, der den Kap-Stil am Ende von Linien darstellt, die mit diesem `Pen` gezeichnet werden. |

### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Liefert den Cap-Stil, der am Ende der Striche verwendet wird, aus denen mit diesem `Pen` gezeichnete Strichlinien bestehen.

**Returns:**
int - Einer der `DashCap`-Werte, der den Kap-Stil am Anfang und Ende der Striche darstellt, aus denen gestrichelte Linien, die mit diesem `Pen` gezeichnet werden, bestehen.
### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Setzt den Cap-Stil, der am Ende der Striche verwendet wird, aus denen mit diesem `Pen` gezeichnete Strichlinien bestehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Einer der `DashCap`-Werte, der den Kap-Stil am Anfang und Ende der Striche darstellt, aus denen gestrichelte Linien, die mit diesem `Pen` gezeichnet werden, bestehen. |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Liefert den Join-Stil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem `Pen` gezeichnet wurden.

**Returns:**
int - Ein `LineJoin`, der den Verbindungsstil für die Enden von zwei aufeinanderfolgenden Linien darstellt, die mit diesem `Pen` gezeichnet werden.
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Setzt den Join-Stil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem `Pen` gezeichnet wurden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Ein `LineJoin`, das den Verbindungsstil für die Enden von zwei aufeinanderfolgenden Linien darstellt, die mit diesem `Pen` gezeichnet werden. |

### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Liefert einen benutzerdefinierten Cap, der am Anfang von mit diesem `Pen` gezeichneten Linien verwendet wird.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the beginning of lines drawn with this `Pen`.
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Setzt einen benutzerdefinierten Cap, der am Anfang von mit diesem `Pen` gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Ein `CustomLineCap`, das die am Anfang von Linien verwendete Kappe darstellt, die mit diesem `Pen` gezeichnet werden. |

### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Liefert einen benutzerdefinierten Cap, der am Ende von mit diesem `Pen` gezeichneten Linien verwendet wird.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the end of lines drawn with this `Pen`.
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Setzt einen benutzerdefinierten Cap, der am Ende von mit diesem `Pen` gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Ein `CustomLineCap`, das die am Ende von Linien verwendete Kappe darstellt, die mit diesem `Pen` gezeichnet werden. |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Liefert die Grenze der Dicke der Verbindung an einer Gehrungsecke.

**Returns:**
float - Die Grenze der Dicke der Verbindung an einer Gehrungsecke.
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Legt die Begrenzung der Dicke der Verbindung an einer Gehrungsecke fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Die Grenze der Dicke der Verbindung an einer Gehrungsecke. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Ermittelt die Ausrichtung für diesen `Pen`.

**Returns:**
int - Ein `PenAlignment`, das die Ausrichtung für diesen `Pen` darstellt.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Legt die Ausrichtung für diesen `Pen` fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Ein `PenAlignment`, das die Ausrichtung für diesen `Pen` darstellt. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Ermittelt eine Kopie der geometrischen Transformation für diesen `Pen`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Matrix` that represents the geometric transformation for this `Pen`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Legt eine Kopie der geometrischen Transformation für diesen `Pen` fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | Eine Kopie der `Matrix`, die die geometrische Transformation für diesen `Pen` darstellt. |

### getPenType() {#getPenType--}
```
public int getPenType()
```


Ermittelt den Stil der mit diesem `Pen` gezeichneten Linien.

**Returns:**
int - Eine `PenType`-Aufzählung, die den Stil der mit diesem `Pen` gezeichneten Linien angibt.
### getColor() {#getColor--}
```
public Color getColor()
```


Ermittelt die Farbe dieses `Pen`.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `Color` structure that represents the color of this `Pen`.
### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Legt die Farbe dieses `Pen` fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Eine `Color`-Struktur, die die Farbe dieses `Pen` darstellt. |

### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Ermittelt den `Brush`, der die Attribute dieses `Pen` bestimmt.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A `Brush` that determines attributes of this `Pen`.
### setBrush(Brush value) {#setBrush-com.aspose.imaging.Brush-}
```
public void setBrush(Brush value)
```


Legt den `Brush` fest, der die Attribute dieses `Pen` bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Brush](../../com.aspose.imaging/brush) | Ein `Brush`, der die Attribute dieses `Pen` bestimmt. |

### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Ermittelt den Stil, der für mit diesem `Pen` gezeichnete Strichlinien verwendet wird.

**Returns:**
int - Ein `DashStyle`, das den für gestrichelte Linien, die mit diesem `Pen` gezeichnet werden, verwendeten Stil darstellt.
### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Legt den Stil fest, der für mit diesem `Pen` gezeichnete Strichlinien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Ein `DashStyle`, das den für gestrichelte Linien, die mit diesem `Pen` gezeichnet werden, verwendeten Stil darstellt. |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Ermittelt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters.

**Returns:**
float - Der Abstand vom Anfang einer Linie bis zum Beginn eines Strichmusters.
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Legt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Abstand vom Anfang einer Linie bis zum Beginn eines Strichmusters. |

### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Ermittelt ein Array benutzerdefinierter Striche und Lücken.

**Returns:**
float[] - Ein Array aus reellen Zahlen, das die Längen von abwechselnden Strichen und Lücken in gestrichelten Linien angibt.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Legt ein Array benutzerdefinierter Striche und Lücken fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] | Ein Array aus reellen Zahlen, das die Längen von abwechselnden Strichen und Lücken in gestrichelten Linien angibt. |

### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Gibt ein Array von Werten zurück, das einen zusammengesetzten Stift angibt. Ein zusammengesetzter Stift zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Lücken besteht.

**Returns:**
float[] - Ein Array aus reellen Zahlen, das das zusammengesetzte Array angibt. Die Elemente im Array müssen in aufsteigender Reihenfolge sein, nicht kleiner als 0 und nicht größer als 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Legt ein Array von Werten fest, das einen zusammengesetzten Stift angibt. Ein zusammengesetzter Stift zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Lücken besteht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] | Ein Array aus reellen Zahlen, das das zusammengesetzte Array angibt. Die Elemente im Array müssen in aufsteigender Reihenfolge sein, nicht kleiner als 0 und nicht größer als 1. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Legt die Werte fest, die den Stil der Endkappe bestimmen, die zum Abschluss von Linien verwendet wird, die von diesem `Pen` gezeichnet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCap | int | Ein `LineCap`, das den zu Beginn von Linien, die mit diesem `Pen` gezeichnet werden, zu verwendenden Kappenstil darstellt. |
| endCap | int | Ein `LineCap`, das den am Ende von Linien, die mit diesem `Pen` gezeichnet werden, zu verwendenden Kappenstil darstellt. |
| dashCap | int | Ein `LineCap`, das den zu Beginn oder am Ende von gestrichelten Linien, die mit diesem `Pen` gezeichnet werden, zu verwendenden Kappenstil darstellt. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Setzt die geometrische Transformationsmatrix für diesen `Pen` auf die Identität zurück.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multipliziert die Transformationsmatrix für diesen `Pen` mit der angegebenen `Matrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Das `Matrix`-Objekt, mit dem die Transformationsmatrix multipliziert wird. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multipliziert die Transformationsmatrix für diesen `Pen` mit der angegebenen `Matrix` in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die `Matrix`, mit der die Transformationsmatrix multipliziert wird. |
| order | int | Die Reihenfolge, in der die Multiplikationsoperation ausgeführt wird. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Translation in x. |
| dy | float | Der Wert der Translation in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Verschiebt die lokale geometrische Transformation um die angegebenen Abmessungen in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Translation in x. |
| dy | float | Der Wert der Translation in y. |
| order | int | Die Reihenfolge (voranstellen oder anhängen), in der die Translation angewendet wird. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. Diese Methode fügt die Skalierungsmatrix der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Faktor, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Faktor, um den die Transformation in y‑Richtung skaliert wird. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Faktor, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Faktor, um den die Transformation in y‑Richtung skaliert wird. |
| order | int | Ein `MatrixOrder`, das angibt, ob die Skalierungsmatrix angehängt oder vorangestellt wird. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rotiert die lokale geometrische Transformation um den angegebenen Winkel. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel. |
| order | int | Ein `MatrixOrder`, das angibt, ob die Rotationsmatrix angehängt oder vorangestellt wird. |

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
int
