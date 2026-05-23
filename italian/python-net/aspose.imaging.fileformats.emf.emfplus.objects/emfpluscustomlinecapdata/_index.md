---
title: "Classe EmfPlusCustomLineCapData"
type: docs
weight: 270
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | Inizializza una nuova istanza della classe EmfPlusCustomLineCapData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore dell'enumerazione LineCap (sezione 2.1.1.18) <br/>            su cui si basa il cap di linea personalizzato. |
| base_inset | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la distanza tra l'inizio <br/>            del cap di linea e la fine della linea. |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta un oggetto EmfPlusPointF che attualmente non è utilizzato. DEVE essere impostato a {0.0, 0.0}. |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | Ottiene o imposta un oggetto opzionale EmfPlusCustomLineCapOptionalData (sezione 2.2.2.14)<br/>             che specifica dati aggiuntivi per il cap di linea grafica personalizzato. Il contenuto specifico di questo campo è determinato <br/>            dal valore del campo CustomLineCapDataFlags. |
| stroke_end_cap | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica quale <br/>            cap di linea deve essere usato alla fine della linea da disegnare. |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta un oggetto EmfPlusPointF che attualmente non è utilizzato. DEVE essere impostato a {0.0, 0.0}. |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineJoin <br/>            (sezione 2.1.1.19), che indica come unire due linee disegnate dalla stessa penna i cui estremi si incontrano. All'intersezione dei due estremi delle linee, <br/>            una giunzione di linea rende la connessione più continua. |
| stroke_miter_limit | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che contiene il limite dello spessore<br/>             della giunzione in un angolo a spigolo impostando il rapporto massimo consentito<br/>             tra la lunghezza dello spigolo e la larghezza della linea. |
| stroke_start_cap | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica il <br/>            cap di linea usato all'inizio della linea da disegnare |
| width_scale | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la quantità di cui <br/>             scalare il cap di linea personalizzato rispetto alla larghezza dell'oggetto EmfPlusPen <br/>            (sezione 2.2.1.7) utilizzato per disegnare le linee. |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

Inizializza una nuova istanza della classe EmfPlusCustomLineCapData

