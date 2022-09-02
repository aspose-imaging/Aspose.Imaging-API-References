---
title: RectangleF
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Memorizza un insieme di quattro numeri a virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo.
type: docs
weight: 10840
url: /it/net/aspose.imaging/rectanglef/
---
## RectangleF structure

Memorizza un insieme di quattro numeri a virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo.

```csharp
public struct RectangleF
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | Inizializza una nuova istanza di[`RectangleF`](../rectanglef) struttura con la posizione e le dimensioni specificate. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | Inizializza una nuova istanza di[`RectangleF`](../rectanglef) struttura con la posizione e le dimensioni specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | Ottiene una nuova istanza di[`RectangleF`](../rectanglef) struttura che ha[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) e[`Height`](./height) valori impostati a zero. |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | Ottiene o imposta la coordinata y che è la somma di[`Y`](./y) e[`Height`](./height) di questo[`RectangleF`](../rectanglef) struttura. |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | Ottiene o imposta l'altezza di questo[`RectangleF`](../rectanglef) struttura. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | Ottiene un valore che indica se il[`Width`](./width) o[`Height`](./height) proprietà di questo[`RectangleF`](../rectanglef) ha un valore pari a zero. |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | Ottiene o imposta la coordinata x del bordo sinistro di questo[`RectangleF`](../rectanglef) struttura. |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | Ottiene o imposta le coordinate dell'angolo superiore sinistro di questo[`RectangleF`](../rectanglef) struttura. |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | Ottiene o imposta la coordinata x che è la somma di[`X`](./x) e[`Width`](./width) di questo[`RectangleF`](../rectanglef) struttura. |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | Ottiene o imposta la dimensione di questo[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | Ottiene o imposta la coordinata y del bordo superiore di questo[`RectangleF`](../rectanglef) struttura. |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | Ottiene o imposta la larghezza di questo[`RectangleF`](../rectanglef) struttura. |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questo[`RectangleF`](../rectanglef) struttura. |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questo[`RectangleF`](../rectanglef) struttura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Crea a[`RectangleF`](../rectanglef) struttura con l'angolo in alto a sinistra e l'angolo in basso a destra nelle posizioni specificate. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | Crea un nuovo[`Rectangle`](../rectangle) da due punti specificati. Due vertici del creato[`Rectangle`](../rectangle) sarà uguale al passato*point1* e*point2* . Questi sarebbero in genere i vertici opposti. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | Crea e restituisce una copia gonfiata dell'oggetto specificato[`RectangleF`](../rectanglef)struttura. La copia viene gonfiata dell'importo specificato. Il rettangolo originale rimane invariato. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | Restituisce a[`RectangleF`](../rectanglef) struttura che rappresenta l'intersezione di due rettangoli. Se non c'è incrocio e vuoto[`RectangleF`](../rectanglef) viene restituito. |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains)(PointF) | Determina se il punto specificato è contenuto all'interno di questo[`RectangleF`](../rectanglef) struttura. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_1)(RectangleF) | Determina se la regione rettangolare rappresentata da*rect* è interamente contenuto in questo[`RectangleF`](../rectanglef) struttura. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_2)(float, float) | Determina se il punto specificato è contenuto all'interno di questo[`RectangleF`](../rectanglef) struttura. |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | Verifica se*obj* è un[`RectangleF`](../rectanglef) con la stessa posizione e dimensione di questo[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | Ottiene il codice hash per questo[`RectangleF`](../rectanglef) struttura. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate)(SizeF) | Gonfia questo[`RectangleF`](../rectanglef) per l'importo specificato. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate_1)(float, float) | Gonfia questo[`RectangleF`](../rectanglef) struttura per l'importo specificato. |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | Sostituisce questo[`RectangleF`](../rectanglef)struttura con l'intersezione di se stessa e il specificato[`RectangleF`](../rectanglef) struttura. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | Determina se questo rettangolo si interseca con*rect* . |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | Normalizza il rettangolo rendendo la larghezza e l'altezza positive, a sinistra meno di destra e in alto meno di sotto. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset)(PointF) | Regola la posizione di questo rettangolo della quantità specificata. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset_1)(float, float) | Regola la posizione di questo rettangolo della quantità specificata. |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | Converte gli attributi di questo[`RectangleF`](../rectanglef) in una stringa leggibile dall'uomo. |
| [operator /](../../aspose.imaging/rectanglef/op_division) | Implementa l'operatore /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | Verifica se due[`RectangleF`](../rectanglef)le strutture hanno la stessa posizione e dimensione. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | Converte l'oggetto specificato[`Rectangle`](../rectangle) struttura ad a[`RectangleF`](../rectanglef) struttura. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | Verifica se due[`RectangleF`](../rectanglef) le strutture differiscono per posizione o dimensioni. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | Implementa l'operatore *. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
