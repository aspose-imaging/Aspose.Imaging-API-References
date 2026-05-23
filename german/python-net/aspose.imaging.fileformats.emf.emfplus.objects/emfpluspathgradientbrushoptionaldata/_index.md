---
title: "EmfPlusPathGradientBrushOptionalData Klasse"
type: docs
weight: 510
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | Initialisiert eine neue Instanz der EmfPlusPathGradientBrushOptionalData‑Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Liest oder schreibt ein optionales Blend‑Muster für den Pfad‑Verlaufs‑Pinsel. Wenn dieses Feld<br/>            vorhanden ist, MUSS es entweder ein EmfPlusBlendColors‑Objekt (Abschnitt 2.2.2.4) <br/>            oder ein EmfPlusBlendFactors‑Objekt (Abschnitt 2.2.2.5) enthalten, darf jedoch NICHT beide enthalten. <br/>            Die nachstehende Tabelle zeigt die gültigen Kombinationen von EmfPlusPathGradientBrushData<br/>            BrushData‑Flags und den entsprechenden Blend‑Mustern. |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | Liest oder schreibt ein optionales EmfPlusFocusScaleData‑Objekt (Abschnitt 2.2.2.18), das Fokus‑Skalen für den Pfad‑Verlaufs‑Pinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das<br/>            BrushDataFocusScales‑Flag im BrushDataFlags‑Feld des <br/>            EmfPlusPathGradientBrushData‑Objekts gesetzt ist. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder schreibt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Welt‑zu‑Geräte‑Raum‑Transformation für den Pfad‑Verlaufs‑Pinsel angibt. <br/>            Dieses Feld MUSS vorhanden sein, wenn das BrushDataTransform‑Flag im BrushDataFlags‑Feld des EmfPlusPathGradientBrushData‑Objekts gesetzt ist. |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

Initialisiert eine neue Instanz der EmfPlusPathGradientBrushOptionalData‑Klasse

