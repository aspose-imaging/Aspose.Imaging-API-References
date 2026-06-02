---
title: "EmfPlusDrawLines Classe"
type: docs
weight: 150
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

**Summary:** The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawLines(source)](#EmfPlusDrawLines_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| closed_shape | bool | r/w | Ottiene o imposta un valore che indica se [closed shape]. |
| compressed | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) è compresso.<br/>            Questo bit indica se il campo PointData specifica dati compressi.<br/>            Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. <br/>            Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit<br/>            Nota Se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella EMF+<br/>            Object Table per disegnare le linee. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta i dati dei punti<br/>            Un array di Count punti che specificano i punti di inizio e fine delle linee da disegnare. |
| relative | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) è relativo.<br/>            Questo bit indica se il campo PointData specifica posizioni relative o assolute.<br/>            Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è relativa <br/>            alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo <br/>            elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se non impostato, <br/>            PointData specifica posizioni assolute secondo il flag C.<br/>            Nota Se questo flag è impostato, il flag Compressed (sopra) è indefinito e DEVE essere ignorato |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawLines(source) {#EmfPlusDrawLines_source_1}


```
 EmfPlusDrawLines(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

