---
title: "EmfPlusFillPie Classe"
type: docs
weight: 260
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---

**Summary:** The EmfPlusFillPie record specifies filling a section of the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusFillPie(source)](#EmfPlusFillPie_source_1) | Inizializza una nuova istanza della classe [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Ottiene o imposta l'identificatore del pennello<br/>            Un intero senza segno a 32 bit che definisce il pennello, il cui contenuto <br/>            è determinato dal bit S nel campo Flags. |
| compresso | bool | r/w | Ottiene o imposta un valore che indica se il PointData è compresso.<br/>            Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38).<br/>            Se non impostato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39). |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| is_color | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è un colore.<br/>            Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). <br/>            Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella tabella degli oggetti EMF+. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta i dati del rettangolo<br/> Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'<br/> ellisse che contiene la fetta di torta. Questo rettangolo definisce la posizione, le dimensioni, <br/> e la forma della torta. Il tipo di oggetto in questo campo è specificato dal valore <br/> del campo Flags. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| start_angle | float | r/w | Ottiene o imposta l'angolo di partenza<br/> Un valore a virgola mobile a 32 bit, non negativo, che specifica l'angolo tra l'asse x e il punto di partenza della fetta di torta. Qualsiasi valore è accettabile, ma DEVE essere interpretato modulo 360, con il risultato utilizzato nell'intervallo <br/> da 0,0 inclusi a 360,0 esclusi. |
| sweep_angle | float | r/w | Ottiene o imposta l'angolo di sweep<br/> Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco che definisce <br/> la fetta di torta da disegnare, come angolo in gradi misurato dal punto di partenza <br/> definito dal valore StartAngle. Qualsiasi valore è accettabile, ma DEVE essere limitato <br/> a -360,0 fino a 360,0 inclusi. Un valore positivo indica che lo sweep è definito <br/> in senso orario, e un valore negativo indica che lo sweep è definito <br/> in senso antiorario. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusFillPie(source) {#EmfPlusFillPie_source_1}


```
 EmfPlusFillPie(source) 
```

Inizializza una nuova istanza della classe [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

