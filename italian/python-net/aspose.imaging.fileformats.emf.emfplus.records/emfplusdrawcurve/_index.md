---
title: "Classe EmfPlusDrawCurve"
type: docs
weight: 100
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

**Summary:** The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) è compresso.<br/>            Questo bit indica se il campo PointData specifica dati compressi.<br/>            Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. <br/>            Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit<br/>            Nota Se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| num_segments | int | r/w | Ottiene o imposta il conteggio dei segmenti <br/>            Un intero senza segno a 32 bit che specifica il numero di segmenti di linea che compongono la spline. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella EMF+<br/>            Object Table per disegnare la curva. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta un array di interi a 32 bit con segno o di numeri a virgola mobile a 32 bit di lunghezza <br/>            Count che definisce i valori delle coordinate dei punti finali delle linee da tracciare. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| tensione | float | r/w | Ottiene o imposta la tensione<br/>            Un numero a virgola mobile a 32 bit che specifica quanto strettamente lo spline <br/>            si piega mentre passa attraverso i punti. Un valore di 0 indica che <br/>            lo spline è una sequenza di linee rette. Man mano che il valore aumenta, <br/>            la curva diventa più arrotondata. Per ulteriori informazioni, vedere [SPLINE77] e [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_1}


```
 EmfPlusDrawCurve(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

