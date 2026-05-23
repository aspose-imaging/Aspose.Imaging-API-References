---
title: "Clase EmfPlusPathGradientBrushOptionalData"
type: docs
weight: 510
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | Inicializa una nueva instancia de la clase EmfPlusPathGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Obtiene o establece un patrón de mezcla opcional para el pincel de degradado de ruta. Si este campo está<br/> presente, DEBE contener ya sea un objeto EmfPlusBlendColors (sección 2.2.2.4), <br/> o un objeto EmfPlusBlendFactors (sección 2.2.2.5), pero NO DEBE contener ambos. <br/> La tabla a continuación muestra las combinaciones válidas de los indicadores EmfPlusPathGradientBrushData<br/> BrushData y los patrones de mezcla correspondientes: |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | Obtiene o establece un objeto opcional EmfPlusFocusScaleData (sección 2.2.2.18) que especifica <br/> escalas de foco para el pincel de degradado de ruta. Este campo DEBE estar presente si el<br/> indicador BrushDataFocusScales está establecido en el campo BrushDataFlags del <br/> objeto EmfPlusPathGradientBrushData. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación del espacio mundial al espacio del dispositivo para el pincel de degradado de ruta. <br/> Este campo DEBE estar presente si el indicador BrushDataTransform está establecido en el campo BrushDataFlags del objeto EmfPlusPathGradientBrushData. |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

Inicializa una nueva instancia de la clase EmfPlusPathGradientBrushOptionalData

