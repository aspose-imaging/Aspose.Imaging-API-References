---
title: "EmfPlusBrushDataFlags"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los indicadores BrushData especifican propiedades de los pinceles gráficos, incluyendo la presencia de campos de datos opcionales."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

Los indicadores BrushData especifican propiedades de los pinceles gráficos, incluyendo la presencia de campos de datos opcionales. Estos indicadores pueden combinarse para especificar múltiples opciones.
## Campos

| Campo | Descripción |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | Este indicador es significativo en objetos [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (sección 2.2.2.29). |
| [BrushDataTransform](#BrushDataTransform) | Esta bandera es significativa en objetos [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (sección 2.2.2.24), objetos [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) y objetos `EmfPlusTextureBrushData` (sección 2.2.2.45). |
| [BrushDataPresetColors](#BrushDataPresetColors) | Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData y EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData y EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData. |
| [BrushDataFocusScales](#BrushDataFocusScales) | Esta bandera es significativa en objetos EmfPlusPathGradientBrushData. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData y EmfPlusTextureBrushData. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | Esta bandera es significativa en objetos EmfPlusTextureBrushData. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


Esta bandera es significativa en objetos [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (sección 2.2.2.29). Si está establecida, se DEBE especificar un objeto [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) (sección 2.2.2.6) en el campo BoundaryData del objeto de datos del pincel. Si no está establecida, se DEBE especificar un objeto [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) (sección 2.2.2.7) en el campo BoundaryData del objeto de datos del pincel.

--------------------

Los pinceles gráficos se especifican mediante objetos [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush) objetos

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


Esta bandera es significativa en objetos [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (sección 2.2.2.24), objetos [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) y objetos `EmfPlusTextureBrushData` (sección 2.2.2.45). Si está establecida, se DEBE especificar una matriz de transformación de espacio mundial a espacio de dispositivo 2x3 en el campo OptionalData del objeto de datos del pincel.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData y EmfPlusPathGradientBrushData. Si está establecida, se DEBE especificar un objeto [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) (sección 2.2.2.4) en el campo OptionalData del objeto de datos del pincel.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData y EmfPlusPathGradientBrushData. Si está establecida, se DEBE especificar un objeto [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) (sección 2.2.2.5) que especifica un patrón de mezcla a lo largo de un degradado horizontal en el campo OptionalData del objeto de datos del pincel.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData. Si está establecida, se DEBE especificar un objeto EmfPlusBlendFactors que especifica un patrón de mezcla a lo largo de un degradado vertical en el campo OptionalData del objeto de datos del pincel.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


Esta bandera es significativa en objetos EmfPlusPathGradientBrushData. Si está establecida, se DEBE especificar un[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) (sección 2.2.2.18) en el campo OptionalData del objeto de datos del pincel.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData y EmfPlusTextureBrushData. Si está establecida, el pincel DEBE estar ya corregido gamma; es decir, el brillo y la intensidad de salida se han corregido para coincidir con la imagen de entrada.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


Esta bandera es significativa en objetos EmfPlusTextureBrushData. Si está establecida, no DEBERÍA aplicarse una transformación de espacio mundial a espacio de dispositivo al pincel de textura.

