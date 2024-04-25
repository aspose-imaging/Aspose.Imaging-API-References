---
title: Region
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Descrive linterno di una forma grafica composta da rettangoli e percorsi. Questa classe non può essere ereditata.
type: docs
weight: 10850
url: /it/aspose.imaging/region/
---
## Region class

Descrive l'interno di una forma grafica composta da rettangoli e percorsi. Questa classe non può essere ereditata.

```csharp
public sealed class Region
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Region](region#constructor)() | Inizializza un nuovo[`Region`](../region) . |
| [Region](region#constructor_1)(GraphicsPath) | Inizializza un nuovo[`Region`](../region) con il specificato[`GraphicsPath`](../graphicspath) . |
| [Region](region#constructor_2)(Rectangle) | Inizializza un nuovo[`Region`](../region) dal specificato[`Rectangle`](../rectangle) struttura. |
| [Region](region#constructor_3)(RectangleF) | Inizializza un nuovo[`Region`](../region) dal specificato[`RectangleF`](../rectanglef) struttura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement#complement)(GraphicsPath) | Aggiorna questo[`Region`](../region) per contenere la parte del specificato[`GraphicsPath`](../graphicspath) che non si interseca con questo[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_1)(Rectangle) | Aggiorna questo[`Region`](../region) per contenere la parte del specificato[`Rectangle`](../rectangle) struttura che non si interseca con essa[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_2)(RectangleF) | Aggiorna questo[`Region`](../region) per contenere la parte del specificato[`RectangleF`](../rectanglef) struttura che non si interseca con essa[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_3)(Region) | Aggiorna questo[`Region`](../region) per contenere la parte del specificato[`Region`](../region) che non si interseca con questo[`Region`](../region) . |
| [DeepClone](../../aspose.imaging/region/deepclone)() | Crea una copia completa esatta di questo[`Region`](../region) . |
| [Equals](../../aspose.imaging/region/equals#equals)(Region, Graphics) | Verifica se è specificato[`Region`](../region) è identico a questo[`Region`](../region) sulla superficie di disegno specificata. |
| [Exclude](../../aspose.imaging/region/exclude#exclude)(GraphicsPath) | Aggiorna questo[`Region`](../region) contenere solo la porzione del suo interno che non si interseca con il specificato[`GraphicsPath`](../graphicspath) . |
| [Exclude](../../aspose.imaging/region/exclude#exclude_1)(Rectangle) | Aggiorna questo[`Region`](../region) contenere solo la porzione del suo interno che non si interseca con il specificato[`Rectangle`](../rectangle) struttura. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_2)(RectangleF) | Aggiorna questo[`Region`](../region) contenere solo la porzione del suo interno che non si interseca con il specificato[`RectangleF`](../rectanglef) struttura. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_3)(Region) | Aggiorna questo[`Region`](../region) contenere solo la porzione del suo interno che non si interseca con il specificato[`Region`](../region) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect)(GraphicsPath) | Aggiorna questo[`Region`](../region) all'intersezione di se stesso con il specificato[`GraphicsPath`](../graphicspath) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect_1)(Rectangle) | Aggiorna questo[`Region`](../region) all'intersezione di se stesso con il specificato[`Rectangle`](../rectangle) struttura. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_2)(RectangleF) | Aggiorna questo[`Region`](../region) all'intersezione di se stesso con il specificato[`RectangleF`](../rectanglef) struttura. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_3)(Region) | Aggiorna questo[`Region`](../region) all'intersezione di se stesso con il specificato[`Region`](../region) . |
| [IsEmpty](../../aspose.imaging/region/isempty)(Graphics) | Verifica se questo[`Region`](../region) ha un interno vuoto sulla superficie di disegno specificata. |
| [IsInfinite](../../aspose.imaging/region/isinfinite)(Graphics) | Verifica se questo[`Region`](../region) ha un interno infinito sulla superficie di disegno specificata. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible)(Point) | Verifica se è specificato[`Point`](../point) la struttura è contenuta in questo[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_2)(PointF) | Verifica se è specificato[`PointF`](../pointf) la struttura è contenuta in questo[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_4)(Rectangle) | Verifica se qualsiasi parte dell'oggetto specificato[`Rectangle`](../rectangle) la struttura è contenuta in questo[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_6)(RectangleF) | Verifica se qualsiasi parte dell'oggetto specificato[`RectangleF`](../rectanglef) la struttura è contenuta in questo[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_11)(float, float) | Verifica se il punto specificato è contenuto all'interno di questo[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_1)(Point, Graphics) | Verifica se è specificato[`Point`](../point) la struttura è contenuta in questo[`Region`](../region)quando disegnato usando il specificato[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_3)(PointF, Graphics) | Verifica se è specificato[`PointF`](../pointf) la struttura è contenuta in questo[`Region`](../region)quando disegnato usando il specificato[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_5)(Rectangle, Graphics) | Verifica se qualsiasi parte dell'oggetto specificato[`Rectangle`](../rectangle) la struttura è contenuta in questo[`Region`](../region)quando disegnato usando il specificato[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_7)(RectangleF, Graphics) | Verifica se qualsiasi parte dell'oggetto specificato[`RectangleF`](../rectanglef) la struttura è contenuta in questo[`Region`](../region)quando disegnato usando il specificato[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_12)(float, float, Graphics) | Verifica se il punto specificato è contenuto all'interno di questo[`Region`](../region)quando disegnato usando il specificato[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_8)(int, int, Graphics) | Verifica se il punto specificato è contenuto all'interno di questo[`Region`](../region) oggetto quando disegnato utilizzando l'oggetto specificato[`Graphics`](../graphics) oggetto. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_13)(float, float, float, float) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_9)(int, int, int, int) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../region)quando disegnato usando il specificato[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../region)quando disegnato usando il specificato[`Graphics`](../graphics) . |
| [MakeEmpty](../../aspose.imaging/region/makeempty)() | Inizializza questo[`Region`](../region) a un interno vuoto. |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite)() | Inizializza questo[`Region`](../region) oggetto di un interno infinito. |
| [Transform](../../aspose.imaging/region/transform)(Matrix) | Lo trasforma[`Region`](../region) dal specificato[`Matrix`](../matrix) . |
| [Translate](../../aspose.imaging/region/translate#translate_1)(float, float) | Sposta le coordinate di questo[`Region`](../region) per l'importo specificato. |
| [Translate](../../aspose.imaging/region/translate#translate)(int, int) | Sposta le coordinate di questo[`Region`](../region) per l'importo specificato. |
| [Union](../../aspose.imaging/region/union#union)(GraphicsPath) | Aggiorna questo[`Region`](../region) all'unione di sé e del specificato[`GraphicsPath`](../graphicspath) . |
| [Union](../../aspose.imaging/region/union#union_1)(Rectangle) | Aggiorna questo[`Region`](../region) all'unione di sé e del specificato[`Rectangle`](../rectangle) struttura. |
| [Union](../../aspose.imaging/region/union#union_2)(RectangleF) | Aggiorna questo[`Region`](../region) all'unione di sé e del specificato[`RectangleF`](../rectanglef) struttura. |
| [Union](../../aspose.imaging/region/union#union_3)(Region) | Aggiorna questo[`Region`](../region) all'unione di sé e del specificato[`Region`](../region) . |
| [Xor](../../aspose.imaging/region/xor#xor)(GraphicsPath) | Aggiorna questo[`Region`](../region) all'unione meno l'intersezione di se stesso con il specificato[`GraphicsPath`](../graphicspath) . |
| [Xor](../../aspose.imaging/region/xor#xor_1)(Rectangle) | Aggiorna questo[`Region`](../region) all'unione meno l'intersezione di se stesso con il specificato[`Rectangle`](../rectangle) struttura. |
| [Xor](../../aspose.imaging/region/xor#xor_2)(RectangleF) | Aggiorna questo[`Region`](../region) all'unione meno l'intersezione di se stesso con il specificato[`RectangleF`](../rectanglef) struttura. |
| [Xor](../../aspose.imaging/region/xor#xor_3)(Region) | Aggiorna questo[`Region`](../region) all'unione meno l'intersezione di se stesso con il specificato[`Region`](../region) . |

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
