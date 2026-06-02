---
title: "Clase EmfPlusLinearGradientBrushOptionalData"
type: docs
weight: 450
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | Inicializa una nueva instancia de la clase EmfPlusLinearGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Obtiene o establece un patrón de mezcla opcional para el pincel de degradado lineal. Si este campo está presente, <br/>
            DEBE contener ya sea un objeto EmfPlusBlendColors (sección 2.2.2.4), <br/>
            o uno o dos objetos EmfPlusBlendFactors (sección 2.2.2.5), <br/>
            pero NO DEBE contener ambos. La tabla a continuación muestra las combinaciones válidas de <br/>
            indicadores BrushData de EmfPlusLinearGradientBrushData y los patrones de mezcla correspondientes:<br/>
            EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Obtiene el patrón de mezcla como factores de mezcla h. |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Obtiene el patrón de mezcla como factores de mezcla v. |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | Obtiene el patrón de mezcla como colores predefinidos. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una<br/>            transformación del espacio mundial al espacio del dispositivo para el pincel de degradado lineal. <br/>            Este campo DEBE estar presente si el indicador BrushDataTransform está establecido en el<br/>            campo BrushDataFlags del objeto EmfPlusLinearGradientBrushData. |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

Inicializa una nueva instancia de la clase EmfPlusLinearGradientBrushOptionalData

