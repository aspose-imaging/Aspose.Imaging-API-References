---
title: EmfPlusDrawArc
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusDrawArc specifica il disegno dellarco di unellisse.
type: docs
weight: 5900
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
## EmfPlusDrawArc class

Il record EmfPlusDrawArc specifica il disegno dell'arco di un'ellisse.

```csharp
public sealed class EmfPlusDrawArc : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusDrawArc](emfplusdrawarc)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusDrawArc`](../emfplusdrawarc) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/datasize) { get; set; } | Ottiene o imposta la dimensione dei dati. Un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte di dati specifici del record che seguono. Per questo tipo di record, il valore DEVE essere uno dei seguenti : 0x00000010 Se il bit C è impostato nel campo Flag. 0x00000018 Se il bit C è azzerato nel campo Flag. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/objectid) { get; set; } | Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare l'arco. Il valore DEVE essere da zero a 63, inclusi. |
| [RectangleData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/rectangledata) { get; set; } | Ottiene o imposta il rettangolo data Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse collineare con l'arco. Questo rettangolo definisce la posizione, la dimensione e la forma dell'arco . Il tipo di oggetto in questo campo è specificato dal valore del campo Flags. |
| [RectFloat](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/rectfloat) { get; set; } | Ottiene o imposta un valore che indica se i dati contengono EmfPlusRectF o EmfPlusRect record Questo bit indica se i dati nel campo RectData sono compressi. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se azzerato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39). |
| override [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/size) { get; set; } | Ottiene o imposta la dimensione. Un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record . Per questo tipo di record, il valore DEVE essere uno dei seguenti: 0x0000001C Se il bit C è impostato nel campo Flags. 0x00000024 Se il bit C è azzerato nel campo Flags |
| [StartAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/startangle) { get; set; } | Ottiene o imposta l'angolo iniziale Un valore a virgola mobile non negativo a 32 bit che specifica l'angolo tra l'asse x e il punto iniziale dell'arco. Qualsiasi valore è accettabile, ma DEVE essere interpretato modulo 360, con il risultato utilizzato che è nell'intervallo da 0.0 incluso a 360.0 esclusivo. |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/sweepangle) { get; set; } | Ottiene o imposta l'angolo di scansione Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco da disegnare, come angolo in gradi misurato dal punto iniziale definito dal valore di StartAngle. Qualsiasi valore è accettabile, ma DEVE essere limitato a -360.0 a 360.0 inclusi. Un valore positivo indica che lo sweep è definito in in senso orario e un valore negativo indica che lo sweep è definito in senso antiorario. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
