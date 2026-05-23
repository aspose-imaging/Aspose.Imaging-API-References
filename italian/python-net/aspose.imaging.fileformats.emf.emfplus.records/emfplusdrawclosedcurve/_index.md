---
title: "EmfPlusDrawClosedCurve Classe"
type: docs
weight: 90
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

**Summary:** The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawClosedCurve(source)](#EmfPlusDrawClosedCurve_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType - Un intero senza segno a 16 bit che identifica questo tipo di record come EmfPlusDrawClosedCurve<br/>            dall'enumerazione RecordType (sezione 2.1.1.1). Il valore DEVE essere 0x4017. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) è compresso.<br/>            Questo bit indica se il campo PointData specifica dati compressi.<br/>            Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. <br/>            Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit<br/>            Nota Se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella EMF+<br/>            Object Table per disegnare la curva chiusa. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta i dati dei punti<br/>            Un array di Count punti che specificano le estremità delle linee che definiscono lo spline. In uno spline cardinal chiuso, <br/>            la curva continua attraverso l'ultimo punto nell'array PointData e si collega al primo punto dell'array.<br/>            Il tipo di dati in questo array è specificato dal campo Flags, come segue: Tipo di Dati Significato<br/>            oggetto EmfPlusPointR (sezione 2.2.2.37)<br/>            Se il flag P è impostato nei Flags, i punti specificano posizioni relative.<br/>            oggetto EmfPlusPointF (sezione 2.2.2.36)<br/>            Se i bit P e C sono impostati nel campo Flags, i punti specificano posizioni assolute.<br/>            oggetto EmfPlusPoint (sezione 2.2.2.35)<br/>            Se il bit P è non impostato e il bit C è impostato nel campo Flags, i punti specificano posizioni relative. |
| relative | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) è relativo.<br/>            Questo bit indica se il campo PointData specifica posizioni relative o assolute.<br/>            Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è relativa <br/>            alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo <br/>            elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se non impostato, <br/>            PointData specifica posizioni assolute secondo il flag C.<br/>            Nota Se questo flag è impostato, il flag Compressed (sopra) è indefinito e DEVE essere ignorato |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| tensione | float | r/w | Ottiene o imposta la tensione<br/>            Un numero a virgola mobile a 32 bit che specifica quanto strettamente lo spline <br/>            si piega mentre passa attraverso i punti. Un valore di 0 indica che <br/>            lo spline è una sequenza di linee rette. Man mano che il valore aumenta, <br/>            la curva diventa più arrotondata. Per ulteriori informazioni, vedere [SPLINE77] e [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawClosedCurve(source) {#EmfPlusDrawClosedCurve_source_1}


```
 EmfPlusDrawClosedCurve(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType - Un intero senza segno a 16 bit che identifica questo tipo di record come EmfPlusDrawClosedCurve<br/>            dall'enumerazione RecordType (sezione 2.1.1.1). Il valore DEVE essere 0x4017.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

