---
title: "Classe EmfPlusSetTsGraphics"
type: docs
weight: 580
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

**Summary:** The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_1) | Inizializza una nuova istanza della classe [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering delle linee,<br/>            incluso il tipo di anti-aliasing delle linee. Deve essere definito nell'enumerazione SmoothingMode<br/>            (sezione 2.1.1.28). |
| basic_vga_colors | bool | r | Ottiene un valore che indica se [basic vga colors].<br/>            Se impostato, la tavolozza contiene solo i colori VGA di base. |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica come i colori di origine sono<br/>            combinati con i colori di sfondo. Deve essere un valore dell'enumerazione CompositingMode<br/>            (sezione 2.1.1.5). |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica il grado di<br/>            levigatura da applicare a linee, curve e ai bordi delle aree riempite per farle apparire più<br/>            continue o nettamente definite. Deve essere un valore dell'enumerazione CompositingQuality (sezione 2.1.1.6). |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica come viene eseguita la scalatura, inclusi allungamento<br/>            e riduzione. Deve essere un valore dell'enumerazione FilterType (sezione 2.1.1.11). |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| have_palette | bool | r | Ottiene un valore che indica se [have palette].<br/>            Se impostato, questo record contiene un oggetto EmfPlusPalette (sezione 2.2.2.28) nel<br/>            campo Palette che segue i dati dello stato grafico. |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Ottiene o imposta un oggetto EmfPlusPalette opzionale. |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità complessiva dell'immagine<br/>            e del processo di rendering del testo. Deve essere un valore dell'enumerazione PixelOffsetMode (sezione 2.1.1.26). |
| render_origin_x | int | r/w | Ottiene o imposta un intero con segno a 16 bit, che è la coordinata orizzontale dell'<br/>            origine per il rendering di retini di mezzitoni e dithering. |
| render_origin_y | int | r/w | Ottiene o imposta un intero con segno a 16 bit, che è la coordinata verticale dell'origine<br/>            per il rendering di retini di mezzitoni e dithering. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| text_contrast | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma<br/>            utilizzato per il rendering di testo anti-aliasing e ClearType. Questo valore DEVE essere nell'intervallo da 0 a 12, inclusi. |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering del testo<br/>            , incluso il tipo di anti-aliasing del testo. Deve essere definito nell'enumerazione TextRenderingHint<br/>            (sezione 2.1.1.32). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta un oggetto EmfPlusTransformMatrix a 192 bit (sezione 2.2.2.47) che<br/>            specifica le trasformazioni dallo spazio mondo allo spazio dispositivo. |


### Constructor: EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_1}


```
 EmfPlusSetTsGraphics(source) 
```

Inizializza una nuova istanza della classe [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

