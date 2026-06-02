---
title: "EmfPlusPathGradientBrushData Klasse"
type: docs
weight: 500
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | Initialisiert eine neue Instanz der EmfPlusPathGradientBrushData-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | Liest oder setzt die Begrenzung des Pfadverlauf-Pinsels, die entweder durch einen Pfad oder eine geschlossene kardinale Spline angegeben wird. <br/>            Wenn das BrushDataPath-Flag im BrushDataFlags-Feld gesetzt ist, MUSS dieses Feld ein EmfPlusBoundaryPathData-Objekt (Abschnitt 2.2.2.6) enthalten; <br/>            andernfalls MUSS dieses Feld ein EmfPlusBoundaryPointData-Objekt (Abschnitt 2.2.2.7) enthalten. |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Daten im OptionalData‑Feld angibt.<br/>            Dieser Wert MUSS aus BrushData‑Flags (Abschnitt 2.1.2.1) bestehen. Die folgenden Flags sind für einen Pfadverlauf-Pinsel relevant: |
| center_argb_32_color | int | r/w | Liest oder setzt ein EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des <br/>            Pfadverlauf-Pinsels angibt, also die Farbe, die am Mittelpunkt des Pinsels erscheint. <br/>            Die Farbe des Pinsels ändert sich allmählich von der Randfarbe <br/>            zur Mittelwertfarbe, wenn sie sich vom Rand zum Mittelpunkt bewegt. |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt ein EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des Pfadverlauf-Pinsels angibt, <br/>            also die Farbe, die am Mittelpunkt des Pinsels erscheint. Die Farbe des<br/>            Pinsels ändert sich allmählich von der Randfarbe zur Mittelwertfarbe, wenn sie<br/>            vom Rand zum Mittelpunkt bewegt. |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | Liest oder setzt ein optionales EmfPlusPathGradientBrushOptionalData-Objekt (Abschnitt 2.2.2.30), das <br/>            zusätzliche Daten für den Pfadverlauf-Pinsel angibt. <br/>            Der konkrete Inhalt dieses Feldes wird durch den Wert des BrushDataFlags-Feldes bestimmt. |
| surrounding_argb_32_colors | int[] | r/w | Liest oder setzt ein Array von SurroundingColorCount EmfPlusARGB-Objekten <br/>            , die die Farben für einzelne Punkte auf der Begrenzung des Pinsels festlegen. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl aus der WrapMode‑Aufzählung (Abschnitt 2.1.1.34), die angibt,<br/>            ob der Bereich außerhalb der Begrenzung des Pinsels gemalt werden soll. Beim Malen <br/>            außerhalb der Begrenzung gibt der Wrap‑Modus an, wie der Farbverlauf wiederholt wird. |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

Initialisiert eine neue Instanz der EmfPlusPathGradientBrushData-Klasse

