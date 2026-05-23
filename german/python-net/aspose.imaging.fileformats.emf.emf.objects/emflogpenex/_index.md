---
title: "EmfLogPenEx Klasse"
type: docs
weight: 190
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

**Summary:** The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Inheritance:** EmfBasePen

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfLogPenEx()](#EmfLogPenEx__1) | Initialisiert eine neue Instanz der EmfLogPenEx Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Liest oder setzt ein WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8). Die Interpretation dieses<br/>            Feldes hängt vom BrushStyle‑Wert ab, wie in der späteren Tabelle dieses Abschnitts gezeigt. |
| brush_dib_pattern | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt das Brush‑DIB‑Muster. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Liest oder setzt das Brush‑Schraffurmuster. Die Definition dieses Feldes hängt vom <br/>            BrushStyle‑Wert ab, wie in der späteren Tabelle dieses Abschnitts gezeigt. |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die einen Pinselstil für den Stift aus der<br/>            WMF BrushStyle‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.4) angibt. <br/>            Ist der Stifttyp im PenStyle‑Feld PS_GEOMETRIC, MUSS dieser Wert entweder <br/>            BS_SOLID oder BS_HATCHED sein. Der Wert dieses Feldes kann BS_NULL sein, jedoch nur, wenn der <br/>            Linienstil im PenStyle PS_NULL ist. Der BS_NULL‑Stil SOLLTE verwendet werden, <br/>            um einen Pinsel zu spezifizieren, der keine Wirkung hat. |
| num_style_entities | int | r | Liest die Anzahl der Elemente im Array, das im StyleEntry‑Feld angegeben ist. <br/>            Dieser Wert SOLLTE null sein, wenn PenStyle nicht PS_USERSTYLE angibt. |
| pen_style | [EmfPenStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/) | r/w | Liest oder setzt den Stiftstil |
| style_entry | int[] | r/w | Liest oder setzt ein optionales Array von 32‑Bit vorzeichenlosen Ganzzahlen, das die Längen von <br/>            Strichen und Lücken in der vom Stift gezeichneten Linie definiert, wenn der Wert von PenStyle <br/>            PS_USERSTYLE ist. Das Array enthält eine Anzahl von <br/>            Einträgen, die durch NumStyleEntries angegeben wird, wird jedoch so verwendet, als würde es unendlich wiederholt. <br/>            Der erste Eintrag im Array gibt die Länge des ersten Strichs an. Der zweite <br/>            Eintrag gibt die Länge der ersten Lücke an. Danach wechseln sich Längen von Strichen und Lücken ab.<br/>            Ist der Stifttyp im PenStyle‑Feld PS_GEOMETRIC, werden die Längen in logischen Einheiten angegeben; andernfalls werden die Längen in Geräte‑Einheiten angegeben. |
| width | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Breite der vom Stift gezeichneten Linie angibt.<br/>            Ist der Stifttyp im PenStyle‑Feld PS_GEOMETRIC, ist dieser Wert die Breite in<br/>            logischen Einheiten; andernfalls wird die Breite in Geräte‑Einheiten angegeben. <br/>            Ist der Stifttyp im PenStyle‑Feld PS_COSMETIC, MUSS dieser Wert 0x00000001 sein. |


### Constructor: EmfLogPenEx() {#EmfLogPenEx__1}


```
 EmfLogPenEx() 
```

Initialisiert eine neue Instanz der EmfLogPenEx Klasse

