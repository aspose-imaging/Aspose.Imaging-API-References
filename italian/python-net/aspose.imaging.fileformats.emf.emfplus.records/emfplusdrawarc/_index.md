---
title: "Classe EmfPlusDrawArc"
type: docs
weight: 70
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_size | int | r/w | Ottiene o imposta la dimensione dei dati.<br/>            Un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di<br/>            byte dei dati specifici del record che seguono.<br/>            Per questo tipo di record, il valore DEVE essere uno dei seguenti:<br/>            0x00000010 Se il bit C è impostato nel campo Flags.<br/>            0x00000018 Se il bit C è cancellato nel campo Flags. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella<br/>            Tabella Oggetti EMF+ per disegnare l'arco. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| rect_float | bool | r/w | Ottiene o imposta un valore che indica se i dati contengono <br/>            record EmfPlusRectF o EmfPlusRect<br/>            Questo bit indica se i dati nel campo RectData sono compressi.<br/>            Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38).<br/>            Se cancellato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39). |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta i dati del rettangolo<br/>            Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione<br/>            dell'ellisse collineare con l'arco. Questo rettangolo definisce la<br/>            posizione, le dimensioni e la forma dell'arco. Il tipo di oggetto in questo campo è<br/>            specificato dal valore del campo Flags. |
| dimensione | int | r/w | Ottiene o imposta la dimensione.<br/>            Un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di<br/>            byte dell'intero record, inclusa l'intestazione del record di 12 byte e<br/>            i dati specifici del record. Per questo tipo di record, il valore DEVE essere uno dei seguenti:<br/>            0x0000001C  Se il bit C è impostato nel campo Flags.<br/>            0x00000024  Se il bit C è cancellato nel campo Flags. |
| start_angle | float | r/w | Ottiene o imposta l'angolo di partenza<br/>            Un valore a virgola mobile non negativo a 32 bit che specifica l'angolo tra<br/>            l'asse x e il punto iniziale dell'arco. Qualsiasi valore è accettabile,<br/>            ma DEVE essere interpretato modulo 360, con il risultato utilizzato compreso<br/>            nell'intervallo da 0,0 inclusi a 360,0 esclusi. |
| sweep_angle | float | r/w | Ottiene o imposta l'angolo di sweep<br/>            Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco da disegnare,<br/>            come angolo in gradi misurato dal punto di partenza definito dal valore<br/>            StartAngle. Qualsiasi valore è accettabile, ma DEVE essere limitato a -360,0<br/>            fino a 360,0 inclusi. Un valore positivo indica che lo sweep è definito in<br/>            senso orario, e un valore negativo indica che lo sweep è<br/>            definito in senso antiorario. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

