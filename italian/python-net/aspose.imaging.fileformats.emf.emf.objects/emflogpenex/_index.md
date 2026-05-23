---
title: "Classe EmfLogPenEx"
type: docs
weight: 190
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

**Summary:** The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Inheritance:** EmfBasePen

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfLogPenEx()](#EmfLogPenEx__1) | Inizializza una nuova istanza della classe EmfLogPenEx |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8). L'interpretazione di questo<br/>            campo dipende dal valore BrushStyle, come mostrato nella tabella più avanti in questa sezione. |
| brush_dib_pattern | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Ottiene o imposta il pattern dib del pennello. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Ottiene o imposta il pattern a trama del pennello. La definizione di questo campo dipende dal <br/>            valore BrushStyle, come mostrato nella tabella più avanti in questa sezione. |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica uno stile di pennello per la penna dalla<br/>            enumerazione WMF BrushStyle ([MS-WMF] sezione 2.1.1.4). <br/>            Se il tipo di penna nel campo PenStyle è PS_GEOMETRIC, questo valore DEVE essere BS_SOLID o BS_HATCHED. Il valore di questo campo può essere BS_NULL, ma solo se lo <br/>            stile di linea specificato in PenStyle è PS_NULL. Lo stile BS_NULL DOVREBBE essere usato <br/>            per specificare un pennello che non ha effetto. |
| num_style_entities | int | r | Ottiene il numero di elementi nell'array specificato nel campo StyleEntry. <br/>            Questo valore DOVREBBE essere zero se PenStyle non specifica PS_USERSTYLE. |
| pen_style | [EmfPenStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/) | r/w | Ottiene o imposta lo stile della penna |
| style_entry | int[] | r/w | Ottiene o imposta un array opzionale di interi senza segno a 32 bit che definisce le lunghezze di <br/>            tratti e spazi nella linea disegnata da questa penna, quando il valore di PenStyle <br/>            è lo stile di linea PS_USERSTYLE per la penna. L'array contiene un numero di <br/>            voci specificato da NumStyleEntries, ma viene usato come se si ripetesse indefinitamente <br/>            La prima voce dell'array specifica la lunghezza del primo tratto. La seconda <br/>            voce specifica la lunghezza del primo spazio. Successivamente, le lunghezze di tratti e spazi si alternano.<br/>            Se il tipo di penna nel campo PenStyle è PS_GEOMETRIC, le lunghezze sono specificate in <br/>            unità logiche; altrimenti, le lunghezze sono specificate in unità di dispositivo. |
| width | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la larghezza della linea disegnata dalla penna.<br/>            Se il tipo di penna nel campo PenStyle è PS_GEOMETRIC, questo valore è la larghezza in<br/>            unità logiche; altrimenti, la larghezza è specificata in unità di dispositivo. <br/>            Se il tipo di penna nel campo PenStyle è PS_COSMETIC, questo valore DEVE essere 0x00000001. |


### Constructor: EmfLogPenEx() {#EmfLogPenEx__1}


```
 EmfLogPenEx() 
```

Inizializza una nuova istanza della classe EmfLogPenEx

