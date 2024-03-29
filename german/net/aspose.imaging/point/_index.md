---
title: Point
second_title: Aspose.Imaging für .NET-API-Referenz
description: Stellt ein geordnetes Paar ganzzahliger x- und y-Koordinaten dar das einen Punkt in einer zweidimensionalen Ebene definiert.
type: docs
weight: 10740
url: /de/net/aspose.imaging/point/
---
## Point structure

Stellt ein geordnetes Paar ganzzahliger x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.

```csharp
public struct Point
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Point](point#constructor_1)(int) | Initialisiert eine neue Instanz von[`Point`](../point) Struktur mit Koordinaten, die durch einen ganzzahligen Wert angegeben werden. |
| [Point](point#constructor)(Size) | Initialisiert eine neue Instanz von[`Point`](../point) Struktur aus der[`Size`](../size) Struktur. |
| [Point](point#constructor_2)(int, int) | Initialisiert eine neue Instanz von[`Point`](../point) Struktur mit den angegebenen Koordinaten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.imaging/point/empty) { get; } | Ruft eine neue Instanz von ab[`Point`](../point) Struktur, die hat[`X`](./x) und[`Y`](./y) Werte auf Null gesetzt. |
| [IsEmpty](../../aspose.imaging/point/isempty) { get; } | Ruft einen Wert ab, der angibt, ob dies[`Point`](../point) ist leer. |
| [X](../../aspose.imaging/point/x) { get; set; } | Holt oder setzt die x-Koordinate davon[`Point`](../point) . |
| [Y](../../aspose.imaging/point/y) { get; set; } | Holt oder setzt die y-Koordinate davon[`Point`](../point) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Add](../../aspose.imaging/point/add)(Point, Size) | Fügt die angegebenen hinzu[`Size`](../size) zu den angegebenen[`Point`](../point) . |
| static [Ceiling](../../aspose.imaging/point/ceiling)(PointF) | Konvertiert die angegebene[`PointF`](../pointf) zu einem[`Point`](../point) durch Rundung der Werte der[`PointF`](../pointf) zu den nächsthöheren ganzzahligen Werten. |
| static [Round](../../aspose.imaging/point/round)(PointF) | Konvertiert die angegebene[`PointF`](../pointf) zu einem[`Point`](../point) Objekt durch Runden der[`Point`](../point) Werte auf die nächste ganze Zahl. |
| static [Subtract](../../aspose.imaging/point/subtract)(Point, Size) | Gibt das Ergebnis der angegebenen Subtraktion zurück[`Size`](../size) aus dem angegebenen[`Point`](../point) . |
| static [Truncate](../../aspose.imaging/point/truncate)(PointF) | Konvertiert die angegebene[`PointF`](../pointf) zu einem[`Point`](../point) durch Abschneiden der Werte der[`Point`](../point) . |
| override [Equals](../../aspose.imaging/point/equals)(object) | Gibt an, ob dies[`Point`](../point) enthält dieselben Koordinaten wie die angegebenenObject . |
| override [GetHashCode](../../aspose.imaging/point/gethashcode)() | Gibt dafür einen Hashcode zurück[`Point`](../point) . |
| [Offset](../../aspose.imaging/point/offset#offset)(Point) | übersetzt dies[`Point`](../point) durch die angegebenen[`Point`](../point) . |
| [Offset](../../aspose.imaging/point/offset#offset_1)(int, int) | übersetzt dies[`Point`](../point) um den angegebenen Betrag. |
| override [ToString](../../aspose.imaging/point/tostring)() | Konvertiert dies[`Point`](../point) in eine für Menschen lesbare Zeichenfolge. |
| [operator +](../../aspose.imaging/point/op_addition) | übersetzt a[`Point`](../point) durch eine gegeben[`Size`](../size) . |
| [operator ==](../../aspose.imaging/point/op_equality) | Vergleicht zwei[`Point`](../point) Objekte. Das Ergebnis gibt an, ob die Werte der[`X`](./x) und[`Y`](./y) Eigenschaften der beiden[`Point`](../point) Objekte sind gleich. |
| [explicit operator](../../aspose.imaging/point/op_explicit) | Konvertiert die angegebene[`Point`](../point) Struktur zu a[`Size`](../size) Struktur. |
| [implicit operator](../../aspose.imaging/point/op_implicit) | Konvertiert die angegebene[`Point`](../point) Struktur zu[`PointF`](../pointf) Struktur. |
| [operator !=](../../aspose.imaging/point/op_inequality) | Vergleicht zwei[`Point`](../point) Objekte. Das Ergebnis gibt an, ob die Werte der[`X`](./x) oder[`Y`](./y) Eigenschaften der beiden[`Point`](../point) Objekte sind ungleich. |
| [operator -](../../aspose.imaging/point/op_subtraction) | übersetzt a[`Point`](../point) durch das Negativ eines Gegebenen[`Size`](../size) . |

### Siehe auch

* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
