---
title: "Classe EmfHeaderExtension1"
type: docs
weight: 90
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---

**Summary:** The HeaderExtension1 object defines the first extension to the EMF metafile header. <br/>            It adds support for a PixelFormatDescriptor object (section 2.2.22) and OpenGL <br/>            [OPENGL] records (section 2.3.9).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1__1) | Inizializza una nuova istanza della classe EmfHeaderExtension1 |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| b_open_gl | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che indica se i comandi OpenGL sono presenti nel metafile.<br/>0x00000000 I record OpenGL non sono presenti nel metafile.<br/>0x00000001 I record OpenGL sono presenti nel metafile. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica i limiti rettangolari inclusivi‑inclusivi <br/>            in unità dispositivo del più piccolo rettangolo che può essere disegnato attorno all'immagine memorizzata nel <br/>            metafile |
| byte | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione del metafile, in byte. |
| cb_pixel_format | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dell'oggetto PixelFormatDescriptor. <br/>Questo DEVE essere 0x00000000 se non è impostato alcun formato pixel. |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Ottiene o imposta un oggetto WMF SizeL ([MS-WMF] sezione 2.2.2.22) che specifica le dimensioni del dispositivo di riferimento, in pixel |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL che specifica le dimensioni rettangolari inclusive‑inclusive, in unità di 0,01 millimetro <br/>            , di un rettangolo che circonda l'immagine memorizzata nel metafile |
| maniglie | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica il numero di oggetti grafici che saranno usati durante l'elaborazione del metafile |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Ottiene o imposta un oggetto WMF SizeL che specifica le dimensioni del dispositivo di riferimento, in millimetri |
| n_desription | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nell'array <br/>            che contiene la descrizione del contenuto del metafile. Questo è zero se non esiste una stringa di descrizione. |
| n_pal_entries | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci nella palette del metafile <br/>            . La palette si trova nel record EMR_EOF |
| off_description | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset dall'inizio di questo <br/>            record all'array che contiene la descrizione del contenuto del metafile |
| off_pixel_format | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset all'oggetto PixelFormatDescriptor.<br/>Questo DEVE essere 0x00000000 se non è impostato alcun formato pixel. |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la firma del record. Questo DEVE essere ENHMETA_SIGNATURE, <br/>            dall'enumerazione FormatSignature (sezione 2.1.14). |
| record | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di record nel metafile |
| riservato | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che DEVE essere 0x0000 e DEVE essere ignorato |
| valid | bool | r | Restituisce un valore che indica se questo [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) è valido. |
| versione | int | r/w | Ottiene o imposta Version (4 byte): Un intero senza segno a 32 bit che specifica l'interoperabilità del metafile EMF. Questo DOVREBBE essere 0x00010000 |


### Constructor: EmfHeaderExtension1() {#EmfHeaderExtension1__1}


```
 EmfHeaderExtension1() 
```

Inizializza una nuova istanza della classe EmfHeaderExtension1

