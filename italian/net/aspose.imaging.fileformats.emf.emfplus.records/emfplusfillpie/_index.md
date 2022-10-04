---
title: EmfPlusFillPie
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusFillPie specifica il riempimento di una sezione dellinterno di unellisse
type: docs
weight: 6090
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
## EmfPlusFillPie class

Il record EmfPlusFillPie specifica il riempimento di una sezione dell'interno di un'ellisse

```csharp
public sealed class EmfPlusFillPie : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusFillPie](emfplusfillpie)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusFillPie`](../emfplusfillpie) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/brushid) { get; set; } | Ottiene o imposta l'identificatore del pennello Un numero intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/compressed) { get; set; } | Ottiene o imposta un valore che indica se PointData è compresso. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se deselezionato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/iscolor) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è color. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se deselezionato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella tabella oggetti EMF+. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/rectdata) { get; set; } | Ottiene o imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse che contiene il cuneo della torta. Questo rettangolo definisce la posizione, la dimensione, e la forma della torta. Il tipo di oggetto in questo campo è specificato dal valore del campo Flags. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [StartAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/startangle) { get; set; } | Ottiene o imposta l'angolo iniziale Un valore a virgola mobile non negativo a 32 bit che specifica l'angolo tra l'asse x e il punto iniziale del cuneo della torta. Qualsiasi valore è accettabile, ma DEVE essere interpretato modulo 360, con il risultato utilizzato compreso tra 0.0 compreso e 360.0 esclusivo. |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/sweepangle) { get; set; } | Ottiene o imposta l'angolo di scansione Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco che definisce il cuneo della torta da disegnare, come angolo in gradi misurato dal punto iniziale definito dal valore StartAngle. Qualsiasi valore è accettabile, ma DEVE essere bloccato da a -360,0 a 360,0 inclusi. Un valore positivo indica che lo sweep è definito in senso orario e un valore negativo indica che lo sweep è definito in senso antiorario. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->