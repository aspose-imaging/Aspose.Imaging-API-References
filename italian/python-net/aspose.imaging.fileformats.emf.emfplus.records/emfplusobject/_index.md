---
title: "EmfPlusObject Classe"
type: docs
weight: 330
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | Inizializza una nuova istanza della classe [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| is_continuable | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è continuabile.<br/>            Indica che la definizione dell'oggetto continua nel successivo record EmfPlusObject<br/>            . Questa flag non è mai impostata nel record finale che definisce l'oggetto. |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | Ottiene o imposta un array di byte che contiene i dati per il tipo di oggetto specificato nel campo Flags. Il contenuto e il formato dei dati possono variare per ciascun tipo di oggetto. Vedere le definizioni individuali degli oggetti nella sezione 2.2.1 per informazioni aggiuntive. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice nella EMF+ Object Table da associare all'oggetto<br/>            creato da questo record. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | Ottiene o imposta il tipo dell'oggetto. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| total_object_size | int | r/w | Ottiene o imposta la dimensione totale dell'oggetto.<br/>            Se il record è continuabile, quando il bit di continuazione è impostato, questo campo<br/>            sarà presente. Gli oggetti continuabili hanno più record EMF+ che iniziano con<br/>            EmfPlusContineudObjectRecord. Ogni EmfPlusContinuedObjectRecord conterrà un<br/>            TotalObjectSize. Una volta letto il numero di byte indicato da TotalObjectSize, il successivo record EMF+<br/>            non sarà trattato come parte dell'oggetto continuabile. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

Inizializza una nuova istanza della classe [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

