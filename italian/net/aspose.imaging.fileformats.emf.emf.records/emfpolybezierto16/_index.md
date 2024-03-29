---
title: EmfPolyBezierTo16
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_POLYBEZIERTO16 specifica una o più curve di Bezier in base alla posizione corrente.
type: docs
weight: 3990
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---
## EmfPolyBezierTo16 class

Il record EMR_POLYBEZIERTO16 specifica una o più curve di Bezier in base alla posizione corrente.

```csharp
public sealed class EmfPolyBezierTo16 : EmfRecord
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPolyBezierTo16](emfpolybezierto16#constructor)() | Inizializza una nuova istanza di[`EmfPolyBezierTo16`](../emfpolybezierto16) classe. |
| [EmfPolyBezierTo16](emfpolybezierto16#constructor_1)(EmfRecord) | Inizializza una nuova istanza di[`EmfPolyBezierTo16`](../emfpolybezierto16) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/apoints) { get; set; } | Ottiene o imposta una matrice Count length di oggetti WMF PointS, specificata in [MS-WMF] sezione 2.2.2.16, che specifica la matrice di punti |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/bounds) { get; set; } | Ottiene o imposta un oggetto RectL WMF a 128 bit, specificato nella sezione [MS-WMF] 2.2.2.19, che specifica il rettangolo di delimitazione, in unità di dispositivo. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |

### Osservazioni

Le curve di Bezier cubiche sono definite utilizzando i punti finali e i punti di controllo specificati dal campo aPoints . La prima curva viene tracciata dal primo punto al quarto punto, utilizzando il secondo e il terzo punto come punti di controllo. Ogni curva successiva nella sequenza richiede esattamente altri tre punti: il punto finale della curva precedente viene utilizzato come punto iniziale, i due punti successivi nella sequenza sono punti di controllo e il terzo è il punto finale. Le curve di Bezier cubiche DEVONO essere disegnate usando la penna corrente

### Guarda anche

* class [EmfRecord](../emfrecord)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
