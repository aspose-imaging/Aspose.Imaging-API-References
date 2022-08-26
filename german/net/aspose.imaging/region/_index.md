---
title: Region
second_title: Aspose.Imaging für .NET-API-Referenz
description: Beschreibt das Innere einer Grafikform die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 10850
url: /de/net/aspose.imaging/region/
---
## Region class

Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class Region
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Region](region#constructor)() | Initialisiert eine neue[`Region`](../region) . |
| [Region](region#constructor_1)(GraphicsPath) | Initialisiert eine neue[`Region`](../region) mit den angegebenen[`GraphicsPath`](../graphicspath) . |
| [Region](region#constructor_2)(Rectangle) | Initialisiert eine neue[`Region`](../region) aus dem angegebenen[`Rectangle`](../rectangle) Struktur. |
| [Region](region#constructor_3)(RectangleF) | Initialisiert eine neue[`Region`](../region) aus dem angegebenen[`RectangleF`](../rectanglef) Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement#complement)(GraphicsPath) | aktualisiert dies[`Region`](../region) um den Teil des angegebenen zu enthalten[`GraphicsPath`](../graphicspath) das überschneidet sich damit nicht[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_1)(Rectangle) | aktualisiert dies[`Region`](../region) um den Teil des angegebenen zu enthalten[`Rectangle`](../rectangle) Struktur, die sich damit nicht überschneidet[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_2)(RectangleF) | aktualisiert dies[`Region`](../region) um den Teil des angegebenen zu enthalten[`RectangleF`](../rectanglef) Struktur, die sich damit nicht überschneidet[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_3)(Region) | aktualisiert dies[`Region`](../region) um den Teil des angegebenen zu enthalten[`Region`](../region) das überschneidet sich damit nicht[`Region`](../region) . |
| [DeepClone](../../aspose.imaging/region/deepclone)() | Erstellt eine exakte tiefe Kopie davon[`Region`](../region) . |
| [Equals](../../aspose.imaging/region/equals#equals)(Region, Graphics) | Testet, ob die angegebene[`Region`](../region) ist damit identisch[`Region`](../region) auf der angegebenen Zeichenfläche. |
| [Exclude](../../aspose.imaging/region/exclude#exclude)(GraphicsPath) | aktualisiert dies[`Region`](../region) um nur den Teil seines Inneren zu enthalten, der sich nicht mit dem angegebenen schneidet[`GraphicsPath`](../graphicspath) . |
| [Exclude](../../aspose.imaging/region/exclude#exclude_1)(Rectangle) | aktualisiert dies[`Region`](../region) um nur den Teil seines Inneren zu enthalten, der sich nicht mit dem angegebenen schneidet[`Rectangle`](../rectangle) Struktur. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_2)(RectangleF) | aktualisiert dies[`Region`](../region) um nur den Teil seines Inneren zu enthalten, der sich nicht mit dem angegebenen schneidet[`RectangleF`](../rectanglef) Struktur. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_3)(Region) | aktualisiert dies[`Region`](../region) um nur den Teil seines Inneren zu enthalten, der sich nicht mit dem angegebenen schneidet[`Region`](../region) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect)(GraphicsPath) | aktualisiert dies[`Region`](../region) zum Schnittpunkt von sich selbst mit dem angegebenen[`GraphicsPath`](../graphicspath) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect_1)(Rectangle) | aktualisiert dies[`Region`](../region) zum Schnittpunkt von sich selbst mit dem angegebenen[`Rectangle`](../rectangle) Struktur. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_2)(RectangleF) | aktualisiert dies[`Region`](../region) zum Schnittpunkt von sich selbst mit dem angegebenen[`RectangleF`](../rectanglef) Struktur. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_3)(Region) | aktualisiert dies[`Region`](../region) zum Schnittpunkt von sich selbst mit dem angegebenen[`Region`](../region) . |
| [IsEmpty](../../aspose.imaging/region/isempty)(Graphics) | Testet ob dies[`Region`](../region) hat einen leeren Innenraum auf der angegebenen Zeichenfläche. |
| [IsInfinite](../../aspose.imaging/region/isinfinite)(Graphics) | Testet ob dies[`Region`](../region) hat einen unendlichen Innenraum auf der angegebenen Zeichenfläche. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible)(Point) | Testet, ob die angegebene[`Point`](../point) Struktur ist darin enthalten[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_2)(PointF) | Testet, ob die angegebene[`PointF`](../pointf) Struktur ist darin enthalten[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_4)(Rectangle) | Testet, ob irgendein Teil der angegebenen[`Rectangle`](../rectangle) Struktur ist darin enthalten[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_6)(RectangleF) | Testet, ob irgendein Teil der angegebenen[`RectangleF`](../rectanglef) Struktur ist darin enthalten[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_11)(float, float) | Prüft, ob der angegebene Punkt darin enthalten ist[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_1)(Point, Graphics) | Testet, ob die angegebene[`Point`](../point) Struktur ist darin enthalten[`Region`](../region)wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_3)(PointF, Graphics) | Testet, ob die angegebene[`PointF`](../pointf) Struktur ist darin enthalten[`Region`](../region)wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_5)(Rectangle, Graphics) | Testet, ob irgendein Teil der angegebenen[`Rectangle`](../rectangle) Struktur ist darin enthalten[`Region`](../region)wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_7)(RectangleF, Graphics) | Testet, ob irgendein Teil der angegebenen[`RectangleF`](../rectanglef) Struktur ist darin enthalten[`Region`](../region)wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_12)(float, float, Graphics) | Prüft, ob der angegebene Punkt darin enthalten ist[`Region`](../region)wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_8)(int, int, Graphics) | Prüft, ob der angegebene Punkt darin enthalten ist[`Region`](../region) Objekt beim Zeichnen mit dem angegebenen[`Graphics`](../graphics) Objekt. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_13)(float, float, float, float) | Testet, ob ein Teil des angegebenen Rechtecks darin enthalten ist[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_9)(int, int, int, int) | Testet, ob ein Teil des angegebenen Rechtecks darin enthalten ist[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | Testet, ob ein Teil des angegebenen Rechtecks darin enthalten ist[`Region`](../region)wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | Testet, ob ein Teil des angegebenen Rechtecks darin enthalten ist[`Region`](../region)wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [MakeEmpty](../../aspose.imaging/region/makeempty)() | Initialisiert dies[`Region`](../region) zu einem leeren Innenraum. |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite)() | Initialisiert dies[`Region`](../region) Objekt zu einem unendlichen Inneren. |
| [Transform](../../aspose.imaging/region/transform)(Matrix) | Transformiert dies[`Region`](../region) durch die angegebenen[`Matrix`](../matrix) . |
| [Translate](../../aspose.imaging/region/translate#translate_1)(float, float) | Versetzt die Koordinaten davon[`Region`](../region) um den angegebenen Betrag. |
| [Translate](../../aspose.imaging/region/translate#translate)(int, int) | Versetzt die Koordinaten davon[`Region`](../region) um den angegebenen Betrag. |
| [Union](../../aspose.imaging/region/union#union)(GraphicsPath) | aktualisiert dies[`Region`](../region) zur Vereinigung von sich selbst und dem Spezifizierten[`GraphicsPath`](../graphicspath) . |
| [Union](../../aspose.imaging/region/union#union_1)(Rectangle) | aktualisiert dies[`Region`](../region) zur Vereinigung von sich selbst und dem Spezifizierten[`Rectangle`](../rectangle) Struktur. |
| [Union](../../aspose.imaging/region/union#union_2)(RectangleF) | aktualisiert dies[`Region`](../region) zur Vereinigung von sich selbst und dem Spezifizierten[`RectangleF`](../rectanglef) Struktur. |
| [Union](../../aspose.imaging/region/union#union_3)(Region) | aktualisiert dies[`Region`](../region) zur Vereinigung von sich selbst und dem Spezifizierten[`Region`](../region) . |
| [Xor](../../aspose.imaging/region/xor#xor)(GraphicsPath) | aktualisiert dies[`Region`](../region) zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen[`GraphicsPath`](../graphicspath) . |
| [Xor](../../aspose.imaging/region/xor#xor_1)(Rectangle) | aktualisiert dies[`Region`](../region) zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen[`Rectangle`](../rectangle) Struktur. |
| [Xor](../../aspose.imaging/region/xor#xor_2)(RectangleF) | aktualisiert dies[`Region`](../region) zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen[`RectangleF`](../rectanglef) Struktur. |
| [Xor](../../aspose.imaging/region/xor#xor_3)(Region) | aktualisiert dies[`Region`](../region) zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen[`Region`](../region) . |

### Siehe auch

* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
