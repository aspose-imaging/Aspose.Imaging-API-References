---
title: EmfPlusPenOptionalData
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto EmfPlusPenOptionalData specifica i dati facoltativi per una penna grafica
type: docs
weight: 5680
url: /it/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

L'oggetto EmfPlusPenOptionalData specifica i dati facoltativi per una penna grafica

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata) { get; set; } | Ottiene o imposta l'oggetto EmfPlusCompoundLineData facoltativo (sezione 2.2.2.9) che specifica una matrice di valori a virgola mobile che definiscono la linea composta di una penna, composta da linee parallele e spazi. Questo campo DEVE essere presente se il flag PenDataCompoundLine è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata) { get; set; } | Ottiene o imposta l'oggetto EmfPlusCustomEndCapData facoltativo (sezione 2.2.2.11) che definisce la forma dell'estremità personalizzata, ovvero la forma da utilizzare alla fine di una linea disegnata con questa penna. Può essere una qualsiasi delle varie forme, come un quadrato, un cerchio o un diamante. Questo campo DEVE essere presente se il flag PenDataCustomEndCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata) { get; set; } | Ottiene o imposta l'oggetto EmfPlusCustomStartCapData facoltativo (sezione 2.2.2.15) che definisce la forma del cappuccio iniziale personalizzata, ovvero la forma da utilizzare all'inizio di una linea disegnata con questa penna. Può essere qualsiasi di varie forme, come un quadrato, un cerchio o un diamante. Questo campo DEVE essere presente se il flag PenDataCustomStartCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype) { get; set; } | Ottiene o imposta un intero con segno a 32 bit facoltativo che specifica la forma per entrambe le estremità di ciascun trattino in una linea tratteggiata. Questo campo DEVE essere presente se il flag PenDataDashedLineCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData e il valore DEVE essere definito nell'enumerazione DashedLineCapType (sezione 2.1.1.10). |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata) { get; set; } | Ottiene o imposta l'oggetto EmfPlusDashedLineData facoltativo (sezione 2.2.2.16) che specifica le lunghezze di trattini e spazi in una linea tratteggiata personalizzata. Questo campo DEVE essere presente se il flag PenDataDashedLine è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData . |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit facoltativo che specifica la distanza dall'inizio di una riga all'inizio del primo spazio in un modello di linea tratteggiata. Questo campo DEVE essere presente se il flag PenDataDashedLineOffset è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap) { get; set; } | Ottiene o imposta un intero con segno a 32 bit facoltativo che specifica lo shape per la fine di una riga nel campo CustomEndCapData. Questo campo DEVE essere presente se il flag PenDataEndCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData e il valore DEVE essere definito nell'enumerazione LineCapType |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join) { get; set; } | Ottiene o imposta un intero con segno a 32 bit facoltativo che specifica come unire due linee disegnate dalla stessa penna e le cui estremità si incontrano. Questo campo DEVE essere presente se il flag PenDataJoin è impostato in il campo PenDataFlags dell'oggetto EmfPlusPenData e il valore DEVE essere definito nell'enumerazione LineJoinType (sezione 2.1.1.19). |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle) { get; set; } | Ottiene o imposta un intero con segno a 32 bit facoltativo che specifica lo stile utilizzato per le linee disegnate con questo oggetto penna. Questo campo DEVE essere presente se il flag PenDataLineStyle è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData e il valore DEVE essere definito nell'enumerazione LineStyle (sezione 2.1.1.20). |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit facoltativo che specifica il limite di dell'angolo di taglio, che è il rapporto massimo consentito tra la lunghezza dell'angolo di taglio e la larghezza della linea . La lunghezza del taglio è la distanza dall'intersezione dei muri lineari all'interno del giunto a l'intersezione dei muri lineari all'esterno del giunto. La lunghezza della smussatura può essere grande quando l'angolo tra due linee è piccolo. Questo campo DEVE essere presente se il flag PenDataMiterLimit è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment) { get; set; } | Ottiene o imposta un intero con segno a 32 bit facoltativo che specifica la distribuzione della larghezza della penna rispetto alle coordinate della linea disegnata. Questo campo DEVE essere se il flag PenDataNonCenter è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData e il valore DEVE essere definito nell'enumerazione PenAlignment (sezione 2.1.1.24). |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap) { get; set; } | Ottiene o imposta un intero con segno a 32 bit facoltativo che specifica la forma per l'inizio di una riga nel campo CustomStartCapData. Questo campo DEVE essere presente se il flag PenDataStartCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData e il valore DEVE essere definito nell'enumerazione LineCapType (sezione 2.1.1.18). |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix) { get; set; } | Ottiene o imposta un oggetto EmfPlusTransformMatrix facoltativo (sezione 2.2.2.47) che specifica una trasformazione da spazio globale a spazio dispositivo per la penna. Questo campo DEVE essere presente se il flag PenDataTransform è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData . |

### Guarda anche

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
