---
title: "Classe EmfLogBrushEx"
type: docs
weight: 120
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---

**Summary:** The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfLogBrushEx()](#EmfLogBrushEx__1) | Inizializza una nuova istanza della classe EmfLogBrushEx |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Ottiene o imposta un oggetto WMF ColorRef a 32 bit ([MS-WMF] sezione 2.2.2.8) che specifica un<br/>colore. L'interpretazione di questo campo dipende dal valore di BrushStyle, come spiegato nella<br/>tabella seguente. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Ottiene o imposta un campo senza segno a 32 bit che contiene i dati di tratteggio del pennello. La sua <br/>interpretazione dipende dal valore di BrushStyle, |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica lo stile del pennello. Il valore DEVE <br/>essere un'enumerazione dalla enumerazione WMF BrushStyle ([MS-WMF] sezione 2.1.1.4). I valori di stile <br/>supportati in questa struttura sono elencati più avanti in questa sezione. Lo stile BS_NULL <br/>DOVREBBE essere usato per specificare un pennello che non ha effetto. |


### Constructor: EmfLogBrushEx() {#EmfLogBrushEx__1}


```
 EmfLogBrushEx() 
```

Inizializza una nuova istanza della classe EmfLogBrushEx

