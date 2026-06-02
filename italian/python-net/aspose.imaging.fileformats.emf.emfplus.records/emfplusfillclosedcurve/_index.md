---
title: "EmfPlusFillClosedCurve Classe"
type: docs
weight: 230
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | Inizializza una nuova istanza della classe [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Ottiene o imposta l'identificatore del pennello<br/>            Un intero senza segno a 32 bit che specifica l'EmfPlusBrush, il cui contenuto è <br/>            determinato dal bit S nel campo Flags. Questo pennello è usato per riempire l'interno <br/>            della spline cardinale chiusa. |
| compressed | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) è compresso.<br/>            Questo bit indica se il campo PointData specifica dati compressi.<br/>            Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit.<br/>            ----------------------<br/>            Un'operazione di riempimento "winding" riempie le aree secondo la regola della "parità pari-dispari". <br/>            Secondo questa regola, un punto di prova può essere determinato come interno o esterno a una <br/>            curva chiusa come segue: Traccia una linea dal punto di prova a un punto distante <br/>            dalla curva. Se quella linea attraversa la curva un numero dispari di volte, il punto <br/>            di prova è interno alla curva; altrimenti, il punto di prova è esterno alla curva.<br/>            ---------------------<br/>            Un'operazione di riempimento "alternate" riempie le aree secondo la regola del "non-zero".<br/>             Secondo questa regola, un punto di prova può essere determinato come interno o esterno <br/>            a una curva chiusa come segue: Traccia una linea da un punto di prova a un punto <br/>            distante dalla curva. Conta il numero di volte in cui la curva attraversa la linea di prova <br/>            da sinistra a destra, e conta il numero di volte in cui la curva attraversa la <br/>            linea di prova da destra a sinistra. Se questi due numeri sono uguali, il punto di prova <br/>            è esterno alla curva; altrimenti, il punto di prova è interno alla curva. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| is_color | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è a colori.<br/>            Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1).<br/>            Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush <br/>            (sezione 2.2.1.1) nella Tabella Oggetti EMF+. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta i dati dei punti<br/>            Un array di Count punti che specificano i punti finali delle linee che definiscono la spline. <br/>            In una spline cardinale chiusa, la curva continua attraverso l'ultimo punto nell'array PointData <br/>            e si collega con il primo punto dell'array. |
| relative | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) è relativo.<br/>            Questo bit indica se il campo PointData specifica posizioni relative o assolute.<br/>            Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è<br/>            relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso <br/>            del primo elemento in PointData, si presume una posizione precedente alle coordinate (0,0). <br/>            Se non impostato, PointData specifica posizioni assolute secondo il flag C.<br/>            Nota: se questo flag è impostato, il flag C (sopra) è indefinito e DEVE essere ignorato. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| tensione | float | r/w | Ottiene o imposta la tensione<br/>            Un valore a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre passa <br/>            attraverso i punti. Un valore di 0.0 indica che la spline è una sequenza di linee rette. Man mano che il valore aumenta, la curva diventa più arrotondata. Per ulteriori informazioni, <br/>            vedi [SPLINE77] e [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |
| winding | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) è di tipo winding.<br/>            Questo bit indica come eseguire l'operazione di riempimento.<br/>            Se impostato, il riempimento è un riempimento "winding". Se non impostato, il riempimento è un riempimento "alternate". |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

Inizializza una nuova istanza della classe [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

