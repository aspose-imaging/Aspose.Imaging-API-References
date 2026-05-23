---
title: "EmfPlusBrushDataFlags Enumeration"
type: docs
weight: 30
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

Die BrushData‑Flags geben Eigenschaften von Grafikpinsel an, einschließlich des Vorhandenseins optionaler Datenfelder. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | Dieses Flag ist in EmfPlusLinearGradientBrushData- und EmfPlusPathGradientBrushData-Objekten von Bedeutung.<br/>            Wenn gesetzt, muss ein [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/)‑Objekt (Abschnitt 2.2.2.5), das ein Mischmuster entlang eines horizontalen Farbverlaufs angibt, im OptionalData‑Feld des Pinsel‑Datenobjekts angegeben werden. |
| BRUSH_DATA_BLEND_FACTORS_V | Dieses Flag ist in EmfPlusLinearGradientBrushData-Objekten von Bedeutung.<br/>            Wenn gesetzt, muss ein EmfPlusBlendFactors‑Objekt, das ein Mischmuster entlang eines vertikalen Farbverlaufs angibt, im OptionalData‑Feld des Pinsel‑Datenobjekts angegeben werden. |
| BRUSH_DATA_DO_NOT_TRANSFORM | Dieses Flag ist in EmfPlusTextureBrushData-Objekten von Bedeutung.<br/>            Wenn gesetzt, sollte keine Welt‑zu‑Geräte‑Raum‑Transformation auf den Texturpinsel angewendet werden. |
| BRUSH_DATA_FOCUS_SCALES | Dieses Flag ist in EmfPlusPathGradientBrushData-Objekten von Bedeutung.<br/>            Wenn gesetzt, muss ein [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/)‑Objekt (Abschnitt 2.2.2.18) im OptionalData‑Feld des Pinsel‑Datenobjekts angegeben werden. |
| BRUSH_DATA_IS_GAMMA_CORRECTED | Dieses Flag ist in EmfPlusLinearGradientBrushData-, EmfPlusPathGradientBrushData- und EmfPlusTextureBrushData-Objekten von Bedeutung.<br/>            Wenn gesetzt, muss der Pinsel bereits gamma‑korrigiert sein; das heißt, Helligkeit und Intensität der Ausgabe wurden korrigiert, um dem Eingabebild zu entsprechen. |
| BRUSH_DATA_PATH | Dieses Flag ist in [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/)‑Objekten (Abschnitt 2.2.2.29) von Bedeutung.<br/>            Wenn gesetzt, muss ein [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/)‑Objekt (Abschnitt 2.2.2.6) im BoundaryData‑Feld des Pinsel‑Datenobjekts angegeben werden.<br/>            Wenn nicht gesetzt, muss ein [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/)‑Objekt (Abschnitt 2.2.2.7) im BoundaryData‑Feld des Pinsel‑Datenobjekts angegeben werden. |
| BRUSH_DATA_PRESET_COLORS | Dieses Flag ist in EmfPlusLinearGradientBrushData- und EmfPlusPathGradientBrushData-Objekten von Bedeutung.<br/>            Wenn gesetzt, muss ein [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/)‑Objekt (Abschnitt 2.2.2.4) im OptionalData‑Feld des Pinsel‑Datenobjekts angegeben werden. |
| BRUSH_DATA_TRANSFORM | Dieses Flag ist in [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/)‑Objekten (Abschnitt 2.2.2.24), [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/)‑Objekten und [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/)‑Objekten (Abschnitt 2.2.2.45) von Bedeutung.<br/>            Wenn gesetzt, muss eine 2x3‑Welt‑zu‑Geräte‑Transformationsmatrix im OptionalData‑Feld des Pinsel‑Datenobjekts angegeben werden. |
