---
title: "EmfLogBrushEx Klasse"
type: docs
weight: 120
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---

**Summary:** The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfLogBrushEx()](#EmfLogBrushEx__1) | Initialisiert eine neue Instanz der EmfLogBrushEx Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Liest oder setzt ein 32‑Bit‑WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8), das eine<br/>
            Farbe angibt. Die Interpretation dieses Feldes hängt vom Wert von BrushStyle ab, wie in der<br/>
            folgenden Tabelle erläutert wird. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Liest oder setzt ein 32‑Bit‑vorzeichenloses Feld, das die Schraffurdaten des Pinsels enthält. Seine <br/>
            Interpretation hängt vom Wert von BrushStyle ab, |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der den Pinselstil angibt. Der Wert MUSS <br/>
            eine Aufzählung aus der WMF BrushStyle‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.4) sein. Die Stilwerte <br/>
            die in dieser Struktur unterstützt werden, sind später in diesem Abschnitt aufgeführt. Der BS_NULL‑Stil <br/>
            SOLLTE verwendet werden, um einen Pinsel zu spezifizieren, der keine Wirkung hat. |


### Constructor: EmfLogBrushEx() {#EmfLogBrushEx__1}


```
 EmfLogBrushEx() 
```

Initialisiert eine neue Instanz der EmfLogBrushEx Klasse

