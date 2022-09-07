---
title: Rectangle
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Memorizza un insieme di quattro numeri interi che rappresentano la posizione e la dimensione di un rettangolo.
type: docs
weight: 10830
url: /it/net/aspose.imaging/rectangle/
---
## Rectangle structure

Memorizza un insieme di quattro numeri interi che rappresentano la posizione e la dimensione di un rettangolo.

```csharp
public struct Rectangle
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Inizializza una nuova istanza di[`Rectangle`](../rectangle) struttura con la posizione e le dimensioni specificate. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Inizializza una nuova istanza di[`Rectangle`](../rectangle) struttura con la posizione e le dimensioni specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | Ottiene una nuova istanza di[`Rectangle`](../rectangle) struttura che ha[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) e[`Height`](./height) valori impostati a zero. |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | Ottiene o imposta la coordinata y che è la somma di[`Y`](./y) e[`Height`](./height) valori di proprietà di questo[`Rectangle`](../rectangle) struttura. |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | Ottiene o imposta l'altezza di questo[`Rectangle`](../rectangle) struttura. |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | Ottiene un valore che indica se tutte le proprietà numeriche di questo[`Rectangle`](../rectangle) avere valori pari a zero. |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | Ottiene o imposta la coordinata x del bordo sinistro di questo[`Rectangle`](../rectangle) struttura. |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | Ottiene o imposta le coordinate dell'angolo superiore sinistro di questo[`Rectangle`](../rectangle) struttura. |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | Ottiene o imposta la coordinata x che è la somma di[`X`](./x) e[`Width`](./width) valori di proprietà di questo[`Rectangle`](../rectangle) struttura. |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | Ottiene o imposta la dimensione di questo[`Rectangle`](../rectangle) . |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | Ottiene o imposta la coordinata y del bordo superiore di questo[`Rectangle`](../rectangle) struttura. |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | Ottiene o imposta la larghezza di questo[`Rectangle`](../rectangle) struttura. |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questo[`Rectangle`](../rectangle) struttura. |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questo[`Rectangle`](../rectangle) struttura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | Converte l'oggetto specificato[`RectangleF`](../rectanglef) struttura ad a[`Rectangle`](../rectangle) struttura arrotondando il[`RectangleF`](../rectanglef) valori ai successivi valori interi superiori. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | Crea a[`Rectangle`](../rectangle) struttura con le posizioni perimetrali specificate. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | Crea un nuovo[`Rectangle`](../rectangle) da due punti specificati. Due verticali del creato[`Rectangle`](../rectangle) sarà uguale al passato*point1* e*point2* . Questi sarebbero in genere i vertici opposti. |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | Crea e restituisce una copia gonfiata dell'oggetto specificato[`Rectangle`](../rectangle) struttura. La copia viene gonfiata dell'importo specificato. L'originale[`Rectangle`](../rectangle) la struttura rimane invariata. |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | Restituisce un terzo[`Rectangle`](../rectangle) struttura che rappresenta l'intersezione di altri due[`Rectangle`](../rectangle) strutture. Se non c'è incrocio, un vuoto[`Rectangle`](../rectangle) viene restituito. |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | Converte l'oggetto specificato[`RectangleF`](../rectanglef) ad un[`Rectangle`](../rectangle) arrotondando il[`RectangleF`](../rectanglef)valori ai valori interi più vicini. |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | Converte l'oggetto specificato[`RectangleF`](../rectanglef) ad un[`Rectangle`](../rectangle) troncando il[`RectangleF`](../rectanglef) valori. |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | Ottiene a[`Rectangle`](../rectangle) struttura che contiene l'unione di due[`Rectangle`](../rectangle) strutture. |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | Determina se il punto specificato è contenuto all'interno di questo[`Rectangle`](../rectangle) struttura. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | Determina se la regione rettangolare rappresentata da*rect* è interamente contenuto in questo[`Rectangle`](../rectangle) struttura. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | Determina se il punto specificato è contenuto all'interno di questo[`Rectangle`](../rectangle) struttura. |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | Verifica se*obj* è un[`Rectangle`](../rectangle)struttura con la stessa posizione e dimensione di questa[`Rectangle`](../rectangle) struttura. |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | Restituisce il codice hash per questo[`Rectangle`](../rectangle) struttura. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | Gonfia questo[`Rectangle`](../rectangle) per l'importo specificato. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | Gonfia questo[`Rectangle`](../rectangle) per l'importo specificato. |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | Sostituisce questo[`Rectangle`](../rectangle) con l'intersezione di se stesso e il specificato[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | Determina se questo rettangolo si interseca con*rect* . |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | Normalizza il rettangolo rendendo la larghezza e l'altezza positive, a sinistra meno di destra e in alto meno di sotto. |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | Regola la posizione di questo rettangolo della quantità specificata. |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | Regola la posizione di questo rettangolo della quantità specificata. |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | Converte gli attributi di questo[`Rectangle`](../rectangle) in una stringa leggibile dall'uomo. |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | Verifica se due[`Rectangle`](../rectangle)le strutture hanno la stessa posizione e dimensione. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | Verifica se due[`Rectangle`](../rectangle) le strutture differiscono per posizione o dimensioni. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
