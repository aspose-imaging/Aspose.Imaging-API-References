---
title: "EmfPlusBrushDataFlags"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die BrushData-Flags geben Eigenschaften von Grafik-Pinseln an, einschließlich des Vorhandenseins optionaler Datenfelder."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

Die BrushData-Flags geben Eigenschaften von Grafik-Pinseln an, einschließlich des Vorhandenseins optionaler Datenfelder. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | Dieses Flag ist in [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata)-Objekten (Abschnitt 2.2.2.29) von Bedeutung. |
| [BrushDataTransform](#BrushDataTransform) | Dieses Flag ist in den Objekten [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (Abschnitt 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) und `EmfPlusTextureBrushData` (Abschnitt 2.2.2.45) von Bedeutung. |
| [BrushDataPresetColors](#BrushDataPresetColors) | Dieses Flag ist in den Objekten EmfPlusLinearGradientBrushData und EmfPlusPathGradientBrushData von Bedeutung. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | Dieses Flag ist in den Objekten EmfPlusLinearGradientBrushData und EmfPlusPathGradientBrushData von Bedeutung. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | Dieses Flag ist in den Objekten EmfPlusLinearGradientBrushData von Bedeutung. |
| [BrushDataFocusScales](#BrushDataFocusScales) | Dieses Flag ist in den Objekten EmfPlusPathGradientBrushData von Bedeutung. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | Dieses Flag ist in den Objekten EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData und EmfPlusTextureBrushData von Bedeutung. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | Dieses Flag ist in den Objekten EmfPlusTextureBrushData von Bedeutung. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


Dieses Flag ist in den Objekten [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (Abschnitt 2.2.2.29) von Bedeutung. Wenn gesetzt, muss ein [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) Objekt (Abschnitt 2.2.2.6) im Feld BoundaryData des Pinsel‑Datenobjekts angegeben werden. Wenn nicht gesetzt, muss ein [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) Objekt (Abschnitt 2.2.2.7) im Feld BoundaryData des Pinsel‑Datenobjekts angegeben werden.

--------------------

Grafikpinsel werden durch die Objekte [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush) spezifiziert.

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


Dieses Flag ist in den Objekten [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (Abschnitt 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) und `EmfPlusTextureBrushData` (Abschnitt 2.2.2.45) von Bedeutung. Wenn gesetzt, muss eine 2x3‑Welt‑zu‑Geräte‑Raum‑Transformationsmatrix im Feld OptionalData des Pinsel‑Datenobjekts angegeben werden.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


Dieses Flag ist in den Objekten EmfPlusLinearGradientBrushData und EmfPlusPathGradientBrushData von Bedeutung. Wenn gesetzt, muss ein [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) Objekt (Abschnitt 2.2.2.4) im Feld OptionalData des Pinsel‑Datenobjekts angegeben werden.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


Dieses Flag ist in den Objekten EmfPlusLinearGradientBrushData und EmfPlusPathGradientBrushData von Bedeutung. Wenn gesetzt, muss ein [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) Objekt (Abschnitt 2.2.2.5), das ein Mischmuster entlang eines horizontalen Farbverlaufs angibt, im Feld OptionalData des Pinsel‑Datenobjekts angegeben werden.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


Dieses Flag ist in den Objekten EmfPlusLinearGradientBrushData von Bedeutung. Wenn gesetzt, muss ein EmfPlusBlendFactors‑Objekt, das ein Mischmuster entlang eines vertikalen Farbverlaufs angibt, im Feld OptionalData des Pinsel‑Datenobjekts angegeben werden.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


Dieses Flag ist in den Objekten EmfPlusPathGradientBrushData von Bedeutung. Wenn gesetzt, muss ein [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) Objekt (Abschnitt 2.2.2.18) im Feld OptionalData des Pinsel‑Datenobjekts angegeben werden.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


Dieses Flag ist in den Objekten EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData und EmfPlusTextureBrushData von Bedeutung. Wenn gesetzt, muss der Pinsel bereits gamma‑korrigiert sein; das heißt, Helligkeit und Intensität der Ausgabe wurden korrigiert, um dem Eingabebild zu entsprechen.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


Dieses Flag ist in den Objekten EmfPlusTextureBrushData von Bedeutung. Wenn gesetzt, sollte keine Welt‑zu‑Geräte‑Raum‑Transformation auf den Texturpinsel angewendet werden.

