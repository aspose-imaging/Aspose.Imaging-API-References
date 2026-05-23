---
title: "Klasse EmfPlusLinearGradientBrushOptionalData"
type: docs
weight: 450
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | Initialisiert eine neue Instanz der Klasse EmfPlusLinearGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Liefert oder setzt ein optionales Blend‑Muster für den Linear‑Gradient‑Brush. Wenn dieses Feld vorhanden ist, <br/>            MUSS es entweder ein EmfPlusBlendColors‑Objekt (Abschnitt 2.2.2.4) enthalten, <br/>            oder ein oder zwei EmfPlusBlendFactors‑Objekte (Abschnitt 2.2.2.5), <br/>            aber es DARF NICHT beide enthalten. Die nachstehende Tabelle zeigt die gültigen Kombinationen von <br/>            EmfPlusLinearGradientBrushData‑BrushData‑Flags und den entsprechenden Blend‑Mustern:<br/>            EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Liefert das Blend‑Muster als Blend‑Faktoren h. |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Liefert das Blend‑Muster als Blend‑Faktoren v. |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | Liefert das Mischmuster als voreingestellte Farben. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt ein optionales EmfPlusTransformMatrix-Objekt (Abschnitt 2.2.2.47), das eine<br/>            Welt-zu-Geräte-Raum-Transformation für den linearen Farbverlauf-Pinsel angibt. <br/>            Dieses Feld MUSS vorhanden sein, wenn das BrushDataTransform-Flag im<br/>            BrushDataFlags-Feld des EmfPlusLinearGradientBrushData-Objekts gesetzt ist. |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

Initialisiert eine neue Instanz der Klasse EmfPlusLinearGradientBrushOptionalData

