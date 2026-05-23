---
title: "Classe EmfPlusDrawBeziers"
type: docs
weight: 80
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| compresso | bool | r/w | Ottiene o imposta un valore che indica se il PointData è compresso. <br/>            Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con <br/>            coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute <br/>            nello spazio delle coordinate con coordinate a virgola mobile a 32 bit.<br/>            Nota Se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella EMF+<br/>            Object Table per disegnare le curve Bezier. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta i dati dei punti<br/>            Un array di punti Count che specificano i punti di inizio, fine e di controllo delle curve Bezier. La coordinata finale di una curva Bezier è la coordinata iniziale della successiva. I punti di controllo sono usati per produrre l'effetto Bezier.<br/>            Il tipo di dati in questo array è specificato dal campo Flags, come segue: Significato del Tipo di Dati<br/>            oggetto EmfPlusPointR (sezione 2.2.2.37)<br/>            Se il flag P è impostato nei Flags, i punti specificano posizioni relative.<br/>            oggetto EmfPlusPointF (sezione 2.2.2.36)<br/>            Se i flag P e C sono non impostati nel campo Flags, i punti specificano posizioni assolute.<br/>            oggetto EmfPlusPoint (sezione 2.2.2.35)<br/>            Se il flag P è non impostato e il flag C è impostato nel campo Flags, i punti specificano posizioni relative.<br/>            Una curva Bezier non passa attraverso i suoi punti di controllo. I punti di controllo agiscono come |
| relative | bool | r/w | Ottiene o imposta un valore che indica se il PointData è relativo.<br/>            Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate <br/>            che è relativa alla posizione specificata dall'elemento precedente nell'array. <br/>            Nel caso del primo elemento in PointData, si presume una posizione precedente alle coordinate <br/>            (0,0). Se non impostato, PointData specifica posizioni assolute secondo <br/>            il flag C.<br/>            Nota: se questo flag è impostato, il flag C (sopra) è indefinito e DEVE essere ignorato. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

