---
title: RectangleF
second_title: Aspose.Imaging für .NET-API-Referenz
description: Speichert einen Satz von vier Fließkommazahlen die die Position und Größe eines Rechtecks darstellen.
type: docs
weight: 10840
url: /de/net/aspose.imaging/rectanglef/
---
## RectangleF structure

Speichert einen Satz von vier Fließkommazahlen, die die Position und Größe eines Rechtecks darstellen.

```csharp
public struct RectangleF
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | Initialisiert eine neue Instanz von[`RectangleF`](../rectanglef) Struktur mit der angegebenen Position und Größe. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | Initialisiert eine neue Instanz von[`RectangleF`](../rectanglef) Struktur mit der angegebenen Position und Größe. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | Ruft eine neue Instanz von ab[`RectangleF`](../rectanglef) Struktur, die hat[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) und[`Height`](./height) Werte auf Null gesetzt. |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | Holt oder setzt die y-Koordinate, die die Summe von ist[`Y`](./y) und[`Height`](./height) von diesem[`RectangleF`](../rectanglef) Struktur. |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | Holt oder setzt die Höhe davon[`RectangleF`](../rectanglef) Struktur. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | Ruft einen Wert ab, der angibt, ob die[`Width`](./width) oder[`Height`](./height) Eigentum davon[`RectangleF`](../rectanglef) hat den Wert null. |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | Holt oder setzt die x-Koordinate der linken Kante davon[`RectangleF`](../rectanglef) Struktur. |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | Holt oder setzt die Koordinaten der oberen linken Ecke davon[`RectangleF`](../rectanglef) Struktur. |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | Holt oder setzt die x-Koordinate, die die Summe von ist[`X`](./x) und[`Width`](./width) von diesem[`RectangleF`](../rectanglef) Struktur. |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | Holt oder setzt die Größe davon[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | Holt oder setzt die y-Koordinate der Oberkante davon[`RectangleF`](../rectanglef) Struktur. |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | Holt oder setzt die Breite davon[`RectangleF`](../rectanglef) Struktur. |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | Liest oder setzt die x-Koordinate der oberen linken Ecke davon[`RectangleF`](../rectanglef) Struktur. |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | Holt oder setzt die y-Koordinate der oberen linken Ecke davon[`RectangleF`](../rectanglef) Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Erstellt ein[`RectangleF`](../rectanglef) Struktur mit oberer linker Ecke und unterer rechter Ecke an den angegebenen Positionen. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | Erstellt eine neue[`Rectangle`](../rectangle) von zwei angegebenen Punkten. Zwei Scheitelpunkte des Geschaffenen[`Rectangle`](../rectangle) wird gleich der bestandenen sein*point1* und*point2* . Dies wären typischerweise die gegenüberliegenden Scheitelpunkte. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | Erstellt und gibt eine vergrößerte Kopie der angegebenen zurück[`RectangleF`](../rectanglef)Struktur. Die Kopie wird um den angegebenen Betrag aufgeblasen. Das ursprüngliche Rechteck bleibt unverändert. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | Gibt a zurück[`RectangleF`](../rectanglef) Struktur, die den Schnittpunkt zweier Rechtecke darstellt. Wenn es keine Kreuzung gibt, und leer[`RectangleF`](../rectanglef) wird zurückgegeben. |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | Erstellt das kleinstmögliche dritte Rechteck, das beide von zwei Rechtecken enthalten kann, die eine Vereinigung bilden. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains)(PointF) | Bestimmt, ob der angegebene Punkt darin enthalten ist[`RectangleF`](../rectanglef) Struktur. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_1)(RectangleF) | Bestimmt, ob der rechteckige Bereich dargestellt wird durch*rect* ist ganz darin enthalten[`RectangleF`](../rectanglef) Struktur. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_2)(float, float) | Bestimmt, ob der angegebene Punkt darin enthalten ist[`RectangleF`](../rectanglef) Struktur. |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | Testet ob*obj* ist ein[`RectangleF`](../rectanglef) mit der gleichen Lage und Größe von diesem[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | Ruft den Hash-Code dafür ab[`RectangleF`](../rectanglef) Struktur. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate)(SizeF) | bläst dies auf[`RectangleF`](../rectanglef) um den angegebenen Betrag. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate_1)(float, float) | bläst dies auf[`RectangleF`](../rectanglef) Struktur um den angegebenen Betrag. |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | Ersetzt dies[`RectangleF`](../rectanglef)Struktur mit der Schnittmenge von sich selbst und der angegebenen[`RectangleF`](../rectanglef) Struktur. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | Bestimmt, ob sich dieses Rechteck mit schneidet*rect* . |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | Normalisiert das Rechteck, indem Breite und Höhe positiv werden, links kleiner als rechts und oben kleiner als unten. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset)(PointF) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset_1)(float, float) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | Wandelt die Attribute davon um[`RectangleF`](../rectanglef) in eine für Menschen lesbare Zeichenfolge. |
| [operator /](../../aspose.imaging/rectanglef/op_division) | Implementiert den Operator /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | Testet ob zwei[`RectangleF`](../rectanglef)Strukturen haben dieselbe Position und Größe. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | Konvertiert die angegebene[`Rectangle`](../rectangle) Struktur zu a[`RectangleF`](../rectanglef) Struktur. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | Testet ob zwei[`RectangleF`](../rectanglef) Strukturen unterscheiden sich in Lage oder Größe. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | Implementiert den Operator *. |

### Siehe auch

* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
