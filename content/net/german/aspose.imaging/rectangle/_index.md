---
title: Rectangle
second_title: Aspose.Imaging für .NET-API-Referenz
description: Speichert einen Satz von vier Ganzzahlen die die Position und Größe eines Rechtecks darstellen.
type: docs
weight: 10830
url: /de/aspose.imaging/rectangle/
---
## Rectangle structure

Speichert einen Satz von vier Ganzzahlen, die die Position und Größe eines Rechtecks darstellen.

```csharp
public struct Rectangle
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Initialisiert eine neue Instanz von[`Rectangle`](../rectangle) Struktur mit der angegebenen Position und Größe. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Initialisiert eine neue Instanz von[`Rectangle`](../rectangle) Struktur mit der angegebenen Position und Größe. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | Ruft eine neue Instanz von ab[`Rectangle`](../rectangle) Struktur, die hat[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) und[`Height`](./height) Werte auf Null gesetzt. |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | Holt oder setzt die y-Koordinate, die die Summe von ist[`Y`](./y) und[`Height`](./height) Eigenschaftswerte davon[`Rectangle`](../rectangle) Struktur. |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | Holt oder setzt die Höhe davon[`Rectangle`](../rectangle) Struktur. |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | Ruft einen Wert ab, der angibt, ob alle numerischen Eigenschaften von this[`Rectangle`](../rectangle) Werte von Null haben. |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | Holt oder setzt die x-Koordinate der linken Kante davon[`Rectangle`](../rectangle) Struktur. |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | Holt oder setzt die Koordinaten der oberen linken Ecke davon[`Rectangle`](../rectangle) Struktur. |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | Holt oder setzt die x-Koordinate, die die Summe von ist[`X`](./x) und[`Width`](./width) Eigenschaftswerte davon[`Rectangle`](../rectangle) Struktur. |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | Holt oder setzt die Größe davon[`Rectangle`](../rectangle) . |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | Holt oder setzt die y-Koordinate der Oberkante davon[`Rectangle`](../rectangle) Struktur. |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | Holt oder setzt die Breite davon[`Rectangle`](../rectangle) Struktur. |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | Liest oder setzt die x-Koordinate der oberen linken Ecke davon[`Rectangle`](../rectangle) Struktur. |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | Holt oder setzt die y-Koordinate der oberen linken Ecke davon[`Rectangle`](../rectangle) Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | Konvertiert die angegebene[`RectangleF`](../rectanglef) Struktur zu a[`Rectangle`](../rectangle) Struktur durch Rundung der[`RectangleF`](../rectanglef) Werte auf die nächsthöheren ganzzahligen Werte. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | Erstellt ein[`Rectangle`](../rectangle) Struktur mit den angegebenen Kantenpositionen. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | Erstellt eine neue[`Rectangle`](../rectangle) von zwei angegebenen Punkten. Zwei Vertikalen des Geschaffenen[`Rectangle`](../rectangle) wird gleich der bestandenen sein*point1* und*point2* . Dies wären typischerweise die gegenüberliegenden Scheitelpunkte. |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | Erstellt und gibt eine vergrößerte Kopie der angegebenen zurück[`Rectangle`](../rectangle) Struktur. Die Kopie wird um den angegebenen Betrag aufgeblasen. Das Original[`Rectangle`](../rectangle) Struktur bleibt unverändert. |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | Gibt ein Drittel zurück[`Rectangle`](../rectangle) Struktur, die die Schnittmenge von zwei anderen darstellt[`Rectangle`](../rectangle) Strukturen. Wenn es keine Schnittmenge gibt, ein Leerzeichen[`Rectangle`](../rectangle) wird zurückgegeben. |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | Konvertiert die angegebene[`RectangleF`](../rectanglef) zu einem[`Rectangle`](../rectangle) durch Runden der[`RectangleF`](../rectanglef)Werte auf die nächsten ganzzahligen Werte. |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | Konvertiert die angegebene[`RectangleF`](../rectanglef) zu einem[`Rectangle`](../rectangle) durch Abschneiden der[`RectangleF`](../rectanglef) Werte. |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | erhält a[`Rectangle`](../rectangle) Struktur, die die Vereinigung von zwei enthält[`Rectangle`](../rectangle) Strukturen. |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | Bestimmt, ob der angegebene Punkt darin enthalten ist[`Rectangle`](../rectangle) Struktur. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | Bestimmt, ob der rechteckige Bereich dargestellt wird durch*rect* ist ganz darin enthalten[`Rectangle`](../rectangle) Struktur. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | Bestimmt, ob der angegebene Punkt darin enthalten ist[`Rectangle`](../rectangle) Struktur. |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | Testet ob*obj* ist ein[`Rectangle`](../rectangle)Struktur mit der gleichen Lage und Größe von diesem[`Rectangle`](../rectangle) Struktur. |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | Gibt den Hash-Code dafür zurück[`Rectangle`](../rectangle) Struktur. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | bläst dies auf[`Rectangle`](../rectangle) um den angegebenen Betrag. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | bläst dies auf[`Rectangle`](../rectangle) um den angegebenen Betrag. |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | Ersetzt dies[`Rectangle`](../rectangle) mit dem Schnittpunkt von sich selbst und dem angegebenen[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | Bestimmt, ob sich dieses Rechteck mit schneidet*rect* . |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | Normalisiert das Rechteck, indem Breite und Höhe positiv werden, links kleiner als rechts und oben kleiner als unten. |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | Wandelt die Attribute davon um[`Rectangle`](../rectangle) in eine für Menschen lesbare Zeichenfolge. |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | Testet ob zwei[`Rectangle`](../rectangle)Strukturen haben dieselbe Position und Größe. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | Testet ob zwei[`Rectangle`](../rectangle) Strukturen unterscheiden sich in Lage oder Größe. |

### Siehe auch

* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
