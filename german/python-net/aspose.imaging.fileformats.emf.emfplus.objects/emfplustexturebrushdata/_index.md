---
title: "Klasse EmfPlusTextureBrushData"
type: docs
weight: 680
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | Initialisiert eine neue Instanz der Klasse EmfPlusTextureBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Liefert oder setzt eine 32‑Bit‑unsigned Ganzzahl, die die Daten im Feld OptionalData angibt. <br/>            Dieser Wert MUSS aus BrushData‑Flags (Abschnitt 2.1.2.1) zusammengesetzt sein. <br/>            Die folgenden Flags sind für einen Texture‑Brush relevant<br/>            BrushDataTransform<br/>            BrushDataIsGammaCorrected<br/>            BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | Liefert oder setzt ein optionales EmfPlusTextureBrushOptionalData‑Objekt (Abschnitt 2.2.2.46), das <br/>            zusätzliche Daten für den Texture‑Brush angibt. Der konkrete Inhalt dieses Feldes wird durch den Wert des BrushDataFlags‑Feldes bestimmt. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Liefert oder setzt eine 32‑Bit‑signed Ganzzahl aus der WrapMode‑Aufzählung (Abschnitt 2.1.1.34) <br/>            die angibt, wie das Texturbild über eine Form wiederholt wird, wenn das <br/>            Bild kleiner ist als die zu füllende Fläche. |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

Initialisiert eine neue Instanz der Klasse EmfPlusTextureBrushData

