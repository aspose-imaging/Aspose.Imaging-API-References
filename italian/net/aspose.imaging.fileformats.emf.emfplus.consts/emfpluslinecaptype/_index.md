---
title: EmfPlusLineCapType
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lenumerazione LineCapType definisce i tipi di terminazioni di linea da utilizzare alle estremità delle linee disegnate con penne grafiche.
type: docs
weight: 4890
url: /it/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
## EmfPlusLineCapType enumeration

L'enumerazione LineCapType definisce i tipi di terminazioni di linea da utilizzare alle estremità delle linee disegnate con penne grafiche.

```csharp
public enum EmfPlusLineCapType
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| LineCapTypeFlat | `0` | Specifica un limite di linea squadrato. La fine della linea DEVE essere l'ultimo punto della linea. |
| LineCapTypeSquare | `1` | Specifica un limite di linea quadrata. Il centro della piazza DEVE trovarsi nell'ultimo punto della linea. La larghezza del quadrato è la larghezza della linea. |
| LineCapTypeRound | `2` | Specifica un limite di linea circolare. Il centro del cerchio DEVE trovarsi nell'ultimo punto della linea. Il diametro del cerchio è la larghezza della linea. |
| LineCapTypeTriangle | `3` | Specifica un limite di linea triangolare. La base del triangolo DEVE trovarsi nell'ultimo punto della linea. La base del triangolo è la larghezza della linea. |
| LineCapTypeNoAnchor | `16` | Specifica che l'estremità della linea non è ancorata. |
| LineCapTypeSquareAnchor | `17` | Specifica che l'estremità della linea è ancorata con un'estremità quadrata. Il centro della piazza DEVE trovarsi nell'ultimo punto della linea. L'altezza e la larghezza del quadrato sono la larghezza della linea. |
| LineCapTypeRoundAnchor | `18` | Specifica che l'estremità della linea è ancorata con un limite di linea circolare. Il centro del cerchio DEVE trovarsi nell'ultimo punto della linea. Il cerchio DOVREBBE essere più largo della linea. |
| LineCapTypeDiamondAnchor | `19` | Specifica che l'estremità della linea è ancorata con un limite di linea a forma di diamante, che è un quadrato ruotato di 45 gradi. Il centro del diamante DEVE trovarsi nell'ultimo punto della linea. Il diamante DOVREBBE essere più largo della linea. |
| LineCapTypeArrowAnchor | `20` | Specifica che l'estremità della linea è ancorata con una forma a punta di freccia. Il punto della freccia DEVE essere posizionato nell'ultimo punto della linea. La punta della freccia DEVE essere più larga della linea. |
| LineCapTypeAnchorMask | `240` | Maschera utilizzata per verificare se un limite di linea è un limite di ancoraggio. |
| LineCapTypeCustom | `255` | Specifica un limite di riga personalizzato. |

### Osservazioni

I limiti delle linee grafiche sono specificati da[`EmfPlusPen`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) oggetti (sezione 2.2.1.7).

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
