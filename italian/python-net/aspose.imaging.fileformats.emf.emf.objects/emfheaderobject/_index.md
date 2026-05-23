---
title: "Classe EmfHeaderObject"
type: docs
weight: 110
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---

**Summary:** The Header object defines the EMF metafile header. It specifies properties of the device on which the image in the metafile was created.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfHeaderObject()](#EmfHeaderObject__1) | Inizializza una nuova istanza della classe [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica i limiti rettangolari inclusivi‑inclusivi <br/>            in unità dispositivo del più piccolo rettangolo che può essere disegnato attorno all'immagine memorizzata nel <br/>            metafile |
| byte | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione del metafile, in byte. |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Ottiene o imposta un oggetto WMF SizeL ([MS-WMF] sezione 2.2.2.22) che specifica le dimensioni del dispositivo di riferimento, in pixel |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL che specifica le dimensioni rettangolari inclusive‑inclusive, in unità di 0,01 millimetro <br/>            , di un rettangolo che circonda l'immagine memorizzata nel metafile |
| maniglie | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica il numero di oggetti grafici che saranno usati durante l'elaborazione del metafile |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Ottiene o imposta un oggetto WMF SizeL che specifica le dimensioni del dispositivo di riferimento, in millimetri |
| n_desription | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nell'array <br/>            che contiene la descrizione del contenuto del metafile. Questo è zero se non esiste una stringa di descrizione. |
| n_pal_entries | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci nella palette del metafile <br/>            . La palette si trova nel record EMR_EOF |
| off_description | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset dall'inizio di questo <br/>            record all'array che contiene la descrizione del contenuto del metafile |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la firma del record. Questo DEVE essere ENHMETA_SIGNATURE, <br/>            dall'enumerazione FormatSignature (sezione 2.1.14). |
| record | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di record nel metafile |
| riservato | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che DEVE essere 0x0000 e DEVE essere ignorato |
| valid | bool | r | Restituisce un valore che indica se questo [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) è valido. |
| versione | int | r/w | Ottiene o imposta Version (4 byte): Un intero senza segno a 32 bit che specifica l'interoperabilità del metafile EMF. Questo DOVREBBE essere 0x00010000 |


### Constructor: EmfHeaderObject() {#EmfHeaderObject__1}


```
 EmfHeaderObject() 
```

Inizializza una nuova istanza della classe [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/).

