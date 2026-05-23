---
title: "Classe EmfPlusDrawImage"
type: docs
weight: 130
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| compresso | bool | r/w | Ottiene o imposta un valore che indica se il PointData è compresso.<br/>            Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38).<br/>            Se non impostato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39). |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| image_attributes_id | int | r/w | Ottiene o imposta l'identificatore degli attributi dell'immagine<br/>            Un intero senza segno a 32 bit che specifica l'indice di un oggetto EmfPlusImageAttributes opzionale (sezione 2.2.1.5) nella EMF+ Object Table. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice di un oggetto EmfPlusImage (sezione 2.2.1.4) nella EMF+<br/>            Object Table, che specifica l'immagine da renderizzare. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta i dati del rettangolo<br/>            Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'immagine.<br/>            La porzione dell'immagine specificata dal campo SrcRect viene scalata per adattarsi a questo rettangolo. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta il rettangolo di origine<br/>            Un oggetto EmfPlusRectF che specifica una porzione dell'immagine da renderizzare.<br/>            La porzione dell'immagine specificata da questo rettangolo viene scalata per adattarsi al rettangolo di destinazione<br/>            specificato dal campo RectData. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Ottiene o imposta l'unità di origine<br/>            Intero a 32 bit con segno che specifica le unità del campo SrcRect.<br/>            Deve essere il membro UnitTypePixel dell'enumerazione UnitType (sezione 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

