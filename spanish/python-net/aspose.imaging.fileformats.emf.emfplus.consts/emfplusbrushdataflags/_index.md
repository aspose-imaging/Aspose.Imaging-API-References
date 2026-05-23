---
title: "EmfPlusBrushDataFlags Enumeration"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

Los indicadores BrushData especifican propiedades de los pinceles gráficos, incluyendo la presencia de campos de datos opcionales. Estos indicadores pueden combinarse para especificar múltiples opciones.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData y EmfPlusPathGradientBrushData.<br/>            Si está activado, se DEBE especificar un objeto [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) (sección 2.2.2.5) que define un patrón de mezcla a lo largo de un degradado horizontal en el campo OptionalData del objeto de datos del pincel. |
| BRUSH_DATA_BLEND_FACTORS_V | Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData.<br/>            Si está activado, se DEBE especificar un objeto EmfPlusBlendFactors que define un patrón de mezcla a lo largo de un degradado vertical en el campo OptionalData del objeto de datos del pincel. |
| BRUSH_DATA_DO_NOT_TRANSFORM | Esta bandera es significativa en objetos EmfPlusTextureBrushData.<br/>            Si está activado, NO DEBERÍA aplicarse una transformación de espacio mundial a espacio de dispositivo al pincel de textura. |
| BRUSH_DATA_FOCUS_SCALES | Esta bandera es significativa en objetos EmfPlusPathGradientBrushData.<br/>            Si está activado, se DEBE especificar un objeto [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) (sección 2.2.2.18) en el campo OptionalData del objeto de datos del pincel. |
| BRUSH_DATA_IS_GAMMA_CORRECTED | Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData y EmfPlusTextureBrushData.<br/>            Si está activado, el pincel DEBE estar ya corregido gamma; es decir, el brillo y la intensidad de salida han sido corregidos para coincidir con la imagen de entrada. |
| BRUSH_DATA_PATH | Esta bandera es significativa en objetos [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) (sección 2.2.2.29).<br/>            Si está activado, se DEBE especificar un objeto [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) (sección 2.2.2.6) en el campo BoundaryData del objeto de datos del pincel.<br/>            Si está desactivado, se DEBE especificar un objeto [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) (sección 2.2.2.7) en el campo BoundaryData del objeto de datos del pincel. |
| BRUSH_DATA_PRESET_COLORS | Esta bandera es significativa en objetos EmfPlusLinearGradientBrushData y EmfPlusPathGradientBrushData.<br/>            Si está activado, se DEBE especificar un objeto [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) (sección 2.2.2.4) en el campo OptionalData del objeto de datos del pincel. |
| BRUSH_DATA_TRANSFORM | Esta bandera es significativa en objetos [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) (sección 2.2.2.24), [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) y [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) (sección 2.2.2.45).<br/>            Si está activado, se DEBE especificar una matriz de transformación de espacio mundial a espacio de dispositivo 2x3 en el campo OptionalData del objeto de datos del pincel. |
