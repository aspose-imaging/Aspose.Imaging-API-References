---
title: "Classe EmfPlusDrawImagePoints"
type: docs
weight: 140
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | Ottiene o imposta un valore che indica se [applying an effect].<br/>            Questo bit indica che il rendering dell'immagine include l'applicazione di un effetto.<br/>            Se impostato, un oggetto della classe Effect DEVE essere stato specificato in un record EmfPlusSerializableObject precedente (sezione 2.3.5.2). |
| compresso | bool | r/w | Ottiene o imposta un valore che indica se il PointData è compresso.<br/>            Questo bit indica se il campo PointData specifica dati compressi.<br/>            Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con interi a 16 bit.<br/>            Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit.<br/>            Nota Se il flag P (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| image_attributes_id | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che contiene l'indice del<br/>            oggetto EmfPlusImageAttributes opzionale (sezione 2.2.1.5) nella EMF+ Object Table. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice di un oggetto EmfPlusImage (sezione 2.2.1.4) nella EMF+<br/>            Object Table, che specifica l'immagine da renderizzare. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta un array di punti Count che specificano tre punti di un parallelogramma.<br/>            I tre punti rappresentano gli angoli superiore sinistro, superiore destro e inferiore sinistro del<br/>            parallelogramma. Il quarto punto del parallelogramma è estrapolato dai primi tre. La<br/>            porzione dell'immagine specificata dal campo SrcRect DOVREBBE avere trasformazioni di scala e shear<br/>            applicate, se necessario, per adattarsi all'interno del parallelogramma. |
| relative | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) è relativo.<br/>            Questo bit indica se il campo PointData specifica posizioni relative o assolute.<br/>            Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è<br/>            relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del<br/>            primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se non impostato,<br/>            PointData specifica posizioni assolute secondo il flag C.<br/>            Nota Se questo flag è impostato, il flag C (sopra) è indefinito e DEVE essere ignorato. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce una porzione dell'immagine da renderizzare. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Ottiene o imposta un intero con segno a 32 bit che definisce le unità del campo SrcRect. Deve<br/>            essere il valore UnitPixel dell'enumerazione UnitType (sezione 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

