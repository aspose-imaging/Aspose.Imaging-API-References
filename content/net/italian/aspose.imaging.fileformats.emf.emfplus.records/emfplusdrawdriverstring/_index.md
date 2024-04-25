---
title: EmfPlusDrawDriverString
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusDrawDriverString specifica loutput di testo con le posizioni dei caratteri.
type: docs
weight: 5940
url: /it/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

Il record EmfPlusDrawDriverString specifica l'output di testo con le posizioni dei caratteri.

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusDrawDriverString`](../emfplusdrawdriverstring) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid) { get; set; } | Ottiene o imposta l'identificatore del pennello Un numero intero senza segno a 32 bit che specifica il colore di primo piano del testo o un pennello grafico, a seconda del valore del flag S in Flags |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags) { get; set; } | Ottiene o imposta le opzioni della stringa del driver flags Un numero intero senza segno a 32 bit che specifica la spaziatura, l'orientamento e la qualità del rendering per la stringa. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount) { get; set; } | Ottiene o imposta il glyph count Un numero intero senza segno a 32 bit che specifica il numero di glifi nella stringa |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos) { get; set; } | Ottiene o imposta le posizioni dei glifi array Un array di oggetti EmfPlusPointF (sezione 2.2.2.36) che specificano la posizione di output di ciascun carattere glifo. DEVONO esserci elementi GlyphCount, che hanno una corrispondenza uno a uno con gli elementi nel Matrice di glifi. Le posizioni di glifi vengono calcolate dalla posizione del primo glifo se è impostato il flag DriverStringOptionsRealizedAdvance nei flag DriverStringOptions. In questo caso, GlyphPos specifica solo la posizione del primo glifo. |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs) { get; set; } | Ottiene o imposta la matrice dei glifi Una matrice di valori a 16 bit che definisce la stringa di testo da disegnare. Se è impostato il flag DriverStringOptionsCmapLookup nel campo DriverStringOptionsFlags, ogni valore in questa matrice specifica un carattere Unicode. In caso contrario, ogni valore specifica un indice per un glifo di carattere nell'oggetto EmfPlusFont specificato dal valore ObjectId nel campo Flags. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è color. Questo bit indica il tipo di dati nel campo BrushId. Se impostato, BrushId specifica il valore del colore in un oggetto EmfPlusARGB (sezione 2.2.2.1). Se deselezionato, BrushId contiene l'indice EMF+ Object di un oggetto EmfPlusBrush (sezione 2.2.1.1). |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent) { get; set; } | Ottiene o imposta se la matrice è presente flag Un numero intero senza segno a 32 bit che specifica se è presente una matrice di trasformazione nel campo TransformMatrix 0 - nessuna matrice presente. 1 - la matrice di trasformazione è nel campo TransformMatrix |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid) { get; set; } | Ottiene o imposta l'identificatore dell'oggetto. L'indice della tabella degli oggetti EMF+ di un[EmfPlusFont](EmfPlusFont) oggetto (sezione 2.2.1.3) per rendere il testo. Il valore DEVE essere da zero a 63, inclusi. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix) { get; set; } | Ottiene o imposta la matrice di trasformazione Un oggetto EmfPlusTransformMatrix facoltativo (sezione 2.2.2.47) che specifica la trasformazione da applicare a ciascun valore nella matrice di testo. La presenza di questi dati è determinata dal campo MatrixPresent. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
