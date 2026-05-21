---
title: "EmfPlusBrushDataFlags"
second_title: "Aspose.Imaging för Java API-referens"
description: "BrushData-flaggorna specificerar egenskaper för grafikpenslar inklusive förekomsten av valfria datafält."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

BrushData-flaggorna specificerar egenskaper för grafikpenslar, inklusive förekomsten av valfria datafält. Dessa flaggor kan kombineras för att specificera flera alternativ.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | Denna flagga är meningsfull i [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata)-objekt (avsnitt 2.2.2.29). |
| [BrushDataTransform](#BrushDataTransform) | Denna flagga är meningsfull i [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) objekt (avsnitt 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) objekt, och `EmfPlusTextureBrushData` objekt (avsnitt 2.2.2.45). |
| [BrushDataPresetColors](#BrushDataPresetColors) | Denna flagga är meningsfull i EmfPlusLinearGradientBrushData och EmfPlusPathGradientBrushData objekt. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | Denna flagga är meningsfull i EmfPlusLinearGradientBrushData och EmfPlusPathGradientBrushData objekt. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | Denna flagga är meningsfull i EmfPlusLinearGradientBrushData objekt. |
| [BrushDataFocusScales](#BrushDataFocusScales) | Denna flagga är meningsfull i EmfPlusPathGradientBrushData objekt. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | Denna flagga är meningsfull i EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData och EmfPlusTextureBrushData objekt. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | Denna flagga är meningsfull i EmfPlusTextureBrushData objekt. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


Denna flagga är meningsfull i [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) objekt (avsnitt 2.2.2.29). Om den är satt måste ett [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) objekt (avsnitt 2.2.2.6) specificeras i fältet BoundaryData i penseldatatobjektet. Om den är avmarkerad måste ett [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) objekt (avsnitt 2.2.2.7) specificeras i fältet BoundaryData i penseldatatobjektet.

--------------------

Grafikpenslar specificeras av [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush) objekt

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


Denna flagga är meningsfull i [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) objekt (avsnitt 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) objekt, och `EmfPlusTextureBrushData` objekt (avsnitt 2.2.2.45). Om den är satt måste en 2x3 världsrum-till-enhetstransformmatris specificeras i fältet OptionalData i penseldatatobjektet.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


Denna flagga är meningsfull i EmfPlusLinearGradientBrushData och EmfPlusPathGradientBrushData objekt. Om den är satt måste ett [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) objekt (avsnitt 2.2.2.4) specificeras i fältet OptionalData i penseldatatobjektet.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


Denna flagga är meningsfull i EmfPlusLinearGradientBrushData och EmfPlusPathGradientBrushData objekt. Om den är satt måste ett [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) objekt (avsnitt 2.2.2.5) som specificerar ett blandningsmönster längs en horisontell gradient specificeras i fältet OptionalData i penseldatatobjektet.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


Denna flagga är meningsfull i EmfPlusLinearGradientBrushData objekt. Om den är satt måste ett EmfPlusBlendFactors-objekt som specificerar ett blandningsmönster längs en vertikal gradient specificeras i fältet OptionalData i penseldatatobjektet.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


Denna flagga är meningsfull i EmfPlusPathGradientBrushData objekt. Om den är satt måste ett[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) objekt (avsnitt 2.2.2.18) specificeras i fältet OptionalData i penseldatatobjektet.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


Denna flagga är meningsfull i EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData och EmfPlusTextureBrushData objekt. Om den är satt måste penseln redan vara gamma-korrigerad; det vill säga, utgångens ljusstyrka och intensitet har korrigerats för att matcha inmatningsbilden.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


Denna flagga är meningsfull i EmfPlusTextureBrushData objekt. Om den är satt bör ingen världsrum-till-enhetstransform tillämpas på texturpenseln.

